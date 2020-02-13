---
default: true
type: Boolean
---
---
##### shortDescription
Specifies whether or not to display the header of a hidden column in the [column chooser](/concepts/05%20Widgets/DataGrid/001%20Visual%20Elements/120%20Column%20Chooser.md '/Documentation/Guide/Widgets/DataGrid/Visual_Elements/#Column_Chooser').

---
A grid column is considered hidden when its [visible](/api-reference/10%20UI%20Widgets/dxDataGrid/1%20Configuration/columns/visible.md '/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/columns/#visible') option is *false*. By default, the header of a hidden column is displayed in the column chooser. If you require this header to be omitted from the column chooser, set the **showInColumnChooser** option to *false*.