# printspoofer

PrintSpoofer exploit that can be used to escalate service user permissions on Windows Server 2016, Server 2019, and Windows 10.  

To escalate privileges, the service account must have SeImpersonate privileges.  To execute:

```bash
PrintSpoofer.exe -i -c cmd
```
With appropriate privileges this should grant system user shell access.
