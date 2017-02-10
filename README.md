jQuery pwdMeter 1.0.1
=============

pwdMeter is a small password strength meter plugin for jQuery that provides a neat and easy way to show the user's password strength. At the same time it helps a user to generate and choose a secured password for their account. The footprint is less than 3 KB in size. 

<hr>

#Installation#

##Step 1:##
Include a reference to the jQuery Core library (1.3 or above) and the pwdMeter plugin. ###

```html
<script language="javascript" src="jquery.js"></script>
<script language="javascript" src="jquery.pwdMeter.js"></script>
```

## Step 2: ##
In your HTML file, provide the markup required by pwdMeter. 

```html
<table width="300" border="0" cellpadding="2" cellspacing="0">
  <tbody><tr>
    <td><input id="password" type="text"></td>
  </tr>
  <tr>
    <td><div id="pwdMeter" class="neutral">Very Weak</div></td>
  </tr>
</tbody></table>
```

## Step 3: ##
Finally you need to fire a call to the pwdMeter plugin and supply your parameters (if any): 

```html
<script language="javascript">
    $(document).ready(function(){
 
        $('#password').pwdMeter();
 
    });
</script>
```


__pwdMeter accepts the following optional parameters:__

+ minLength: The minimum length of the password.

+ displayGeneratePassword: If set to true, displays a link to generate random passwords.

+ generatePassText: You can specify any text that you'd like the "Generate Password" link read.

+ generatePassClass: This specifies the class for the "Generate Password" link.

+ randomPassLength: Specifying the length of the random password. Can be any integer for example 8, 10, 15 etc.


[Click here for Demo](http://shouvik.net/pwdmeter.php)


