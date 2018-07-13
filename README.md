# Android-icon-font

Step 1. Add the JitPack repository to your build file
Add it in your root build.gradle at the end of repositories:

```
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```

Step 2. Add the dependency

```
dependencies {
        implementation 'com.github.ha-excited:android-icon-font:0.1'
}
```

Step 3. Use fonts

```
        <!--fontawesome-->
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:fontFamily="@font/fontawesome"
            android:padding="@dimen/small_margin"
            android:text="@string/fa_glass"
            android:textSize="@dimen/icon_size" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:fontFamily="@font/fontawesome"
            android:padding="@dimen/small_margin"
            android:text="@string/fa_500px"
            android:textSize="@dimen/icon_size" />

        <!--ionicons-->
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:fontFamily="@font/ionicons"
            android:padding="@dimen/small_margin"
            android:text="@string/ion_android_add"
            android:textSize="@dimen/icon_size" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:fontFamily="@font/ionicons"
            android:padding="@dimen/small_margin"
            android:text="@string/ion_android_add_circle"
            android:textSize="@dimen/icon_size" />

        <!--map_icons-->
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:fontFamily="@font/map_icons"
            android:padding="@dimen/small_margin"
            android:text="@string/map_icon_abseiling"
            android:textSize="@dimen/icon_size" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:fontFamily="@font/map_icons"
            android:padding="@dimen/small_margin"
            android:text="@string/map_icon_accounting"
            android:textSize="@dimen/icon_size" />

        <!--material_icons_regular-->
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:fontFamily="@font/material_icons_regular"
            android:padding="@dimen/small_margin"
            android:text="@string/mr_3d_rotation"
            android:textSize="@dimen/icon_size" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:fontFamily="@font/material_icons_regular"
            android:padding="@dimen/small_margin"
            android:text="@string/mr_ac_unit"
            android:textSize="@dimen/icon_size" />

        <!--octicons-->
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:fontFamily="@font/octicons"
            android:padding="@dimen/small_margin"
            android:text="@string/oc_alert"
            android:textSize="@dimen/icon_size" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:fontFamily="@font/octicons"
            android:padding="@dimen/small_margin"
            android:text="@string/oc_alignment_align"
            android:textSize="@dimen/icon_size" />

        <!--open_iconic-->
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:fontFamily="@font/open_iconic"
            android:padding="@dimen/small_margin"
            android:text="@string/oi_account_login"
            android:textSize="@dimen/icon_size" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:fontFamily="@font/open_iconic"
            android:padding="@dimen/small_margin"
            android:text="@string/oi_account_logout"
            android:textSize="@dimen/icon_size" />

        <!--segoe_mdl2_assets-->
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:fontFamily="@font/segoe_mdl2_assets"
            android:padding="@dimen/small_margin"
            android:text="@string/se_Accept"
            android:textSize="@dimen/icon_size" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:fontFamily="@font/segoe_mdl2_assets"
            android:padding="@dimen/small_margin"
            android:text="@string/se_Accident"
            android:textSize="@dimen/icon_size" />

        <!--themify-->
        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:fontFamily="@font/themify"
            android:padding="@dimen/small_margin"
            android:text="@string/th_agenda"
            android:textSize="@dimen/icon_size" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:fontFamily="@font/themify"
            android:padding="@dimen/small_margin"
            android:text="@string/th_alarm_clock"
            android:textSize="@dimen/icon_size" />
```

## Prefixes

| Font         | Prefix | Cheat Sheet                               |
|--------------|--------|-------------------------------------------|
| Font Awesome | fa:    | [List](http://fontawesome.io/icons/) |
| Ion Icons    | io:    | [List](http://ionicons.com)               |
| Octicons     | oc:    | [List](https://octicons.github.com)       |
| Open Iconic  | ic:    | [List](https://useiconic.com/open/)       |
| Material Icon   | ma:    | [List](https://design.google.com/icons/)       |
| Themify   | ti:    | [List](https://themify.me/themify-icons)       |
| Map Icons   | mi:    | [List](http://map-icons.com)       |
| Segoe MDL2   | sm:    | [List](https://docs.microsoft.com/en-us/windows/uwp/design/style/segoe-ui-symbol-font)       |