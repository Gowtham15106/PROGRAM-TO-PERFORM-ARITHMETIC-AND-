# PROGRAM-TO-PERFORM-ARITHMETIC-AND-SOURCE CODE:Private Sub CommandButton1_Click()If (1 = 1) And (0 = 0) ThenMsgBox "AND evaluated to TRUE", vbOKOnly, "AND operator"ElseMsgBox "AND evaluated to FALSE", vbOKOnly, "AND operator"End IfEnd SubPrivate Sub CommandButton2_Click()If (1 = 1) Or (5 = 0) ThenMsgBox "OR evaluated to TRUE", vbOKOnly, "OR operator"ElseMsgBox "OR evaluated to FALSE", vbOKOnly, "OR operator"End IfEnd SubPrivate Sub CommandButton3_Click()If Not (0 = 0) ThenMsgBox "NOT evaluated to TRUE", vbOKOnly, "NOT operator"ElseMsgBox "NOT evaluated to FALSE", vbOKOnly, "NOT operator"End IfEnd Sub
