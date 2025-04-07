# Webpage Redirects

This repository contains various techniques for implementing webpage redirects using HTML, JavaScript, and server-side approaches.

## Files

- `index.html`: HTML-based redirect using the `<meta>` tag.
- `redirect.html`: JavaScript-based redirect.
- `app.js`: Node.js (Express.js) server-side redirect.
- `redirect.php`: PHP server-side redirect.
- `.htaccess`: Apache server configuration for redirects.

## Instructions

### HTML-based Redirect

Open `index.html` in a web browser. The page will redirect to `https://www.newpage.com` after 5 seconds.

### JavaScript-based Redirect

Open `redirect.html` in a web browser. The page will redirect to `https://www.newpage.com` immediately or after 5 seconds if the `setTimeout` function is uncommented.

### Node.js (Express.js) Redirect

1. Make sure you have Node.js and npm installed.
2. Run `npm install express` to install the Express framework.
3. Run the server with `node app.js`.
4. Open `http://localhost:3000` in a web browser. The page will redirect to `https://www.newpage.com`.

### PHP Redirect

Upload `redirect.php` to a PHP-enabled server. Access the PHP file in a web browser. The page will redirect to `https://www.newpage.com`.

### Apache Redirect

Add the `.htaccess` file to the root directory of your Apache server. Access `http://yourdomain.com/oldpage.html` in a web browser. The page will redirect to `https://www.newpage.com`.
