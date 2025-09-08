# class-14-html
A simple project demonstrating the integration of HTML, CSS, and JavaScript in a webpage. Includes a text paragraph, styled content, alert messages, button interaction, and an example of a deceptive hyperlink (for cybersecurity awareness).
# CSDF Class 14 - HTML, CSS, and JavaScript Example

This project is part of **Class 14 (Cyber Security & Digital Forensics)**.  
It demonstrates how **HTML, CSS, and JavaScript** can be combined to create an interactive webpage.

---

## Features

- **HTML Structure** → Headings, paragraphs, and button.
- **CSS File** (`session 14.css`) → External stylesheet for design.
- **JavaScript**:
  - Welcome alert on page load.
  - Custom function (`showMessage`) that displays "Bismillah!" when the button is clicked.
- **Cybersecurity Example** → A fake link that looks like `https://facebook.com` but actually points to `https://hacker.com`.

---

## Example Code

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSDF</title>
    <link rel="stylesheet" href="session 14.css">
    <script>
        alert("Welcome to my website")
    </script>
    <script>
        function showMessage() {
            alert("Bismillah!");
        }
    </script>
</head>
<body>
    <h1>Class 14:</h1>
    <p>Lorem ipsum dolor sit amet...</p>
    <br>
    <button onclick="showMessage()">click me</button>
    <br><br>
    <a href="https://hacker.com" target="_blank">https://facebook.com</a>
</body>
</html>
