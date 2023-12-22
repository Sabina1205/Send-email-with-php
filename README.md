# Send-email-with-php
Contact form for sending emails via **PHP code with open-source PHP library.**

Connect PHPMailer with PHP code.
```php
 use PHPMailer\PHPMailer\PHPMailer; 
```


```php 
 require_once "PHPMailer/PHPMailer.php";
 require_once "PHPMailer/SMTP.php";
 require_once "PHPMailer/Exception.php";

 $mail = new PHPMailer();
 ```


Include id attributes from contact form.
```php 
$name = $_POST['name'];
$email = $_POST['email'];
$subject = $_POST['subject'];
$body = $_POST['body'];
```
![form-php](https://github.com/Sabina1205/Send-email-with-php/assets/96692767/6ed9d8c2-d749-4b6a-8dad-f51d22f0c372)

Set up **SMTP and EMAIL settings.**
