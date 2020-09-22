<div align="center">

## Lock a Windows NT Workstation in One Line of Code


</div>

### Description

Simple. This locks a Windows NT-based computer in one line of code. This would be the same as the user pressing CTRL-ALT-DEL and pressing "Lock Computer". NOTE: You must have WinNT 5.0 or later. (that's 2000 or XP)
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Doctor Evil](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/doctor-evil.md)
**Level**          |Beginner
**User Rating**    |5.0 (35 globes from 7 users)
**Compatibility**  |VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Windows API Call/ Explanation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/windows-api-call-explanation__1-39.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/doctor-evil-lock-a-windows-nt-workstation-in-one-line-of-code__1-24090/archive/master.zip)

### API Declarations

```
Public Declare Sub LockWorkStation Lib "user32.dll" ()
```


### Source Code

```
Private Sub Command1_Click()
LockWorkStation
End Sub
```

