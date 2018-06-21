---
title: Microsoft Dynamics AX Retail Windows Phone Point of Sale
TOCTitle: Windows Phone Point of Sale
ms:assetid: 7ac49af3-c664-4dd0-ab35-0a0f477e0c3f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn741448(v=AX.60)
ms:contentKeyID: 62219725
ms.date: 10/26/2016
mtps_version: v=AX.60
---

# Microsoft Dynamics AX Retail Windows Phone Point of Sale [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Microsoft Dynamics AX 2012 for Retail Retail Modern POS includes sample code for Windows Phone Point of Sale in the Retail SDK.

The Windows Phone sample includes code for reports. To enable these reports, you need to uncomment the sample code in the Retail SDK and then add references to the Silverlight toolkit.

## Prerequisites

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Prerequisite</p></th>
<th><p>Details</p></th>
<th><p>Links</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Install WCF Data Services RTM Tools Installer</p></td>
<td><p>In order to generate server references, you need the WCF Data Services RTM Tools Installer. If you don’t have this version, the output will not be compatible with the Windows Phone architecture and the project will not compile.</p></td>
<td><p><a href="http://www.microsoft.com/en-us/download/details.aspx?id=39373">WCF Data Services RTM Tools Installer</a></p></td>
</tr>
<tr class="even">
<td><p>Install Silverlight libraries</p></td>
<td><p>You must install the Silverlight libraries. Newer versions of Silverlight are not supported for Windows Phone POS.</p></td>
<td><p><a href="http://silverlight.codeplex.com/releases/view/75888">Windows Phone Toolkit</a></p>
<p><a href="http://silverlight.codeplex.com/releases/view/36060">Silverlight 3 Toolkit</a></p></td>
</tr>
</tbody>
</table>


## Deploy Windows Phone POS to a device

To deploy the sample code to a Windows Phone device, you must remove some references and then deploy the code by using side-loading.

1.  In the Retail SDK, open **POS Clients** \> **WP8** \> **ViewModel** \> **packages.config**.

2.  Comment out or remove the following line:
    
        “ <package id="Microsoft.Composition" version="1.0.16" targetFramework="portable-win+net45" />

3.  Open **POS Clients** \> **WP8** \> **ViewModel** \> **ViewModel.csproj**.

4.  Comment out or remove the following lines:
    
            <Reference Include="System.Composition.AttributedModel">
              <HintPath>..\packages\Microsoft.Composition.1.0.16\lib\portable-net45+win8\System.Composition.AttributedModel.dll</HintPath>
            </Reference>
            <Reference Include="System.Composition.Convention">
              <HintPath>..\packages\Microsoft.Composition.1.0.16\lib\portable-net45+win8\System.Composition.Convention.dll</HintPath>
            </Reference>
            <Reference Include="System.Composition.Hosting">
              <HintPath>..\packages\Microsoft.Composition.1.0.16\lib\portable-net45+win8\System.Composition.Hosting.dll</HintPath>
            </Reference>
            <Reference Include="System.Composition.Runtime">
              <HintPath>..\packages\Microsoft.Composition.1.0.16\lib\portable-net45+win8\System.Composition.Runtime.dll</HintPath>
            </Reference>
            <Reference Include="System.Composition.TypedParts">
              <HintPath>..\packages\Microsoft.Composition.1.0.16\lib\portable-net45+win8\System.Composition.TypedParts.dll</HintPath>
            </Reference>

5.  Build and normally deploy the app on the device. For more information, see [Install Retail Modern POS](install-retail-modern-pos.md).

## Uncomment code for reports

In the Retail SDK, open **POS Clients** \> **WP8** \> **POS.sln**.

1.  In **Solution Explorer**, open **POS** \> **View** \> **ReportResultsPage.xaml**.

2.  Uncomment the following code in lines 77-91.
    
        <ItemsControl ItemsSource="{Binding Charts}">
                            <ItemsControl.ItemTemplate>   
                                <DataTemplate>
                                    <ctrl:ReportChartControl 
                                        ItemsSource="{Binding Path=Series}" 
                                        Width="Auto" 
                                        Height="300" 
                                        VerticalAlignment="Top" 
                                        Margin="10"/>
                                </DataTemplate>
                                
                            </ItemsControl.ItemTemplate>
                        </ItemsControl>

3.  In **Solution Explorer**, open **POS** \> **View** \> **CustomControls** \> **ReportChartControl.xaml**.

