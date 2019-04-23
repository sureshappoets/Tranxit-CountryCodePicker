-- Country Code picker library --

To try use 
###Layout add 
```
<com.tranxit.countrycode_picker.CountryCodePicker
        android:id="@+id/ccp"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:ccp_defaultNameCode="IN" 
        app:ccp_defaultCode="91"/>
```
### EditText

```
<EditText
        android:id="@+id/phone_number_edt"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:hint="phone"
        android:inputType="phone" />
        
```


### Activiy Class include 

```

        ccp = (CountryCodePicker) findViewById(R.id.ccp);
        edtPhoneNumber = (EditText) findViewById(R.id.phone_number_edt);
        ccp.registerPhoneNumberTextView(edtPhoneNumber);
        
```
All Rights Reserved by Tranxit       
        
