# antiV.1.0.0
Protect your device!
make your own Software
copy and paste this into an .bat:

@echo off
title Antivirus
echo Antivirus
echo created by Clinicz
:start
if exist virus.bat goto infected
cd C:\Windows\system32
if not exist virus.bat goto clean
:infected
echo warning virus detected
exit
del virus.bat
pause
goto start
:clean
echo System secure!
pause****
