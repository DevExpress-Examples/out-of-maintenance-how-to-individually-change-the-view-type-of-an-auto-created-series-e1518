<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/ChangeViewOfAnAutoSeries/Form1.cs) (VB: [Form1.vb](./VB/ChangeViewOfAnAutoSeries/Form1.vb))
<!-- default file list end -->
# How to individually change the view type of an auto-created series

This example demonstrates how an [auto-created series](https://docs.devexpress.com/WindowsForms/6562/controls-and-libraries/chart-control/provide-data/generate-series-from-a-data-source) (a series generated automatically based on the series template settings) can be accessed at runtime to individually change its [view type](https://docs.devexpress.com/WindowsForms/6761/controls-and-libraries/chart-control/series-views).

This is performed in the [ChartControl.BoundDataChanged](https://docs.devexpress.com/WindowsForms/DevExpress.XtraCharts.ChartControl.BoundDataChanged?p=netframework) event.
