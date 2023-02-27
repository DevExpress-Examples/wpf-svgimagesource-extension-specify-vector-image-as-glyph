<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128642536/22.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T407507)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->

# WPF SvgImageSource Extension - Specify a Vector Image as a Glyph 

This example uses the [SvgImageSource](https://docs.devexpress.com/WPF/DevExpress.Xpf.Core.SvgImageSourceExtension) extension to specify the [BarButtonItem](https://docs.devexpress.com/WPF/DevExpress.Xpf.Bars.BarButtonItem)'s glyph.

![image](https://user-images.githubusercontent.com/65009440/221585879-619c64b1-3ef4-4676-8f8c-9dd5d3041006.png)

You can reference a resource in xaml as follows:

```xaml
xmlns:dx="http://schemas.devexpress.com/winfx/2008/xaml/core"

<Image Source="{dx:SvgImageSource Uri=Images/Notebook.svg}"/>
```

## Files to Review

* [MainWindow.xaml](./CS/DXSample/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/DXSample/MainWindow.xaml))

## Documentation

* [SVG Images](https://docs.devexpress.com/WPF/120131/common-concepts/images/svg-images)
* [SvgImageSourceExtension](https://docs.devexpress.com/WPF/DevExpress.Xpf.Core.SvgImageSourceExtension)

## More Examples

* [Specify SVG Images Manually](https://github.com/DevExpress-Examples/how-to-specify-svg-images-manually-t612359)
* [Use Palettes to Replace Colors for SVG Images](https://github.com/DevExpress-Examples/how-to-replace-colors-for-svg-images-using-palettes-t615789)
