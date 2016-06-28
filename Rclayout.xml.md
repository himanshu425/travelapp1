<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:orientation="vertical"
    android:layout_height="match_parent">
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:id="@+id/Name"
        android:text="Name"
        android:textSize="15sp"
        />
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Location"
        android:textSize="15sp"
        android:id="@+id/Location"
        android:layout_alignTop="@+id/Name"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true"
      />


    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:paddingRight="120sp"
        android:text="Price"
        android:textSize="15sp"
        android:layout_alignParentTop="true"
        android:layout_alignParentRight="true"
        android:layout_alignParentEnd="true"
        android:id="@+id/Price" />
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:textSize="15sp"
        android:text="locationDescription"
        android:id="@+id/locationDescription"
        android:layout_below="@+id/Name"
        android:layout_alignLeft="@+id/Name"
        android:layout_alignStart="@+id/Name" />
    <View
        android:layout_width="match_parent"
        android:layout_height="2dp"
        android:background="#ff8800"/>

</LinearLayout>
