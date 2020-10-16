<?xml version="1.0" encoding="utf-8"?> 
<androidx.constraintlayout.widget.ConstraintLayout
	xmlns:android="http://schemas.android.com/apk/res/android"
	xmlns:app="http://schemas.android.com/apk/res-auto"
	xmlns:tools="http://schemas.android.com/tools"
	android:layout_width="match_parent"
	android:layout_height="match_parent"
	android:background="#8BC34A"
	android:backgroundTint="@android:color/darker_gray"
	tools:context=".MainActivity"> 

	<TextView
		android:id="@+id/textView"
		android:layout_width="133dp"
		android:layout_height="28dp"
		android:layout_marginStart="139dp"
		android:layout_marginLeft="139dp"
		android:layout_marginTop="16dp"
		android:layout_marginEnd="139dp"
		android:layout_marginRight="139dp"
		android:layout_marginBottom="559dp"
		android:background="#0F9D58" 

		android:text="myFirstApp" 
		android:textAppearance="@style/TextAppearance.AppCompat.Medium" 
		app:layout_constraintBottom_toBottomOf="parent" 
		app:layout_constraintEnd_toEndOf="parent" 
		app:layout_constraintStart_toStartOf="parent" 
		app:layout_constraintTop_toTopOf="parent" /> 

	<TextView
		android:layout_width="194dp"
		android:layout_height="43dp"
		android:layout_marginStart="114dp"
		android:layout_marginLeft="114dp"
		android:layout_marginTop="58dp"
		android:layout_marginEnd="103dp"
		android:layout_marginRight="103dp"
		android:layout_marginBottom="502dp"
		android:scrollbarSize="30dp"
		android:text=" Calculator"
		android:textAppearance="@style/TextAppearance.AppCompat.Body1"
		android:textSize="30dp"
		app:layout_constraintBottom_toBottomOf="parent"
		app:layout_constraintEnd_toEndOf="parent"
		app:layout_constraintStart_toStartOf="parent"
		app:layout_constraintTop_toTopOf="parent" /> 

	<EditText
		android:id="@+id/num1"
		android:layout_width="364dp"
		android:layout_height="28dp"
		android:layout_marginStart="72dp"
		android:layout_marginTop="70dp"
		android:layout_marginEnd="71dp"
		android:layout_marginBottom="416dp"
		android:background="@android:color/white"
		android:ems="10"
		android:hint="Number1(0)"
		android:inputType="number"
		app:layout_constraintBottom_toBottomOf="parent"
		app:layout_constraintEnd_toEndOf="parent"
		app:layout_constraintStart_toStartOf="parent"
		app:layout_constraintTop_toTopOf="parent" /> 

	<EditText
		android:id="@+id/num2"
		android:layout_width="363dp"
		android:layout_height="30dp"
		android:layout_marginStart="72dp"
		android:layout_marginTop="112dp"
		android:layout_marginEnd="71dp"
		android:layout_marginBottom="374dp"
		android:background="@android:color/white"
		android:ems="10"
		android:hint="number2(0)"
		android:inputType="number"
		app:layout_constraintBottom_toBottomOf="parent"
		app:layout_constraintEnd_toEndOf="parent"
		app:layout_constraintStart_toStartOf="parent"
		app:layout_constraintTop_toTopOf="parent" /> 
	
	<TextView
		android:id="@+id/result"
		android:layout_width="356dp"
		android:layout_height="71dp"
		android:layout_marginStart="41dp"
		android:layout_marginTop="151dp"
		android:layout_marginEnd="48dp"
		android:layout_marginBottom="287dp"
		android:background="@android:color/white"
		android:text="result"
		android:textColorLink="#673AB7"
		android:textSize="25sp"
		app:layout_constraintBottom_toBottomOf="parent"
		app:layout_constraintEnd_toEndOf="parent"
		app:layout_constraintStart_toStartOf="parent"
		app:layout_constraintTop_toTopOf="parent" /> 

	
	<Button
		android:id="@+id/sum"
		android:layout_width="wrap_content"
		android:layout_height="wrap_content"
		android:layout_marginStart="16dp"
		android:layout_marginTop="292dp"
		android:layout_marginEnd="307dp"
		android:layout_marginBottom="263dp"
		android:backgroundTint="@android:color/holo_red_light"
		android:onClick="doSum"
		android:text="+"
		app:layout_constraintBottom_toBottomOf="parent"
		app:layout_constraintEnd_toEndOf="parent"
		app:layout_constraintStart_toStartOf="parent"
		app:layout_constraintTop_toTopOf="parent" /> 

	<Button
		android:id="@+id/sub"
		android:layout_width="wrap_content"
		android:layout_height="wrap_content"
		android:layout_marginStart="210dp"
		android:layout_marginTop="292dp"
		android:layout_marginEnd="113dp"
		android:layout_marginBottom="263dp"
		android:backgroundTint="@android:color/holo_red_light"
		android:onClick="doSub"
		android:text="-"
		app:layout_constraintBottom_toBottomOf="parent"
		app:layout_constraintEnd_toEndOf="parent"
		app:layout_constraintStart_toStartOf="parent"
		app:layout_constraintTop_toTopOf="parent" /> 

	<Button
		android:id="@+id/div"
		android:layout_width="wrap_content"
		android:layout_height="wrap_content"
		android:layout_marginStart="307dp"
		android:layout_marginTop="292dp"
		android:layout_marginEnd="16dp"
		android:layout_marginBottom="263dp"
		android:backgroundTint="@android:color/holo_red_light"
		android:onClick="doDiv"
		android:text="/"
		app:layout_constraintBottom_toBottomOf="parent"
		app:layout_constraintEnd_toEndOf="parent"
		app:layout_constraintHorizontal_bias="0.0"
		app:layout_constraintStart_toStartOf="parent"
		app:layout_constraintTop_toTopOf="parent" /> 
	
	<Button
		android:id="@+id/mul"
		android:layout_width="wrap_content"
		android:layout_height="wrap_content"
		android:layout_marginStart="16dp"
		android:layout_marginTop="356dp"
		android:layout_marginEnd="307dp"
		android:layout_marginBottom="199dp"
		android:backgroundTint="@android:color/holo_red_light"
		android:onClick="doMul"
		android:text="x"
		app:layout_constraintBottom_toBottomOf="parent"
		app:layout_constraintEnd_toEndOf="parent"
		app:layout_constraintStart_toStartOf="parent"
		app:layout_constraintTop_toTopOf="parent" /> 
	
	<Button
		android:id="@+id/button"
		android:layout_width="92dp"
		android:layout_height="48dp"
		android:layout_marginStart="113dp"
		android:layout_marginTop="356dp"
		android:layout_marginEnd="206dp"
		android:layout_marginBottom="199dp"
		android:backgroundTint="@android:color/holo_red_light"
		android:onClick="doMod"
		android:text="%(mod)"
		app:layout_constraintBottom_toBottomOf="parent"
		app:layout_constraintEnd_toEndOf="parent"
		app:layout_constraintStart_toStartOf="parent"
		app:layout_constraintTop_toTopOf="parent" /> 

	<Button
		android:id="@+id/pow"
		android:layout_width="wrap_content"
		android:layout_height="wrap_content"
		android:layout_marginStart="113dp"
		android:layout_marginTop="292dp"
		android:layout_marginEnd="210dp"
		android:layout_marginBottom="263dp"
		android:backgroundTint="@android:color/holo_red_light"
		android:onClick="doPow"
		android:text="n1^n2"
		app:layout_constraintBottom_toBottomOf="parent"
		app:layout_constraintEnd_toEndOf="parent"
		app:layout_constraintStart_toStartOf="parent"
		app:layout_constraintTop_toTopOf="parent" /> 

