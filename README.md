# WinWaitActive
Start Mysourcecontrol.exe Run("C:\Prigram Files\MySourceControl\Mysourcecontrol.exe") ; Wait until the window with My Source Control title becomes active Local $hWnd = WinWaitActive("My Source Control","") ; Write the user and password Send("my.user") Send("{TAB}")
