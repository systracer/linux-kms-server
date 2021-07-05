# linux-kms-server
Linux kms server.

## Client usage:

**Note: run `cmd` with administrator.**

- Windows: https://technet.microsoft.com/ru-ru/library/jj612867(v=ws.11).aspx
- Windows+: https://docs.microsoft.com/ru-ru/windows-server/get-started/kmsclientkeys
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
KeyManagementServiceName

- Source Code:
You can download source code on [MDL](https://forums.mydigitallife.info/threads/50234-Emulated-KMS-Servers-on-non-Windows-platforms)

- Man:
https://colascarlet.moe/Server/160/
https://archive.fo/48jvW

```
2012 - D2N9P-3P6X9-2R39C-7RTCD-MDVJX
2019 - N69G4-B89J2-4G8F4-WWYCC-J464C
