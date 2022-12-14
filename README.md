# MP-TK-ODEV-3
MP TK ODEV 3
package com.example.myapplication;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;

public class MainActivity extends AppCompatActivity{

        EditText editText Sayilar;
        Button button_TekSayi, button_Ciftsayi,button_TumSayi;
@Override
        protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        editText_Sayilar = findViewById(R.id.editTextTextMultiline_Sayilar);
        button_Ciftsayi -findViewById(R.id.button_Ciftsayilar);
        button_Teksayi = findViewById(R.id.button_Teksayilar);
        button_Tumsayi = findViewById(R.id.button_Tumsayilar); 
        }
    public void Ciftsayilar (View view) {
        editText Sayilar.setText("");
        for (int i = 0; i <= 15; i++) {
            if (1 % 2 == 0) {
                editText Sayilar.setText(editText_Sayilar.getText() + "\n" + 1);

            }
        }

    }
    public void Teksayilar (View view) {
        editText_Sayilar.setText("");

        for (int i = 0; i <= 15; i++) {
            if (1 % 2 != 0) {
                editText_Sayilar.setText(editText_Sayilar.getText() + "\n" + 1);
            }
        }
    }
    public void Teksayilar (View view) {
         editText_Sayilar.setText("");
             for (int i=0;i<=15;i++) { if (1%2!=0) {
                editText_Sayilar.setText(editText_Sayilar.getText() + "\n" + 1);

             }

        }
    }
    public void Tumsayilar (View view) {
        editText_Sayilar.setText("");
           for (int i = 0; i <= 15; i++) {
                    editText_Sayilar.setText(editText_Sayilar.getText() + "\n" + 1);

           }
        }
    }
