activity_main.xml


<?xml version="1.0" encoding="utf-8"?>
<layout xmlns:android="http://schemas.android.com/apk/res/android">
    <androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
        xmlns:app="http://schemas.android.com/apk/res-auto"
        xmlns:tools="http://schemas.android.com/tools"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        tools:context=".MainActivity">

        <RelativeLayout
            tools:context="com.example.calculator.MainActivity"
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:background="#1B1919">


            <TextView
                android:id="@+id/textView"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_marginStart="10dp"
                android:layout_marginTop="50dp"
                android:text="CALCULATOR"
                android:textColor="@color/white"
                android:textSize="30dp"
                android:layout_marginLeft="10dp" />

            <TextView
                android:id="@+id/res"
                android:layout_width="300dp"
                android:layout_height="50dp"
                android:layout_below="@id/textView"
                android:layout_marginTop="120dp"

                android:textColor="@color/white"
                android:textSize="30dp" />

            <EditText
                android:id="@+id/editText"
                android:layout_width="300dp"
                android:layout_height="50dp"
                android:layout_below="@id/res"
                android:layout_marginTop="10dp"

                android:textColor="@color/white"
                android:textSize="30dp" />

            <Button
                android:id="@+id/buttonseven"
                android:layout_width="100dp"
                android:layout_height="70dp"
                android:layout_below="@id/editText"
                android:layout_marginTop="10dp"
                android:text="7"
                android:textSize="25dp"
                android:theme="@style/Theme.AppCompat.Light.DarkActionBar" />

            <Button
                android:id="@+id/buttoneight"
                android:layout_width="100dp"
                android:layout_height="70dp"
                android:layout_below="@id/editText"
                android:layout_marginTop="10dp"
                android:layout_toRightOf="@id/buttonseven"
                android:text="8"
                android:textSize="25dp"
                android:theme="@style/Theme.AppCompat.Light.DarkActionBar" />

            <Button
                android:id="@+id/buttonnine"
                android:layout_width="100dp"
                android:layout_height="70dp"
                android:layout_below="@id/editText"
                android:layout_marginTop="10dp"
                android:layout_toRightOf="@id/buttoneight"
                android:text="9"
                android:textSize="25dp"
                android:theme="@style/Theme.AppCompat.DayNight.DarkActionBar" />

            <Button
                android:id="@+id/add"
                android:layout_width="100dp"
                android:layout_height="70dp"
                android:layout_below="@id/editText"
                android:layout_marginTop="10dp"
                android:layout_toRightOf="@id/buttonnine"
                android:text="+"
                android:textSize="25dp" />

            <Button
                android:id="@+id/buttonfour"
                android:layout_width="100dp"
                android:layout_height="70dp"
                android:layout_below="@id/buttonseven"
                android:text="4"
                android:textSize="25dp"
                android:theme="@style/Theme.AppCompat.Light.DarkActionBar" />

            <Button
                android:id="@+id/buttonfive"
                android:layout_width="100dp"
                android:layout_height="70dp"
                android:layout_below="@id/buttoneight"
                android:layout_toRightOf="@id/buttonfour"
                android:text="5"
                android:textSize="25dp"
                android:theme="@style/Theme.AppCompat.Light.DarkActionBar" />

            <Button
                android:id="@+id/buttonsix"
                android:layout_width="100dp"
                android:layout_height="70dp"
                android:layout_below="@id/buttonnine"
                android:layout_toRightOf="@id/buttonfive"
                android:text="6"
                android:textSize="25dp"
                android:theme="@style/Theme.AppCompat.Light.DarkActionBar" />

            <Button
                android:id="@+id/sub"
                android:layout_width="100dp"
                android:layout_height="70dp"
                android:layout_below="@id/add"
                android:layout_toRightOf="@id/buttonsix"
                android:text="-"
                android:textSize="25dp" />

            <Button
                android:id="@+id/buttonone"
                android:layout_width="100dp"
                android:layout_height="70dp"
                android:layout_below="@id/buttonfour"
                android:text="1"
                android:textSize="25dp"
                android:theme="@style/Theme.AppCompat.Light.DarkActionBar" />

            <Button
                android:id="@+id/buttontwo"
                android:layout_width="100dp"
                android:layout_height="70dp"
                android:layout_below="@id/buttonfive"
                android:layout_toRightOf="@id/buttonone"
                android:text="2"
                android:textSize="25dp"
                android:theme="@style/Theme.AppCompat.Light.DarkActionBar" />

            <Button
                android:id="@+id/buttonthree"
                android:layout_width="100dp"
                android:layout_height="70dp"
                android:layout_below="@id/buttonsix"
                android:layout_toRightOf="@id/buttontwo"
                android:text="3"
                android:textSize="25dp"
                android:theme="@style/Theme.AppCompat.Light.DarkActionBar" />

            <Button
                android:id="@+id/buttonmulti"
                android:layout_width="100dp"
                android:layout_height="70dp"
                android:layout_below="@id/sub"
                android:layout_toRightOf="@id/buttonthree"
                android:text="*"
                android:textSize="25dp" />

            <Button
                android:id="@+id/buttondot"
                android:layout_width="100dp"
                android:layout_height="70dp"
                android:layout_below="@id/buttonone"
                android:text="."
                android:textSize="25dp"
                android:theme="@style/Theme.AppCompat.Light.DarkActionBar" />

            <Button
                android:id="@+id/buttonzero"
                android:layout_width="100dp"
                android:layout_height="70dp"
                android:layout_below="@id/buttontwo"
                android:layout_toRightOf="@id/buttondot"
                android:text="0"
                android:textSize="25dp"
                android:theme="@style/Theme.AppCompat.Light.DarkActionBar" />


            <Button
                android:id="@+id/equals"
                android:layout_width="100dp"
                android:layout_height="70dp"
                android:layout_below="@id/buttonmulti"
                android:layout_toRightOf="@id/buttonzero"
                android:text="="
                android:textColor="#4AE116"
                android:textSize="40dp"
                android:theme="@style/Theme.AppCompat.Light.DarkActionBar" />

            <Button
                android:id="@+id/buttondivi"
                android:layout_width="100dp"
                android:layout_height="70dp"
                android:layout_below="@id/buttonmulti"
                android:layout_toRightOf="@id/equals"
                android:text="/"
                android:textSize="25dp" />

            <Button
                android:id="@+id/buttonclear"
                android:layout_width="100dp"
                android:layout_height="70dp"
                android:layout_below="@id/res"
                android:layout_toRightOf="@id/editText"
                android:text="C"
                android:textSize="25dp" />

        </RelativeLayout>

    </androidx.constraintlayout.widget.ConstraintLayout>
