```'Write a VBA macro to save the active workbook with a new name.
Sub newName()
Dim workbookName As String
workbookName = ActiveWorkbook.Name
ActiveWorkbook.SaveAs ("Project based learning new")
End Sub```