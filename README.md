# **[AgeInMinutes](https://www.youtube.com/watch?v=uRyvNKRkwbs&t=24046s)** 

Kotlin Android Tutorial

<img width="372" alt="Android" src="https://github.com/YamamotoDesu/AgeinMinutes/blob/master/app/src/main/java/com/codewithkyo/ageinminutes/ageinminutes.gif">

<img width="343" alt="Android_Emulator_-_Nexus_6_API_30_5554" src="https://user-images.githubusercontent.com/47273077/144738509-4fc82d0a-7bca-418f-8497-df4271d7858f.png">

```xml
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:gravity="center_horizontal"
    android:orientation="vertical"
    android:padding="16dp"
    android:background="@color/backgroundColor"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="15dp"
        android:text="CALCULATE YOUR"
        android:textColor="@color/textColor"
        android:textSize="25sp"
        android:textStyle="bold" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="15dp"
        android:padding="10dp"
        android:background="@color/ageTextBackgroundColor"
        android:text="AGE"
        android:textColor="@color/white"
        android:textSize="25sp"
        android:textStyle="bold" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="15dp"
        android:text="IN MINUTES"
        android:textColor="@color/textColor"
        android:textSize="25sp"
        android:textStyle="bold" />
    
    <Button
        android:id="@+id/date_btn"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="select Date"
        android:layout_marginTop="15dp"
        android:backgroundTint="@color/white"
        android:textColor="@color/darkGray"
        android:textStyle="bold"
        android:textSize="20sp"/>

    <TextView
        android:id="@+id/selected_date"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="20dp"
        android:textColor="@color/textColor"
        android:textSize="20sp"
        android:textStyle="bold" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="10dp"
        android:text="Selected Date"
        android:textColor="@color/lightGray"
        android:textSize="18sp"
        android:textStyle="bold" />

    <TextView
        android:id="@+id/date_count"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="20dp"
        android:textColor="@color/textColor"
        android:textSize="25sp"
        android:textStyle="bold" />

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginTop="10dp"
        android:text="Age in Minutes"
        android:textColor="@color/lightGray"
        android:textSize="15sp"
        android:textStyle="bold" />
</LinearLayout>
```