4.  Uncomment the code in lines 15, 17-21, and 27-33. Move the reference in line 15 after line 8. The result should look like this:
    
        <UserControl x:Class="Microsoft.Dynamics.Retail.Pos.View.ReportChartControl"
            xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
            xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
            xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
            xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
            xmlns:phone="clr-namespace:Microsoft.Phone.Controls;assembly=Microsoft.Phone"
            xmlns:shell="clr-namespace:Microsoft.Phone.Shell;assembly=Microsoft.Phone"  
            xmlns:toolkit="clr-namespace:Microsoft.Phone.Controls;assembly=Microsoft.Phone.Controls.Toolkit"
            xmlns:charting="clr-namespace:System.Windows.Controls.DataVisualization.Charting;assembly=System.Windows.Controls.DataVisualization.Toolkit"
            mc:Ignorable="d"
            FontFamily="{StaticResource PhoneFontFamilyNormal}"
            FontSize="{StaticResource PhoneFontSizeNormal}"
            Foreground="{StaticResource PhoneForegroundBrush}"
            d:DesignHeight="480" d:DesignWidth="480">
        
             xmlns:charting="clr-namespace:System.Windows.Controls.DataVisualization.Charting;assembly=System.Windows.Controls.DataVisualization.Toolkit" 
        
            
            <UserControl.Resources>
                <ResourceDictionary Source="/Microsoft.Dynamics.Retail.Pos.View;component/Resources/Resources.xaml"/>
            </UserControl.Resources>
            
            
            <Grid x:Name="LayoutRoot" Background="{StaticResource PhoneChromeBrush}">
                <ScrollViewer 
                        HorizontalScrollBarVisibility="Hidden"
                        VerticalScrollBarVisibility="Disabled">
                    
                    <charting:Chart
                        x:Name="chartControl"
                        Style="{StaticResource PhoneChartStyle}"
                        Template="{StaticResource PhoneChartPortraitTemplate}" FontSize="12">
                    </charting:Chart>
                    
                </ScrollViewer>
            </Grid>
        </UserControl>

5.  In **Solution Explorer**, open **POS** \> **View** \> **CustomControls** \> **ReportChartControl.xaml** \> **ReportChartControl.xaml.cs**.

6.  Uncomment the whole class.

7.  In **Solution Explorer**, open **POS** \> **View** \> **Resources** \> **Resources.xaml**.

8.  Uncomment lines 16-18 and move them after line 13. The result should look like the following snippet:
    
        <ResourceDictionary
            xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
            xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
            xmlns:res="clr-namespace:Microsoft.Dynamics.Retail.Pos.View.Resources"
            xmlns:phone="clr-namespace:Microsoft.Phone.Controls;assembly=Microsoft.Phone"
            xmlns:datavis="clr-namespace:System.Windows.Controls.DataVisualization;assembly=System.Windows.Controls.DataVisualization.Toolkit"
            xmlns:charting="clr-namespace:System.Windows.Controls.DataVisualization.Charting;assembly=System.Windows.Controls.DataVisualization.Toolkit"
            xmlns:chartingprimitives="clr-namespace:System.Windows.Controls.DataVisualization.Charting.Primitives;assembly=System.Windows.Controls.DataVisualization.Toolkit"
            xmlns:converter="clr-namespace:Microsoft.Dynamics.Retail.Pos.View.Converters">

9.  Uncomment lines 60-119.
    
    ``` 
        
        <ControlTemplate x:Key="PhoneChartPortraitTemplate" TargetType="charting:Chart">
            <Grid>
                <Grid.RowDefinitions>
                    <RowDefinition Height="Auto"/>
                    <RowDefinition Height="Auto"/>
                    <RowDefinition Height="Auto"/>
                </Grid.RowDefinitions>          
                <datavis:Legend x:Name="Legend"
                    Grid.Row="2"
                    Header="{TemplateBinding LegendTitle}"
                    Style="{TemplateBinding LegendStyle}">
                    <datavis:Legend.ItemsPanel>
                        <ItemsPanelTemplate>
                            <StackPanel Orientation="Horizontal"/>
                        </ItemsPanelTemplate>
                    </datavis:Legend.ItemsPanel>
                    <datavis:Legend.Template>
                        <ControlTemplate TargetType="datavis:Legend">
                            <Border
                                Background="{TemplateBinding Background}">
                                <Grid>
                                    <Grid.RowDefinitions>
                                        <RowDefinition Height="Auto" />
                                        <RowDefinition />
                                    </Grid.RowDefinitions>
                                    <datavis:Title
                                        Grid.Row="0"
                                        x:Name="HeaderContent"
                                        Content="{TemplateBinding Header}"
                                        ContentTemplate="{TemplateBinding HeaderTemplate}"
                                        Style="{TemplateBinding TitleStyle}"/>
                                    <ScrollViewer
                                        Grid.Row="1"
                                        HorizontalScrollBarVisibility="Auto"
                                        VerticalScrollBarVisibility="Disabled"
                                        BorderThickness="0"
                                        Padding="0"
                                        IsTabStop="False">
                                        <ItemsPresenter
                                            x:Name="Items"
                                            Margin="5,0,5,5"/>
                                    </ScrollViewer>
                                </Grid>
                            </Border>
                        </ControlTemplate>
                    </datavis:Legend.Template>
                </datavis:Legend>
                <chartingprimitives:EdgePanel
                    Grid.Column="0"
                    Grid.Row="1"
                    x:Name="ChartArea"
                    Style="{TemplateBinding ChartAreaStyle}">
                    <Grid
                        Canvas.ZIndex="-1"
                        Style="{TemplateBinding PlotAreaStyle}" />
                </chartingprimitives:EdgePanel>
            </Grid>
        </ControlTemplate>
        
    ```

