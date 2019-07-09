# Unity_DateTimeConverter

``DateTimeConverter`` is just a static class. Not dependence on Unity.

## Import to Your Project

You can import this asset from UnityPackage.

- [DateTimeConverter.unitypackage](https://github.com/XJINE/Unity_DateTimeConverter/blob/master/DateTimeConverter.unitypackage)

## How to Use

Multiply these parameters. ``using DateTimeConverter`` is useful.

```csharp
public static float DayToHour = 24;
public static float DayToMin  = 24 * 60;
public static float DayToSec  = 24 * 60 * 60;
public static float DayToMsec = 24 * 60 * 60 * 100;

public static float HourToDay  = 1 / 24;
public static float HourToMin  = 60;
public static float HourToSec  = 60 * 60;
public static float HourToMsec = 60 * 60 * 100;

public static float MinToDay  = 1 / 60 / 24;
public static float MinToHour = 1 / 60;
public static float MinToSec  = 60;
public static float MinToMsec = 60 * 100;

public static float SecToDay  = 1 / 60 / 60 / 24;
public static float SecToHour = 1 / 60 / 60;
public static float SecToMin  = 1 / 60;
public static float SecToMsec = 100;

public static float MsecToDay  = 1 / 100 / 60 / 60 / 24;
public static float MsecToHour = 1 / 100 / 60 / 60;
public static float MsecToMin  = 1 / 100 / 60;
public static float MsecToSec  = 1 / 100;
```
