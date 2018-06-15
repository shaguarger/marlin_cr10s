# Configurations for Marlin+BLTouch on CR-10s

Follow these instructions if you want to add the BLTouch to your CR-10s:
http://3dmakerita.it/2018/03/21/bltouch-on-cr10s-english-version-i-hope/

I found one little mistake: You should not disable this line if you want to read the settings from EEPROM with Pronterface:

```
Row 1118 , #define DISABLE_M503
```

