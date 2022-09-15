# Basic-AndroidStudio

## Program:

```
Developed By: Challa Sandeep
Register Number: 212221240011
```

### MainActivity.java:
```
package com.example.project;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Toast toast=Toast.makeText(getApplicationContext(),"OnCreate Executed",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onStart(){
        super.onStart();
        Toast toast=Toast.makeText(getApplicationContext(),"OnStart Executed",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onResume(){
        super.onResume();
        Toast toast=Toast.makeText(getApplicationContext(),"OnResume Executed",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onPause(){
        super.onPause();
        Toast toast=Toast.makeText(getApplicationContext(),"OnPause Executed",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onStop(){
        super.onStop();
        Toast toast=Toast.makeText(getApplicationContext(),"OnStop Executed",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onRestart(){
        super.onRestart();
        Toast toast=Toast.makeText(getApplicationContext(),"OnRestart Executed",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onDestroy(){
        super.onDestroy();
        Toast toast=Toast.makeText(getApplicationContext(),"OnDestroy Executed",Toast.LENGTH_LONG);
        toast.show();
    }
}

```

### activity_main.xml:
```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World!"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>
```

### Output:

<img width="1440" alt="1" src="https://user-images.githubusercontent.com/93427522/190354780-18c3a3de-74e0-42f2-afed-45b7bc918392.png">

<img width="1440" alt="2" src="https://user-images.githubusercontent.com/93427522/190354859-2ce6ef6a-f372-4457-9bdf-263f2c805beb.png">

<img width="1440" alt="3" src="https://user-images.githubusercontent.com/93427522/190354920-a8d11921-4a9d-4c06-a568-dd185127b0f1.png">

<img width="1440" alt="4" src="https://user-images.githubusercontent.com/93427522/190354941-65e779ae-7672-44c5-ae7e-0c60629c1715.png">

<img width="1440" alt="5" src="https://user-images.githubusercontent.com/93427522/190354980-055db276-e06f-42f7-a3b5-efa56e2baa82.png">

<img width="1440" alt="6" src="https://user-images.githubusercontent.com/93427522/190355033-1a0e4f3a-848f-4957-ba6d-6c764450e60c.png">

<img width="1440" alt="7" src="https://user-images.githubusercontent.com/93427522/190355117-6d28377e-a298-4855-8ca0-f9a93c931f57.png">


### Result:
Therefore a program is return to develop a program to detect the various life cycles of an activity. The program is successfully executed.
