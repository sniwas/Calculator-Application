# Calculator-Application

Mobile Application Development
Assignment – 2





Name : S.Niwas
Register No : 20ITR079
Class : 20IT06B
Title: Calculator Application
Course Code :  18ITT61






Github Link : https://github.com/sniwaserode/Calculator-Application
AIM:
	To develop a calculator application that calculates basic addition, subtraction, multiplication, division and modulus operation.

CODE:
Activity_main.xml
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/textView3"
        android:layout_width="match_parent"
        android:layout_height="100dp"
        android:layout_marginStart="20dp"
        android:layout_marginTop="20dp"
        android:layout_marginEnd="20dp"
        android:layout_marginBottom="20dp"
        android:text=""
        android:textAlignment="textEnd"
        android:textSize="20dp" />

    <TextView
        android:id="@+id/textView1"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginStart="20dp"
        android:layout_marginTop="40dp"
        android:layout_marginEnd="20dp"
        android:layout_marginBottom="20dp"
        android:text="0"
        android:textAlignment="textEnd"
        android:textSize="43dp"
        tools:ignore="TextViewEdits" />

    <TextView
        android:id="@+id/textView2"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="0"
        android:textSize="64dp"
        android:textAlignment="textEnd"
        android:layout_above="@id/layout1"/>

    <LinearLayout
        android:id="@+id/layout1"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:paddingVertical="25dp"
        android:background="#B7EAA3A3"
        android:orientation="vertical">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:gravity="center"
            android:orientation="horizontal">

            <Button
                android:id="@+id/button_clr"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_marginRight="20dp"
                android:text="C"
                android:textSize="32dp" />

            <Button
                android:id="@+id/button_o"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_marginLeft="20dp"
                android:layout_marginRight="20dp"
                android:text="("
                android:textSize="32dp" />

            <Button
                android:id="@+id/button_c"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_marginLeft="20dp"
                android:layout_marginRight="20dp"
                android:text=")"
                android:textSize="32dp" />

            <Button
                android:id="@+id/button_div"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_marginLeft="20dp"
                android:text="/"
                android:textSize="32dp" />

        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:gravity="center"
            android:orientation="horizontal">

            <Button
                android:id="@+id/button7"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_marginRight="20dp"
                android:text="7"
                android:textSize="32dp" />

            <Button
                android:id="@+id/button8"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_marginLeft="20dp"
                android:layout_marginRight="20dp"
                android:text="8"
                android:textSize="32dp" />

            <Button
                android:id="@+id/button9"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_marginLeft="20dp"
                android:layout_marginRight="20dp"
                android:text="9"
                android:textSize="32dp" />

            <Button
                android:id="@+id/button_mul"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_marginLeft="20dp"
                android:text="*"
                android:textSize="32dp" />

        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:gravity="center"
            android:orientation="horizontal">

            <Button
                android:id="@+id/button1"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_marginRight="20dp"
                android:text="1"
                android:textSize="32dp" />

            <Button
                android:id="@+id/button2"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_marginLeft="20dp"
                android:layout_marginRight="20dp"
                android:text="2"
                android:textSize="32dp" />

            <Button
                android:id="@+id/button3"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_marginLeft="20dp"
                android:layout_marginRight="20dp"
                android:text="3"
                android:textSize="32dp" />

            <Button
                android:id="@+id/button_add"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_marginLeft="20dp"
                android:text="+"
                android:textSize="32dp" />

        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:gravity="center"
            android:orientation="horizontal">

            <Button
                android:id="@+id/button4"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_marginRight="20dp"
                android:text="4"
                android:textSize="32dp" />

            <Button
                android:id="@+id/button5"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_marginLeft="20dp"
                android:layout_marginRight="20dp"
                android:text="5"
                android:textSize="32dp" />

            <Button
                android:id="@+id/button6"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_marginLeft="20dp"
                android:layout_marginRight="20dp"
                android:text="6"
                android:textSize="32dp" />

            <Button
                android:id="@+id/button_sub"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_marginLeft="20dp"
                android:text="-"
                android:textSize="32dp" />

        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:gravity="center"
            android:orientation="horizontal">

            <Button
                android:id="@+id/button_mod"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_marginRight="20dp"
                android:text="%"
                android:textSize="32dp" />

            <Button
                android:id="@+id/button0"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_marginLeft="20dp"
                android:layout_marginRight="20dp"
                android:text="0"
                android:textSize="32dp" />

            <Button
                android:id="@+id/button_dot"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_marginLeft="20dp"
                android:layout_marginRight="20dp"
                android:text="."
                android:textSize="32dp" />

            <Button
                android:id="@+id/button_equ"
                android:layout_width="72dp"
                android:layout_height="72dp"
                android:layout_marginLeft="20dp"
                android:text="="
                android:textSize="32dp" />

        </LinearLayout>
   </LinearLayout>