10. Uncomment lines 268-417.
    
    ``` 
        
        <Style x:Key="PhoneChartStyle" TargetType="charting:Chart">
            <Setter Property="IsTabStop" Value="False" />
            <Setter Property="Padding" Value="3" />
            <Setter Property="VerticalAlignment" Value="Top"/>
            <Setter Property="Background" Value="Transparent"/>
            <Setter Property="LegendStyle">
                <Setter.Value>
                    <Style TargetType="datavis:Legend">
                        <Setter Property="HorizontalAlignment" Value="Center"/>
                        <Setter Property="VerticalAlignment" Value="Center"/>
                        <Setter Property="Margin" Value="1"/>
                    </Style>
                </Setter.Value>
            </Setter>
            <Setter Property="ChartAreaStyle">
                <Setter.Value>
                    <Style TargetType="Panel">
                        <Setter Property="MinWidth" Value="100" />
                        <Setter Property="Height" Value="225" />
                        <Setter Property="Background" Value="Transparent"/>
                        <Setter Property="Margin" Value="3, 13, 3, 0" />
                    </Style>
                </Setter.Value>
            </Setter>
            <Setter Property="PlotAreaStyle">
                <Setter.Value>
                    <Style TargetType="Grid">
                        <Setter Property="Background" Value="Transparent"/>
                        <Setter Property="Margin" Value="3" />
                    </Style>
                </Setter.Value>
            </Setter>
            <Setter Property="Template" Value="{StaticResource PhoneChartPortraitTemplate}"/>
        </Style>
        <Style x:Key="PhoneChartColumnDataPointStyle" TargetType="charting:ColumnDataPoint">        
            <Setter Property="Template">
                <Setter.Value>
                    <ControlTemplate TargetType="charting:ColumnDataPoint">
                        <Border
                            BorderBrush="{TemplateBinding BorderBrush}"
                            BorderThickness="{TemplateBinding BorderThickness}"
                            Opacity="0"
                            x:Name="Root">
                            <VisualStateManager.VisualStateGroups>
                                <VisualStateGroup x:Name="CommonStates">
                                    <VisualStateGroup.Transitions>
                                        <VisualTransition GeneratedDuration="0:0:0.1"/>
                                    </VisualStateGroup.Transitions>
                                    <VisualState x:Name="Normal"/>
                                    <VisualState x:Name="MouseOver">
                                        <Storyboard>
                                            <DoubleAnimation
                                                Storyboard.TargetName="MouseOverHighlight"
                                                Storyboard.TargetProperty="Opacity"
                                                To="0.6"
                                                Duration="0"/>
                                        </Storyboard>
                                    </VisualState>
                                </VisualStateGroup>
                                <VisualStateGroup x:Name="SelectionStates">
                                    <VisualStateGroup.Transitions>
                                        <VisualTransition GeneratedDuration="0:0:0.1"/>
                                    </VisualStateGroup.Transitions>
                                    <VisualState x:Name="Unselected"/>
                                    <VisualState x:Name="Selected">
                                        <Storyboard>
                                            <DoubleAnimation
                                                Storyboard.TargetName="SelectionHighlight"
                                                Storyboard.TargetProperty="Opacity"
                                                To="0.6"
                                                Duration="0"/>
                                        </Storyboard>
                                    </VisualState>
                                </VisualStateGroup>
                                <VisualStateGroup x:Name="RevealStates">
                                    <VisualStateGroup.Transitions>
                                        <VisualTransition GeneratedDuration="0:0:0.5"/>
                                    </VisualStateGroup.Transitions>
                                    <VisualState x:Name="Shown">
                                        <Storyboard>
                                            <DoubleAnimation
                                                Storyboard.TargetName="Root"
                                                Storyboard.TargetProperty="Opacity"
                                                To="1"
                                                Duration="0"/>
                                        </Storyboard>
                                    </VisualState>
                                    <VisualState x:Name="Hidden">
                                        <Storyboard>
                                            <DoubleAnimation
                                                Storyboard.TargetName="Root"
                                                Storyboard.TargetProperty="Opacity"
                                                To="0"
                                                Duration="0"/>
                                        </Storyboard>
                                    </VisualState>
                                </VisualStateGroup>
                            </VisualStateManager.VisualStateGroups>
                            <Grid>
                                <Rectangle Fill="{TemplateBinding Background}" Opacity="0.75"></Rectangle>
                                <Grid
                                    Background="Transparent"
                                    Margin="0 -20 0 0"
                                    HorizontalAlignment="Center"
                                    VerticalAlignment="Top">
                                    <TextBlock
                                        Text="{Binding Value, Converter={StaticResource DecimalConverter}}"
                                        FontWeight="Bold"
                                        Margin="2" 
                                        TextWrapping="Wrap" 
                                        FontSize="10"/>
                                </Grid>
                                <ToolTipService.ToolTip>
                                    <StackPanel Orientation="Horizontal" Margin="2,2,2,2">
                                        <ContentControl Content="{Binding Key}"></ContentControl>
                                        <ContentControl Content="{Binding Value, Converter={StaticResource DecimalConverter}}"></ContentControl>
                                    </StackPanel>
                                </ToolTipService.ToolTip>
                            </Grid>
                        </Border>
                    </ControlTemplate>
                </Setter.Value>
            </Setter>
        </Style>    
        <Style x:Key="PhoneChartAxisLabelStyle" TargetType="charting:AxisLabel">
            <Setter Property="FontSize" Value="10" />
            <Setter Property="Template">
                <Setter.Value>
                    <ControlTemplate TargetType="charting:AxisLabel">
                            <TextBlock 
                                Text="{TemplateBinding FormattedContent}" 
                                TextWrapping="Wrap" 
                                Width="50" 
                                TextAlignment="Center"/>
                    </ControlTemplate>
                </Setter.Value>
            </Setter>
        </Style>
        <Style x:Key="PhoneChartYAxisLabelStyle" TargetType="charting:NumericAxisLabel">
            <Setter Property="FontSize" Value="9" />        
            <Setter Property="Template">
                <Setter.Value>
                    <ControlTemplate TargetType="charting:NumericAxisLabel">
                        <TextBlock Text="{Binding Converter={StaticResource DecimalConverter}}"/>
                    </ControlTemplate>
                </Setter.Value>
            </Setter>
        </Style>
        
    ```

