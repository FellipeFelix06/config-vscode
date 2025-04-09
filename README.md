```
if (!(Test-Path -Path $PROFILE)) {
    New-Item -Type File -Path $PROFILE -Force
}
Add-Content $PROFILE "`nSet-Alias clear cls"
```
> cls -> clear win10

clear; oh-my-posh init pwsh --config "$env:POSH_THEMES_PATH\star.omp.json" | Invoke-Expression

