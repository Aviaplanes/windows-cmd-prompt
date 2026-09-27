<p align="center">
  <img src="demo.png" alt="demo">
</p>


```cmd
reg add "HKCU\Software\Microsoft\Command Processor" /v AutoRun /t REG_SZ /d "prompt $E[49;34m$E[44;30m$P $E[49;34m$E[0m " /f
```
