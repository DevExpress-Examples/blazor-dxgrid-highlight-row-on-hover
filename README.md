<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/519170935/22.1.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T1105889)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# Grid for Blazor - How to highlight a row on hover

This example demonstrates how to highlight a [DxGrid](https://docs.devexpress.com/Blazor/403143/grid) row when a user hovers over the row.

![Blazor DxGrid highlight a row on hower](highlight-row.png)

The [CustomizeElement](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxGrid.CustomizeElement) event allows you to customize the [DxGrid](https://docs.devexpress.com/Blazor/403143/grid)'s rows and cells. This event's [ElementType](https://docs.devexpress.com/Blazor/DevExpress.Blazor.GridCustomizeElementEventArgs.ElementType) argument property gets the type of the processed element. Use event's [CssClass](https://docs.devexpress.com/Blazor/DevExpress.Blazor.GridCustomizeElementEventArgs.CssClass) argument property to apply a CSS class to the processed element.

## Files to Look At

- [Index.razor](./CS/HighlightHoveredRow/Pages/Index.razor)

## Documentation

- [Grid: Edit Data](https://docs.devexpress.com/Blazor/403454/grid/edit-data-and-validate-input)
- [Grid: Selection](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxGrid.SelectionMode)

## More Examples

- [Grid for Blazor - How to edit a row on a separate page](https://github.com/DevExpress-Examples/blazor-DxGrid-Separate-Edit-Form)
