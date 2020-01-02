# Spinner-background

## Spinner-bg.xml

```
<?xml version="1.0" encoding="utf-8"?>
<layer-list xmlns:android="http://schemas.android.com/apk/res/android">
    <item>
        <color android:color="@color/reg_frag_box" />
    </item>
    <item android:gravity="center_vertical|right" android:right="8dp">
        <layer-list>
            <item android:width="12dp" android:height="12dp" android:gravity="center" android:bottom="10dp">
                <rotate
                    android:fromDegrees="45"
                    android:toDegrees="45">
                    <shape android:shape="rectangle">
                        <solid android:color="@color/reg_frag_text" />
                        <stroke android:color="@color/reg_frag_box_border" android:width="1dp"/>
                    </shape>
                </rotate>
            </item>
            <item android:width="30dp" android:height="10dp" android:bottom="21dp" android:gravity="center">
                <shape android:shape="rectangle">
                    <solid android:color="@color/reg_frag_box"/>
                </shape>
            </item>
        </layer-list>
    </item>

    <item>
        <shape android:shape="rectangle">
            <stroke android:width="2dp" android:color="@color/reg_frag_box_border"/>
            <padding android:bottom="12dp" android:top="12dp"/>
            <corners android:radius="5dp"/>
        </shape>
    </item>
</layer-list>

```

## Layout Editor 

[Look like this in Layout editor](https://raw.githubusercontent.com/shahzadafridi/Spinner-background/master/layout_editor.PNG)