</androidx.constraintlayout.widget.ConstraintLayout> 


package com.example.gfg_my_first_app; 

import androidx.appcompat.app.AppCompatActivity; 

import android.os.Bundle; 
import android.view.View; 
import android.widget.Button; 
import android.widget.EditText; 
import android.widget.TextView; 

public class MainActivity extends AppCompatActivity { 

	EditText e1, e2; 
	TextView t1; 
	int num1, num2; 

	@Override
	protected void onCreate(Bundle savedInstanceState) 
	{ 
		super.onCreate(savedInstanceState); 

		setContentView(R.layout.activity_main); 
	} 
 
	public boolean getNumbers() 
	{ 

		
		e1 = (EditText)findViewById(R.id.num1); 

		
		e2 = (EditText)findViewById(R.id.num2); 

		t1 = (TextView)findViewById(R.id.result); 

	
		s1 = e1.getText().toString(); 

		s2 = e2.getText().toString(); 


		if ((s1.equals(null) && s2.equals(null)) 
			|| (s1.equals("") && s2.equals(""))) { 

			String result = "Please enter a value"; 
			t1.setText(result); 

			return false; 
		} 
		else { 
			num1 = Integer.parseInt(e1.getText().toString()); 

			num2 = Integer.parseInt(e2.getText().toString()); 
		} 

		return true; 
	} 


	public void doSum(View v) 
	{ 

		if (getNumbers()) { 
			int sum = num1 + num2; 
			t1.setText(Integer.toString(sum)); 
		} 
	} 

	public void doPow(View v) 
	{ 

		if (getNumbers()) { 
			double sum = Math.pow(num1, num2); 
			t1.setText(Double.toString(sum)); 
		} 
	} 

 
	public void doSub(View v) 
	{ 

	 
		if (getNumbers()) { 
			int sum = num1 - num2; 
			t1.setText(Integer.toString(sum)); 
		} 
	} 
 
	public void doMul(View v) 
	{ 

		if (getNumbers()) { 
			int sum = num1 * num2; 
			t1.setText(Integer.toString(sum)); 
		} 
	} 
 
	public void doDiv(View v) 
	{ 

		 
		if (getNumbers()) { 
 
			double sum = num1 / (num2 * 1.0); 
			t1.setText(Double.toString(sum)); 
		} 
	} 
 
	public void doMod(View v) 
	{ 

 
		if (getNumbers()) { 
			double sum = num1 % num2; 
			t1.setText(Double.toString(sum)); 
		} 
	} 
} 

