# notepad
If $OSVersion = 'Win7' Or $OSVersion = 'Win7SP1' Or $OSVersion = 'Win7X64' Or $OSVersion = 'Win7SP1x64' Then     $ProgramFiles = "C:\Programs\" Else     $ProgramFiles = "C:\Program Files (x86)" EndIf  $sRunFile = 'C:\Dnload\9xAddons\TestRunVer.5.28.exe' ;~ $sRunFile = @WindowsDir&amp;'\notepad.exe'   ; decomment for testing purposes If Not FileExists($sRunFile) Then
