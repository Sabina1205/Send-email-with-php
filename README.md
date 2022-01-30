# Send-email-with-php
Contact form for sending emails via **PHP code with open-source PHP library.**
______________________________________________________________________________

use PHPMailer\PHPMailer\PHPMailer;

if (isset($_POST['name']) && isset($_POST['email'])) {
        $name = $_POST['name'];
        $email = $_POST['email'];
        $subject = $_POST['subject'];
        $body = $_POST['body']; 

