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

![phpemail](https://user-images.githubusercontent.com/96692767/151716362-eaffd81c-82e3-49c9-ab74-b057ae92ef21.jpg)

Set up **SMTP and EMAIL settings.**
