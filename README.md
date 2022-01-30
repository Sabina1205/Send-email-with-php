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

![phpsendemail](https://user-images.githubusercontent.com/96692767/151716292-4a66fc73-0770-4d62-b9fa-35ed547f7020.jpg)


Set up **SMTP and EMAIL settings.**