11. In **Solution Explorer**, open **POS** \> **ViewModel** \> **Operations** \> **ViewReportsOperation.cs**.

12. Uncomment line 30, and then comment out lines 31-34. The result should look like this:
    
        using Microsoft.Dynamics.Retail.Pos.View;
        using Microsoft.Dynamics.Retail.Pos.View.Resources;
        using System.Windows;
        
        namespace Microsoft.Dynamics.Retail.Pos.ViewModel
        {
            /// <summary>
            /// Represents the view reports operation.
            /// </summary>
            [OperationId(OperationType.ViewReports)]
            public class ViewReportsOperation : OperationBase
            {
                /// <summary>
                /// Defines the method to be called when the command is invoked.
                /// </summary>
                /// <param name="parameter">Data used by the command. If the command does not require data to be passed, this object can be set to null.</param>
                public override void Execute(object parameter)
                {
                    base.Execute(parameter);
        
                    this.NavigationManager.Navigate<ReportsPage, ReportsViewModel>(parameter);
                    /*
                    this.MessageManager.ShowMessageBox(
                       AppResources.Feature_Disabled,
                       AppResources.MessageBoxTitle_Error,
                       MessageBoxButton.OK);
                     */
                }
            }
        }

## Add references to the Silverlight toolkit for reports

After you uncomment the Windows Phone report code, you need to add the references to the Silverlight toolkit. The references must be added from the toolkit location where the Silverlight SDKs are installed.

1.  Navigate to the Silverlight install folder in View.csproj.

2.  Remove references from the **View** project for assemblies System.Windows.Controls.DataVisualization.Toolkit.dll and System.Windows.Controls.dll.

3.  Add a reference by browsing to the location of System.Windows.Controls.DataVisualization.Toolkit.dll.
    

    > [!NOTE]
    > <P>It should be in C:\Program Files\Microsoft SDKs\Silverlight\v3.0\Toolkit\Nov09\Bin.</P>



4.  Add reference by browsing to the location of System.Windows.Controls.dll. It should be in C:\\Program Files\\Microsoft SDKs\\Silverlight\\v3.0\\Libraries\\Client\\. For this assembly any version will work (v4.0 or v5.0).

5.  Build the project and run the application.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

