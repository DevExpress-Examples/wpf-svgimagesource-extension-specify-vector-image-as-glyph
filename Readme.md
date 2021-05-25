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
