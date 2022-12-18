<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128642536/22.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T407507)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/DXSample/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/DXSample/MainWindow.xaml))
<!-- default file list end -->
# How to use the SvgImageSource extension to specify a vector image as BarButtonItem's glyph 


The SvgImageSource extension allows you to specify a vector image as BarButtonItem's glyph . You can reference a resource in xaml as follows:<br>


```xaml
Glyph="{dx:SvgImageSource Uri=Images/Notebook.svg}"
```


where **dx** is the `xmlns:dx="http://schemas.devexpress.com/winfx/2008/xaml/core"` namespace.
