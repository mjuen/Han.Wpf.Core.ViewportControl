# Han.Wpf.Core.ViewportControl
A Wpf Viewport Control that provides pan and zoom functionality based on .NET Core 3.1

This is a fork of ![Han.Wpf.ViewportControl](https://github.com/ahancock1/Han.Wpf.ViewportControl)

## Installation

    Install-Package Han.Wpf.ViewportControl
    
## Documentation

### Themes
Include in App.xaml

    <Application.Resources>

        <ResourceDictionary Source="pack://application:,,,/Han.Wpf.ViewportControl;component/Themes/Generic.xaml" />

    </Application.Resources>

### Usage

    <controls:Viewport MinZoom="1" MaxZoom="50" ZoomSpeed="1.1">

        <Image Source="{Binding}" />

    </controls:Viewport>