</RelativeLayout>

MainActivity.java
package com.example.calculator;

import android.app.Activity;
import android.os.Bundle;
import android.view.View;
import android.widget.Button;
import android.widget.TextView;
import android.widget.Toast;
import java.text.DecimalFormat;
import java.util.Objects;

public class MainActivity extends Activity {
    TextView textview1,textview2,textview3;
    Button bclr,bo,bc,bdiv,bmul,badd,bsub,bqu,bdot,bmod,b1,b2,b3,b4,b5,b6,b7,b8,b9,b0;
    String opers;
    String b_text,res;
    double n1,n2;
    double sum=0.0;
    int i=1;
    
   @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        textview1=findViewById(R.id.textView1);
        textview2=findViewById(R.id.textView2);
        textview3=findViewById(R.id.textView3);
        bclr=findViewById(R.id.button_clr);
        bo=findViewById(R.id.button_o);
        bc=findViewById(R.id.button_c);
        bdiv=findViewById(R.id.button_div);
        bmul=findViewById(R.id.button_mul);
        badd=findViewById(R.id.button_add);
        bsub=findViewById(R.id.button_sub);
        bqu=findViewById(R.id.button_equ);
        bdot=findViewById(R.id.button_dot);
        bmod=findViewById(R.id.button_mod);
        b1=findViewById(R.id.button1);
        b2=findViewById(R.id.button2);
        b3=findViewById(R.id.button3);
        b4=findViewById(R.id.button4);
        b5=findViewById(R.id.button5);
        b6=findViewById(R.id.button6);
        b7=findViewById(R.id.button7);
        b8=findViewById(R.id.button8);
        b9=findViewById(R.id.button9);
        b0=findViewById(R.id.button0);

        bclr.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
               b_text=bclr.getText().toString();

