After running the Playbook with the AME Wizard some people get stuck at the "Reticulating Splines" screen. (Certain regions like China and India may have higher possibility having this issue)

Atlas uses Chocolatey for downloading DirectX, .NET 3.5, and uses GitHub for downloading vcredits. Any one of those not downloading successfully will result stuck at "Reticulating Spilines". (most users seems to have issue with [vcredists](https://github.com/abbodi1406/vcredist))


We are working on a fix. Right now, please try the following methods.

### Fix 1
Switch to a different network enviornment. (This includes but are not limited to using hotspot, using a different ISP, and using a VPN that proxies CMD)

### Fix 2
Check if you have **both the AME Wizard and the playbook on your desktop**. If not, please stop the AME Wizard with Task Manager, move both the Wizard and Playbook to your desktop and try again.

### Fix 3
1. Open Task Manager.
2. Kill The curl executable,
3. Kill powershell,
4. Kill Windows Command Processor,

The install progress should start again.