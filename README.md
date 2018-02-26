# linux-kms-server
Linux kms server.

## Client usage:

**Note: run `cmd` with administrator.**

- Windows: https://technet.microsoft.com/ru-ru/library/jj612867(v=ws.11).aspx
```powershell
slmgr /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX
slmgr /skms .ddns.info:8080
slmgr /ato
```

- Office: https://technet.microsoft.com/ru-ru/library/ee624355(office.14).aspx
http://winitpro.ru/index.php/2013/02/25/aktivaciya-ms-office-2013-vl
```powershell
cd "C:\Program Files (x86)\Microsoft Office\Office14"
cscript ospp.vbs /inpkey:V7QKV-4XVVR-XYV4D-F7DFM-8R6BM
cscript ospp.vbs /sethst:.ddns.info
cscript ospp.vbs /setprt:8080
cscript ospp.vbs /act
```

- Source Code:
You can download source code on [MDL](https://forums.mydigitallife.info/threads/50234-Emulated-KMS-Servers-on-non-Windows-platforms)

- Man:
https://colascarlet.moe/Server/160/
