---
type: Object
---
---
##### shortDescription
Configures column fixing.

---
When the width of all columns exceeds the widget width, horizontal scrolling appears. If specific columns should be on screen constantly regardless of how far the widget is scrolled, allow a user to fix them at runtime using the context menu. For this, set the **columnFixing**.[enabled](/api-reference/10%20UI%20Widgets/GridBase/1%20Configuration/columnFixing/enabled.md '{basewidgetpath}/Configuration/columnFixing/#enabled') option to **true**.

![DevExtreme HTML5 JavaScript jQuery Angular Knockout Widget DataGrid ColumnFixing](/images/DataGrid/visual_elements/column_fixing.png)

When you enable column fixing, [command columns](/concepts/05%20Widgets/DataGrid/15%20Columns/10%20Column%20Types/4%20Command%20Columns.md '/Documentation/Guide/Widgets/DataGrid/Columns/Column_Types/Command_Columns/') become fixed automatically. 

#include common-demobutton with {
    url: "https://js.devexpress.com/Demos/WidgetsGallery/Demo/Data_Grid/ColumnCustomization/jQuery/Light/"
}

#####See Also#####
- [Column Fixing](/concepts/05%20Widgets/DataGrid/15%20Columns/30%20Column%20Fixing.md '/Documentation/Guide/Widgets/DataGrid/Columns/Column_Fixing/')