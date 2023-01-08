# MacroSchedule-UCN

1.Install https://www.mjtnet.com
2.Create a new Macro and include this code :
GetActiveWindow>title,,,,
IF>title=Ultimate Custom Night
MouseMove>1737,916
LClick
Endif
, set the hotkey and save it.

3.Create a new Macro and include this code :
GetActiveWindow>title,,,,
IF>title=Ultimate Custom Night
MouseMove>672,934
LClick
Endif
, set the hotkey and save it.

Atantion: You probaly need to stop the process via task manger afterwords (ctrl+shift+esc)
!!!While the programm runs the hotkeys are logged so they will always try to access the macro!!!
