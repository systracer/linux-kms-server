# linux-kms-server
Linux kms server.

## Client usage:

**Note: run `cmd` with administrator.**

- Windows: https://technet.microsoft.com/ru-ru/library/jj612867(v=ws.11).aspx
```powershell
slmgr /ipk XXXXX-XXXXX-XXXXX-XXXXX-XXXXX
slmgr /skms 
slmgr /ato
```

- Office: http://technet.microsoft.com/ru-ru/library/ee624355(office.14).aspx
```powershell
cd "C:\Program Files (x86)\Microsoft Office\Office14"
cscript ospp.vbs /inpkey:XXXXX-XXXXX-XXXXX-XXXXX-XXXXX
cscript ospp.vbs /sethst:
cscript ospp.vbs /setprt:
cscript ospp.vbs /act
```

- Source Code:
You can download source code on [MDL](https://forums.mydigitallife.info/threads/50234-Emulated-KMS-Servers-on-non-Windows-platforms)

- Man:
https://colascarlet.moe/Server/160/
