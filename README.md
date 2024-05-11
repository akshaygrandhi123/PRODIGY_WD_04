# Akshay's Portfolio

This is a personal portfolio website built using HTML, CSS, JavaScript, and PHP. The website showcases my skills, projects, and provides a way for visitors to contact me or subscribe to my newsletter.

## Features

- Responsive design for optimal viewing on various devices
- Navigation bar for easy navigation through different sections
- About section with a brief introduction and download link for my CV
- Skills section displaying my technical expertise with progress bars
- Qualification section highlighting my educational background
- Social Accounts section showcasing my professional profiles
- Services section listing the services I offer
- Contact form for visitors to reach out to me
- Feedback form for visitors to share their valuable feedback
- Newsletter subscription form for visitors to stay updated
- PHP mailer integration for sending emails

## Technologies Used

- HTML5
- CSS3
- JavaScript
- PHP
- PHPMailer (for sending emails)

## Installation

To run this project locally, follow these steps:

1. Clone the repository or download the ZIP file:

```bash
git clone https://github.com/akshaygrandhi123/PRODIGY_WD_04.git
```

2. Make sure you have a local server environment set up (e.g., XAMPP, WAMP, or MAMP) to run PHP files.

3. Configure the PHPMailer settings in the `index.php` file with your email credentials:

```php
$mail->Username = "your-email@example.com";
$mail->Password = "your-email-password";
$mail->SetFrom("your-email@example.com", "Your Name");
```

4. Place the project files in the appropriate directory (e.g., `htdocs` for XAMPP, `www` for MAMP) of your local server environment.

5. Start your local server and navigate to `http://localhost/portfolio-website` (or the appropriate URL based on your server configuration) in your web browser.

## Usage

1. The website will load, and you can navigate through different sections using the navigation bar or by scrolling.
2. In the Contact section, fill out the form and submit it to send me an email.
3. In the Feedback section, provide your valuable feedback by filling out the form and submitting it.
4. In the Newsletter section, enter your email address and submit it to subscribe to my newsletter.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Additional Files

- `PHPMailer`: This directory contains the PHPMailer library files for sending emails.
- `LICENSE`: The license file for the PHPMailer library.
- `README.md`: The README file for the PHPMailer library.
- `security.txt`: The security information file for the PHPMailer library.

Please note that you need to configure the PHPMailer settings with your email credentials to ensure proper email functionality.