</layout>



MainActivity.java


package com.example.simple_calc;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;

import androidx.databinding.DataBindingUtil;

import android.view.View;

import java.text.DecimalFormat;

public class MainActivity extends AppCompatActivity {

    private com.example.simple_calc.databinding.ActivityMainBinding binding;

    private static final char ADDITION = '+';
    private static final char SUBTRACTION = '-';
    private static final char MULTIPLICATION = '*';
    private static final char DIVISION = '/';

    private char CURRENT_ACTION;

    private double valueOne = Double.NaN;
    private double valueTwo;

    private DecimalFormat decimalFormat;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);


        decimalFormat = new DecimalFormat("#.##########");

        binding = DataBindingUtil.setContentView(this, R.layout.activity_main);

        binding.buttondot.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                binding.editText.setText(binding.editText.getText() + ".");
            }
        });

        binding.buttonzero.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                binding.editText.setText(binding.editText.getText() + "0");
            }
        });

        binding.buttonone.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                binding.editText.setText(binding.editText.getText() + "1");
            }
        });

        binding.buttontwo.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                binding.editText.setText(binding.editText.getText() + "2");
            }
        });

        binding.buttonthree.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                binding.editText.setText(binding.editText.getText() + "3");
            }
        });

        binding.buttonfour.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                binding.editText.setText(binding.editText.getText() + "4");
            }
        });

        binding.buttonfive.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                binding.editText.setText(binding.editText.getText() + "5");
            }
        });

        binding.buttonsix.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                binding.editText.setText(binding.editText.getText() + "6");
            }
        });

        binding.buttonseven.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                binding.editText.setText(binding.editText.getText() + "7");
            }
        });

        binding.buttoneight.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                binding.editText.setText(binding.editText.getText() + "8");
            }
        });

        binding.buttonnine.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                binding.editText.setText(binding.editText.getText() + "9");
            }
        });

        binding.add.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                computeCalculation();
                CURRENT_ACTION = ADDITION;
                binding.res.setText(decimalFormat.format(valueOne) + "+");
                binding.editText.setText(null);
            }
        });

        binding.sub.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                computeCalculation();
                CURRENT_ACTION = SUBTRACTION;
                binding.res.setText(decimalFormat.format(valueOne) + "-");
                binding.editText.setText(null);
            }
        });

        binding.buttonmulti.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                computeCalculation();
                CURRENT_ACTION = MULTIPLICATION;
                binding.res.setText(decimalFormat.format(valueOne) + "*");
                binding.editText.setText(null);
            }
        });

        binding.buttondivi.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                computeCalculation();
                CURRENT_ACTION = DIVISION;
                binding.res.setText(decimalFormat.format(valueOne) + "/");
                binding.editText.setText(null);
            }
        });

        binding.equals.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                computeCalculation();
                binding.res.setText(binding.res.getText().toString() +
                        decimalFormat.format(valueTwo) + " = " + decimalFormat.format(valueOne));
                valueOne = Double.NaN;
                CURRENT_ACTION = '0';
            }
        });

        binding.buttonclear.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View view) {
                if(binding.editText.getText().length() > 0) {
                    CharSequence currentText = binding.editText.getText();
                    binding.editText.setText(currentText.subSequence(0, currentText.length()-1));
                }
                else {
                    valueOne = Double.NaN;
                    valueTwo = Double.NaN;
                    binding.editText.setText("");
                    binding.res.setText("");
                }
            }
        });
    }

    private void computeCalculation() {
        if(!Double.isNaN(valueOne)) {
            valueTwo = Double.parseDouble(binding.editText.getText().toString());
            binding.editText.setText(null);

            if(CURRENT_ACTION == ADDITION)
                valueOne = this.valueOne + valueTwo;
            else if(CURRENT_ACTION == SUBTRACTION)
                valueOne = this.valueOne - valueTwo;
            else if(CURRENT_ACTION == MULTIPLICATION)
                valueOne = this.valueOne * valueTwo;
            else if(CURRENT_ACTION == DIVISION)
                valueOne = this.valueOne / valueTwo;
        }
        else {
            try {
                valueOne = Double.parseDouble(binding.editText.getText().toString());
            }
            catch (Exception e){}
        }

    }

}


build gradle  ->> Plugins 



plugins {
    id 'com.android.application'
}


android {
    compileSdk 31


    defaultConfig {
        applicationId "com.example.calculator"
        minSdk 16
        targetSdk 31
        versionCode 1
        versionName "1.0"

        testInstrumentationRunner "androidx.test.runner.AndroidJUnitRunner"
    }

    buildTypes {
        release {
            minifyEnabled false
            proguardFiles getDefaultProguardFile('proguard-android-optimize.txt'), 'proguard-rules.pro'
        }
    }
    dataBinding{
        enabled=true
    }

    compileOptions {
        sourceCompatibility JavaVersion.VERSION_1_8
        targetCompatibility JavaVersion.VERSION_1_8
    }
}
dependencies {

    implementation 'androidx.appcompat:appcompat:1.4.1'
    implementation 'com.google.android.material:material:1.5.0'
    implementation 'androidx.constraintlayout:constraintlayout:2.1.3'
    testImplementation 'junit:junit:4.13.2'
    androidTestImplementation 'androidx.test.ext:junit:1.1.3'
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.4.0'
}
