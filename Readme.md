<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/MinimalisticReportPreviewDemo/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/MinimalisticReportPreviewDemo/MainWindow.xaml))
* **[MainWindow.xaml.cs](./CS/MinimalisticReportPreviewDemo/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/MinimalisticReportPreviewDemo/MainWindow.xaml.vb))**
<!-- default file list end -->
# DocumentPreview - how to disable toolbar dragging


<p>To prevent Bar from being dragged by a user, set the <a href="http://documentation.devexpress.com/#WPF/DevExpressXpfBarsBar_ShowDragWidgettopic">Bar.ShowDragWidget Property </a> of the "DocumentPreviewToolBar" to false in the <strong>BarManager.Loaded</strong> event handler instead of the corresponding event handler of the main window.</p>

<br/>


