<div align="center">

## Showing icons/images on your toolbar \(Bugfix for XP Style\)


</div>

### Description

This article will help you (hopefully) when you want to use icons on your toolbars using the XP style.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Mathieu](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/mathieu.md)
**Level**          |Beginner
**User Rating**    |3.8 (15 globes from 4 users)
**Compatibility**  |VB\.NET
**Category**       |[Graphics/ Sound](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/graphics-sound__10-15.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/mathieu-showing-icons-images-on-your-toolbar-bugfix-for-xp-style__10-1791/archive/master.zip)





### Source Code

If you want to use XP style in your vb.net apps, you can simply use the EnableVisualThemes property (application.EnableVisualThemes())
But there is a small bug in vs.net 2003.
If you want to use a toolbar with (xp) icons, those icons will not appear at runtime.
This code will help you:
<hr size="0">
[code]
Sub new()<br>
 'Enable XP Look<br>
 Application.EnableVisualStyles()<br>
 Application.DoEvents()<br>
 Application.run(new frmMain)<br>
end sub<br>
[/code]
<hr size="0">

