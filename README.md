# Weather_android
Weather_app_via_kotlin
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="25dp"
    android:background="@drawable/gradient_bg"
    tools:context=".MainActivity">

    <RelativeLayout
        android:id="@+id/mainContainer"
        android:visibility="visible"
        android:layout_width="match_parent"
        android:layout_height="match_parent">
        <LinearLayout
            android:id="@+id/adressContainer"
            android:orientation="vertical"
            android:gravity="center"
            android:layout_width="match_parent"
            android:layout_height="wrap_content">
            <TextView
                android:id="@+id/adress"
                android:textSize="24sp"
                android:text="Location"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content">

            </TextView>
        </LinearLayout>
    </RelativeLayout>
</RelativeLayout>

<?xml version="1.0" encoding="utf-8"?>
<shape android:shape="rectangle"
    xmlns:android="http://schemas.android.com/apk/res/android">
    <gradient android:angle="90"
        android:startColor="#9561"
        android:endColor="#122213"
        android:type="linear">

    </gradient>

</shape>
