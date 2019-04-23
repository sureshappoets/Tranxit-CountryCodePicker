-- Country Code picker library --

To try use 
###Layout add 
```
<com.tranxit.countrycode_picker.CountryCodePicker
        android:id="@+id/ccp"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        tools:ignore="MissingConstraints" />
```
### EditText

```
<EditText
        android:id="@+id/phone_number_edt"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:hint="phone"
        android:inputType="phone"
        tools:ignore="MissingConstraints" />```
        
```


### Activiy Class include 

```

        ccp = (CountryCodePicker) findViewById(R.id.ccp);
        edtPhoneNumber = (EditText) findViewById(R.id.phone_number_edt);
        ccp.registerPhoneNumberTextView(edtPhoneNumber);
        
```
All Rights Reserved by Tranxit       
        
