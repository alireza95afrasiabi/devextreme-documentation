---
id: dxResizable.Options.onResize
type: function(e)
default: null
---
---
##### shortDescription
A function that is executed each time the UI component is resized by one pixel.

##### param(e): ui/resizable:ResizeEvent
Information about the event.

##### field(e.component): {WidgetName}
The UI component's instance.

##### field(e.element): DxElement
#include common-ref-elementparam with { element: "UI component" }

##### field(e.event): event
#include common-ref-eventparam

##### field(e.height): Number
The UI component's current height.

##### field(e.model): any
Model data. Available only if Knockout is used.

##### field(e.width): Number
The UI component's current width.

---
