<div align="center">

## \!\!\!\*Hide the Mouse Pointer\!\!  EASY\!\*\!\!\!


</div>

### Description

This simple code hides the mouse pointer when you want to. (o:
 
### More Info
 
Make a new project. Add a module. Add 2 Command Buttons.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[SeeD](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/seed.md)
**Level**          |Unknown
**User Rating**    |4.1 (98 globes from 24 users)
**Compatibility**  |VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/seed-hide-the-mouse-pointer-easy__1-2902/archive/master.zip)





### Source Code

```
'put this in your module
Declare Function ShowCursor& Lib "user32" _
(ByVal bShow As Long)
'Add this code to Command1.
Private Sub Command1_Click()
ShowCursor (bShow = True)
End Sub
'Add this to Command2.
Private Sub Command2_Click()
ShowCursor (bShow = False)
End Sub
'ok, that's it. (o:
```

