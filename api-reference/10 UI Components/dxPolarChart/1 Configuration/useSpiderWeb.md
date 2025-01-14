---
id: dxPolarChart.Options.useSpiderWeb
type: Boolean
default: false
---
---
##### shortDescription
Indicates whether or not to display a "spider web".

---
In a polar coordinate system, the argument axis is a circle because it tracks a continuous angle change. When the argument in the chart's data source is discrete, you may want to display the argument axis as a discrete axis. For this purpose, set the **useSpiderWeb** property to **true**. In this instance, the argument axis, as well as the value axis' grid lines, will be displayed by straight lines between axis ticks/grid lines.

![UseSpiderWeb ChartJS](/images/ChartJS/UseSpiderWeb.png)

The spider web property is supported in the following series types.

- [line](/api-reference/10%20UI%20Components/dxPolarChart/5%20Series%20Types/LineSeries '/Documentation/ApiReference/UI_Components/dxPolarChart/Series_Types/LineSeries/')
- [area](/api-reference/10%20UI%20Components/dxPolarChart/5%20Series%20Types/AreaSeries '/Documentation/ApiReference/UI_Components/dxPolarChart/Series_Types/AreaSeries/')
- [scatter](/api-reference/10%20UI%20Components/dxPolarChart/5%20Series%20Types/ScatterSeries '/Documentation/ApiReference/UI_Components/dxPolarChart/Series_Types/ScatterSeries/')

[note]A spider web demands that the [discreteAxisDivisionMode](/api-reference/10%20UI%20Components/dxPolarChart/1%20Configuration/commonAxisSettings/discreteAxisDivisionMode.md '/Documentation/ApiReference/UI_Components/dxPolarChart/Configuration/commonAxisSettings/#discreteAxisDivisionMode') property is set to *'crossLabels'* and the [firstPointOnStartAngle](/api-reference/10%20UI%20Components/dxPolarChart/1%20Configuration/argumentAxis/firstPointOnStartAngle.md '/Documentation/ApiReference/UI_Components/dxPolarChart/Configuration/argumentAxis/#firstPointOnStartAngle') property is set to **true**. Thus, do not change the values of these property so that the spider web saves its look.

#include btn-open-demo with {
    href: "https://js.devexpress.com/Demos/WidgetsGallery/Demo/Charts/SpiderWeb/"
}