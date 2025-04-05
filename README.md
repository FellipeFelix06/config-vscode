```
if (!(Test-Path -Path $PROFILE)) {
    New-Item -Type File -Path $PROFILE -Force
}
Add-Content $PROFILE "`nSet-Alias clear cls"
```
> cls -> clear win10
