<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128659399/24.2.1%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E4652)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->

# WPF PageView - Create Page Content Container and Bind It to Data

This example demonstrates how to create a [WPF PageView](https://docs.devexpress.com/WPF/DevExpress.Xpf.WindowsUI.PageView), bind it to data (`EmployeesData`), and use templates to visualize data items and item headers.

![WPF PageView - Create Page Content Container, DevExpress](https://raw.githubusercontent.com/DevExpress-Examples/how-to-create-a-pageview-and-populate-it-with-data-e4652/22.2.2%2B/i/wpf-pageview-devexpress.png)

```xaml
<dxwui:PageView AnimationType="SlideHorizontal" Header="Page View"
      ItemsSource="{Binding DataSource}"
      ItemTemplate="{StaticResource ItemHeaderTemplate}"
      ContentTemplate="{StaticResource ItemContentTemplate}"/>
```

## Files to Review

* [MainWindow.xaml](./CS/PageViewSample/MainWindow.xaml)
* [DataStorage.cs](./CS/PageViewSample/DataStorage.cs)
* [MainWindow.xaml.cs](./CS/PageViewSample/MainWindow.xaml.cs)


## Documentation

* [Create a PageView and Populate It with Data (Step-by-Step Tutorial)](https://docs.devexpress.com/WPF/15028/controls-and-libraries/windows-modern-ui/examples/how-to-create-a-pageview-and-populate-it-with-data?p=netframework)
* [Windows Modern UI for WPF](https://docs.devexpress.com/WPF/15018/controls-and-libraries/windows-modern-ui)
<!-- feedback -->
## Does this example address your development requirements/objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=wpf-pageview-create-bind-to-data&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=wpf-pageview-create-bind-to-data&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
