<div align="center">

## Add a giant crosshair for your whole app\!\!\!


</div>

### Description

Does what the title says, adds a big crosshair that follows your mouse in your whole application, dig it!
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Joshua Conklin](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/joshua-conklin.md)
**Level**          |Beginner
**User Rating**    |4.0 (12 globes from 3 users)
**Compatibility**  |VB 5\.0
**Category**       |[Custom Controls/ Forms/  Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/custom-controls-forms-menus__1-4.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/joshua-conklin-add-a-giant-crosshair-for-your-whole-app__1-29300/archive/master.zip)





### Source Code

```
' Add a line named Line1 , verticlly up and down
' through the center of your form
' Now add another line named Line2 ,
' horozontally accross the whole form
' if you dont understand look at the screenshot
' then just copy and paste this code
Private Sub Form_MouseMove(Button As Integer, Shift As Integer, X As Single, Y As Single)
  Line1.X1 = X
  Line1.X2 = X
  Line2.Y1 = Y
  Line2.Y2 = Y
End Sub
```