               textview1.setText("0");
               i=i+1;
               if(i==3){
                   textview3.setText("");
                   i=0;
               }

            }

        });
        bo.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                b_text=bo.getText().toString();
                Toast.makeText(MainActivity.this,"Open Bracket Selected",Toast.LENGTH_LONG).show();
            }

        });
        bc.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                b_text=bc.getText().toString();
                Toast.makeText(MainActivity.this,"Close Bracket Selected",Toast.LENGTH_LONG).show();
            }

        });
        bdiv.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                opers="div";
                textview3.append("/");
                n1=Double.valueOf(textview1.getText().toString()).doubleValue();
                b_text=bdiv.getText().toString();
                textview1.setText("");
            }

        });
        bmul.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                opers="mul";
                textview3.append("*");
                n1=Double.valueOf(textview1.getText().toString()).doubleValue();
                b_text=bmul.getText().toString();
                textview1.setText("");
            }
        });
        badd.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                opers="add";
                textview3.append("+");
                n1=Double.valueOf(textview1.getText().toString()).doubleValue();
                b_text=badd.getText().toString();

                textview1.setText("");

            }

        });
        bmod.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                opers="mod";
                textview3.append("%");
                n1=Double.valueOf(textview1.getText().toString()).doubleValue();
                b_text=bmod.getText().toString();
                textview1.setText("");
            }
        });
        bsub.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                opers="sub";
                textview3.append("-");
                n1=Double.valueOf(textview1.getText().toString()).doubleValue();
                b_text=bsub.getText().toString();
                textview1.setText("");
            }

        });
        bqu.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                n2=Double.valueOf(textview1.getText().toString()).doubleValue();
                textview3.append("=");
                if (opers.equals("mul"))
                {
                    sum=n1*n2;
                    sum=Double.parseDouble(new DecimalFormat("##.###").format(sum));
                    res=String.valueOf(sum);
                    textview1.setText(res);
                    textview2.setText(res);
                }
                else if(opers.equals("add")) //for calculating at this
                {
                    sum=n1+n2;
                    sum=Double.parseDouble(new DecimalFormat("##.###").format(sum));
                    res=String.valueOf(sum);
                    textview1.setText(res);
                    textview2.setText(res);
                }else if(opers.equals("mod"))
                {
                    sum=n1%n2;
                    sum=Double.parseDouble(new DecimalFormat("##.###").format(sum));
                    res=String.valueOf(sum);
                    textview1.setText(res);
                    textview2.setText(res);
                }
                else if (opers.equals("sub")) //at this step the sum value will be calculated
                {
                    sum = n1 - n2;
                    sum=Double.parseDouble(new DecimalFormat("##.###").format(sum));
                    res=String.valueOf(sum);
                    textview1.setText(res);
                    textview2.setText(res);
                }
                else if (opers.equals("div"))

                {

                    sum=n1/n2;
                    sum=Double.parseDouble(new DecimalFormat("##.###").format(sum));
                     res=String.valueOf(sum);
                    textview1.setText(res);
                    textview2.setText(res);
                }
                else
                {
                    textview1.setText("Enter a number after symbol");
                }
                textview3.append(res);
                textview3.append(",");
            }
        });
        bdot.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                b_text=bdot.getText().toString();
                textview3.append(b_text);
                textview1.append(b_text);
            }
        });
        b1.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                b_text=b1.getText().toString();
                textview3.append(b_text);
                textview1.append(b_text);
            }
        });
        b2.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                b_text=b2.getText().toString();
                textview3.append(b_text);
                textview1.append(b_text);
            }
        });
        b3.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                b_text=b3.getText().toString();
                textview3.append(b_text);
                textview1.append(b_text);
            }
        });
        b4.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                b_text=b4.getText().toString();
                textview3.append(b_text);
                textview1.append(b_text);
            }
        });
        b5.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                b_text=b5.getText().toString();
                textview3.append(b_text);
                textview1.append(b_text);
            }
        });
        b6.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                b_text=b6.getText().toString();
                textview3.append(b_text);
                textview1.append(b_text);
            }
        });
        b7.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                b_text=b7.getText().toString();
                textview3.append(b_text);
                textview1.append(b_text);
            }
        });
        b8.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                b_text=b8.getText().toString();
                textview3.append(b_text);
                textview1.append(b_text);
            }
        });
        b9.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                b_text=b9.getText().toString();
                textview3.append(b_text);
                textview1.append(b_text);
            }
        });
        b0.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                b_text=b0.getText().toString();
                textview3.append(b_text);
                textview1.append(b_text);
            }
        });
    }
}



 
Output:
1. On Launch 
![image](https://user-images.githubusercontent.com/122344020/228675712-b6186ca1-0402-41da-890b-22b50d8d4d4e.png)

2.  On clicking number buttons
 ![image](https://user-images.githubusercontent.com/122344020/228675876-5d0abbd6-2fd1-4162-92d0-7a9027e6b76f.png)
 
3. On clicking divide button
![image](https://user-images.githubusercontent.com/122344020/228675858-c3b0b867-318e-4a59-959e-ac2fb0c57377.png)

4. On clicking number buttons after division button
 ![image](https://user-images.githubusercontent.com/122344020/228676126-db129390-859f-424e-ab6e-6d1e66c8bacd.png)

5. After clicking equals button
![image](https://user-images.githubusercontent.com/122344020/228676180-d1cda030-bc85-4497-af13-f2e9d216df0f.png)

6. After calculating 3 values 
  ![image](https://user-images.githubusercontent.com/122344020/228676219-894f68ea-16b1-4184-b342-b22b4fbc620d.png)

7. On pressing ‘C’ button 
![image](https://user-images.githubusercontent.com/122344020/228676344-46106882-da45-4f21-9145-7ac493e334ef.png)
  
 
Result:
Thus, the calculator app has been build and executed successfully. 
