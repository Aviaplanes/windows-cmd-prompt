<p align="center">
  <img src="blue.png" alt="demo">
</p>

```cmd
reg add "HKCU\Software\Microsoft\Command Processor" /v AutoRun /t REG_SZ /d "prompt $E[49;34m$E[44;30m$P $E[49;34m$E[0m " /f
```

<p align="center">
  <img src="cyan.png" alt="demo">
</p>

```cmd
reg add "HKCU\Software\Microsoft\Command Processor" /v AutoRun /t REG_SZ /d "prompt $E[96m$E[7m$P$E[27m$E[0m " /f
```

<p align="center">
  <img src="green.png" alt="demo">
</p>

```cmd
reg add "HKCU\Software\Microsoft\Command Processor" /v AutoRun /t REG_SZ /d "prompt $E[32m$E[42;30m$P $E[0m$E[32m$E[0m " /f
```

<p align="center">
  <img src="lblue.png" alt="demo">
</p>

```cmd
reg add "HKCU\Software\Microsoft\Command Processor" /v AutoRun /t REG_SZ /d "prompt $E[38;2;123;165;255m$E[48;2;123;165;255m$E[30m$P $E[0m$E[38;2;123;165;255m$E[0m " /f
```

**Default**
reg delete "HKCU\Software\Microsoft\Command Processor" /v AutoRun /f
