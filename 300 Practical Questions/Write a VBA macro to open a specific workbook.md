```Public Sub RunSW()
Call SpecificWorkbook("D:\Coding\Excel VBA\Udemy\Projects-Practical Learnings\", "Unlock Excel VBA and Excel Macros.xlsx")
End Sub

Public Sub SpecificWorkbook(filePath As String, fileName As String)

Workbooks.Open (filePath + fileName)
'use & instead of + sign

Workbooks(fileName).Close

End Sub```