# HelloWorld
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/activity_hello_world"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:paddingBottom="@dimen/activity_vertical_margin"
    android:paddingLeft="@dimen/activity_horizontal_margin"
    android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
    tools:context="com.example.mbrady0106.myapplication.HelloWorld">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World!"
        android:id="@+id/textView" />

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="
        Matt Brady
        Mobile Development
        Video Game design"
        android:layout_below="@+id/textView"
        android:layout_alignParentRight="true"
        android:layout_alignParentEnd="true"
        android:layout_marginRight="7dp"
        android:layout_marginEnd="7dp"
        android:layout_marginTop="83dp"
        android:id="@+id/textView2" />

</RelativeLayout>

