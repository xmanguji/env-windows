# env-windows

## stop port 8000
```
netstat -o -n -a | findstr "8080"
taskkill /F /PID 3116
```


## deeplink test in android
```
    adb shell am start -W -a android.intent.action.VIEW -d metasalt://nftmarketplace/eth/0xa8abA6bB110745e079Ad90cbbAF62102c8bA80Fe/0x9136dd81610fc41d2e8326c0035579ee65aa4c7bb00001588880000000000414

```

## adb commands
```
adb devices
```

```
adb reverse tcp:8081 tcp:8081
```

## credentials
```
rundll32.exe keymgr.dll,KRShowKeyMgr
```

```
Gpedit.msc
Computer Configuration - Windows Settings - Security Settings - Local Policies - Security Options - Network Access: Do not allow storage of passwords
Enabled
```

```
From the run/command prompt - Services.msc - locate and go to the properties of Web Account Manager and set it to disabled then stop it.


```
