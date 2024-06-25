<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/399434660/21.1.5%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T1024041)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->
# Dashboard for MVC - How to store dashboard state in the dashboard layout

This example illustrates how to create and store a [custom property](https://docs.devexpress.com/Dashboard/401702/web-dashboard/ui-elements-and-customization/create-custom-properties) to save the [Dashboard State](https://docs.devexpress.com/Dashboard/119765/web-dashboard/aspnet-mvc-dashboard-extension/manage-dashboard-state) along with the dashboard layout (XML).

The `DashboardState` custom property is stored at the Dashboard level. The following events are handled on the client side:

* [DashboardControl.onDashboardInitialized](https://docs.devexpress.com/Dashboard/js-DevExpress.Dashboard.DashboardControlOptions#js_devexpress_dashboard_dashboardcontroloptions_ondashboardinitialized) - to read the dashboard state from a custom property.
* [DashboardControl.onDashboardStateChanged](https://docs.devexpress.com/Dashboard/js-DevExpress.Dashboard.DashboardControlOptions#js_devexpress_dashboard_dashboardcontroloptions_ondashboardstatechanged) - to save the changed dashboard state to a custom property.

See the following article for information on how to store a custom property value at the Dashboard level: [Dashboard Description - Custom Property](https://docs.devexpress.com/Dashboard/401710/web-dashboard/ui-elements-and-customization/create-custom-properties/dashboard-description-custom-property).

<!-- default file list -->
## Files to Look at

* [DashboardConfig.cs](./CS/App_Start/DashboardConfig.cs)
* [Index.cshtml](./CS/Views/Home/Index.cshtml)
* [DashboardStateExtension.js](./CS/Scripts/DashboardStateExtension.js)
* [dashboard1.xml](./CS/App_Data/Dashboards/dashboard1.xml)

<!-- default file list end -->


## Documentation

- [Create Custom Properties](https://docs.devexpress.com/Dashboard/401702/web-dashboard/ui-elements-and-customization/create-custom-properties)
- [Dashboard Description - Custom Property](https://docs.devexpress.com/Dashboard/401710/web-dashboard/ui-elements-and-customization/create-custom-properties/dashboard-description-custom-property)
- [Manage Dashboard State in ASP.NET MVC Dashboard](https://docs.devexpress.com/Dashboard/119765/web-dashboard/aspnet-mvc-dashboard-extension/manage-dashboard-state)

## More Examples

- [Dashboard for MVC - Custom Properties](https://github.com/DevExpress-Examples/asp-net-mvc-dashboard-custom-properties-sample)
- [Dashboard for ASP.NET Core - How to implement dependent custom properties in a custom item](https://github.com/DevExpress-Examples/CustomItemDependentProperties)
- [Dashboard for MVC - How to customize a dashboard before displaying it in a browser](https://github.com/DevExpress-Examples/how-to-customize-a-dashboard-before-displaying-it-in-a-browser-t596822)
<!-- feedback -->
## Does this example address your development requirements/objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=mvc-dashboard-custom-properties-state&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=mvc-dashboard-custom-properties-state&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
