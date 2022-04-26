# Ex.No:1 To create a HelloWorld Activity using all lifecycles methods to display messages.


## AIM:

To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

## EQUIPMENTS REQUIRED:

Android Studio(Min. required Artic Fox)

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as “ex.no.1″ and click Next. 

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:
```
/*
Program to print the text “Hello World”.
Developed by: J . RITHANIEPRIYANKA
Registeration Number : 212220230039
MainActivity.java

package com.example.test;

import android.os.Bundle;
import android.support.v7.app.AppCompatActivity;
import android.widget.Toast;
public class MainActivity extends AppCompatActivity {
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState); setContentView(R.layout.activity_main);
        Toast toast=Toast.makeText(getApplicationContext(),"OnCreate Invoked",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onStart(){ super.onStart();
        Toast toast=Toast.makeText(getApplicationContext(),"OnStart Invoked",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onResume(){ super.onResume();
        Toast toast=Toast.makeText(getApplicationContext(),"OnResume Invoked",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onPause(){ super.onPause();
        Toast toast=Toast.makeText(getApplicationContext(),"OnPause Invoked",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onStop(){ super.onStop();
        Toast toast=Toast.makeText(getApplicationContext(),"OnStop Invoked",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onRestart(){ super.onRestart();

        Toast toast=Toast.makeText(getApplicationContext(),"OnRestart Invoked",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onDestroy(){ super.onDestroy();
        Toast toast=Toast.makeText(getApplicationContext(),"OnDestroy Invoked",Toast.LENGTH_LONG);
        toast.show();
    }
}


activity_main.xml
<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />
</android.support.constraint.ConstraintLayout>
*/
```

## OUTPUT
![J1](https://user-images.githubusercontent.com/75235132/163753204-ae6cd681-698f-4193-bc8d-8a56ef1d558d.jpeg)
![J2](https://user-images.githubusercontent.com/75235132/163753227-7ed87af8-621f-4b1c-8ae2-0ff727982c11.jpeg)
![J3](https://user-images.githubusercontent.com/75235132/163753247-d3c28392-2ef3-4cda-9446-4d2630c47a42.jpeg)
![J4](https://user-images.githubusercontent.com/75235132/163753264-5bf3a4d5-03a8-47bd-8708-06a2f8e85d03.jpeg)
![J5](https://user-images.githubusercontent.com/75235132/163753280-3cb458cc-5cb4-465a-887b-5757d7a67488.jpeg)
![J6](https://user-images.githubusercontent.com/75235132/163753302-55991a96-aeda-4237-a534-089e8fc23d3e.jpeg)




## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
