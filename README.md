# mediatek-telephony-base-jar

## Instructions 
decompile

```
apktool d 'mediatek-telephony-base.jar' -api 29
```

compile

```
apktool b -d -f 'mediatek-telephony-base.jar.out' -api 29
```

copy classes.dex from build dir inside `mediatek-telephony-base.jar.out` and add classes.dex to 'mediatek-telephony-base.jar' 
