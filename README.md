# Fixed-Flutter-Crash
Fixed Flutter App Crash in debug mode for android 5.0+

Go to folder

```
android\app\src\main\res\drawable-v21\launch_background.xml
```

and change this

From :

```
<item android:drawable="?android:colorBackground" />
```

To :
```
<item>
    <color android:color="?android:colorBackground" />
</item>
```
