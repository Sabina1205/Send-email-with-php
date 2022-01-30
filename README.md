# Send-email-with-php
Contact form for sending emails via **PHP code with open-source PHP library.**

Connect PHPMailer in PHP code.
```php
 use PHPMailer\PHPMailer\PHPMailer; 
```

Include id attributes from contact form.
```php 
$name = $_POST['name'];
$email = $_POST['email'];
$subject = $_POST['subject'];
$body = $_POST['body'];
```

Set up **SMTP and EMAIL settings.
