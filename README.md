# Runas-Admin
Copy and paste the code below and press enter
```
runas /user:PC-NAME\Admin-User "cmd"
password: 
```

or

```
cmd /c "runas /user:admin-mtk \"C:\Path\To\Your\App.exe""
```


or 

```
powershell -Command "$p = ConvertTo-SecureString 'YourPasswordHere' -AsPlainText -Force; $c = New-Object System.Management.Automation.PSCredential ('Administrator', $p); Start-Process 'C:\Path\To\Your\App.exe' -Credential $c"
```
