The grid control can render cells with simple content first, and only then proceed to cells with complex content (filter row, command columns, editors and columns with checkboxes). In this case, the control shows content sooner and the app UI can be perceived as more responsive. To load simple content first, use the [renderAsync](/api-reference/10%20UI%20Components/GridBase/1%20Configuration/renderAsync.md '/Documentation/ApiReference/UI_Components/dxDataGrid/Configuration/#renderAsync') property. You can also enable [the same property](/api-reference/_hidden/GridBaseColumn/renderAsync.md '/Documentation/ApiReference/UI_Components/dxDataGrid/Configuration/columns/#renderAsync') for individual columns if they use content-heavy [cell templates](/api-reference/_hidden/dxDataGridColumn/cellTemplate.md '/Documentation/ApiReference/UI_Components/dxDataGrid/Configuration/columns/#cellTemplate').