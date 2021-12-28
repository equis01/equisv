cd C:\Windows\Temp
DEL /F/Q/S *.* > NUL

cd %temp%
DEL /F/Q/S *.* > NUL

cd C:\Windows\Prefetch
DEL /F/Q/S *.* > NUL

cls

ipconfig
ipconfig /flushdns
ipconfig /renew

cls

rd /s /q C:\$Recycle. bin

cls

defrag c: /a
start msedge "equisv.xyz"

EN CASO DE QUE TU DISPOSITIVO SOLICITE DEFRAGMENTACION BORRA ESTE TEXTO Y SOLO DEJA LO SIGUIENTE defrag c: /u /v
