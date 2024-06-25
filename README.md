<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/519170935/22.2.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T1105889)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->
# Grid for Blazor - How to highlight a row on hover

This example highlights a Blazor Grid ([DxGrid](https://docs.devexpress.com/Blazor/403143/grid)) row when a user hovers over the row.

![Blazor DxGrid highlight a row on hower](images/highlight-row.png)

Our Blazor Grid's [CustomizeElement](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxGrid.CustomizeElement) event allows you to customize the [DxGrid](https://docs.devexpress.com/Blazor/403143/grid) rows and cells. This event's [ElementType](https://docs.devexpress.com/Blazor/DevExpress.Blazor.GridCustomizeElementEventArgs.ElementType) argument property gets the type associated with the processed element. Use the event's [CssClass](https://docs.devexpress.com/Blazor/DevExpress.Blazor.GridCustomizeElementEventArgs.CssClass) argument property to apply a CSS class to the processed element.

## Files to Review

- [Index.razor](./CS/HighlightHoveredRow/Pages/Index.razor)

## Documentation

- [Grid: Edit Data](https://docs.devexpress.com/Blazor/403454/grid/edit-data-and-validate-input)
- [Grid: Selection](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxGrid.SelectionMode)

## More Examples
 
- [Grid for Blazor - How to edit a row on a separate page](https://github.com/DevExpress-Examples/blazor-DxGrid-Separate-Edit-Form)
<!-- feedback -->
## Does this example address your development requirements/objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=blazor-dxgrid-highlight-row-on-hover&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=blazor-dxgrid-highlight-row-on-hover&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
