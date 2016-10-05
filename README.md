# localhost-directory-design
For Apache2 Server

How to use:<br>
1. Open localhost folder (default : /var/www or /var/www/html), delete or move index.html to another dir<br><br>
2. Copy css folder to localhost (default : /var/www or /var/www/html)<br><br>
3. a) Go to /etc/apache2/sites-enabled/ and open 000-default.conf (as root)<br><br>
   b) Go to /etc/apache2/ and open apache2.conf (as root)<br><br>
4. Find and edit, save  :<br>
  DocumentRoot /var/www/html<br>
	IndexStyleSheet "/css/style.css"<br><br>
5. Open your browser, type localhost and enter.<br><br>

*you can change the style*<br><br>

#Screenshot
![SS1.png](/screenshot/1.jpg?raw=true "Screenshot-1")<br><br>
![SS1.png](/screenshot/2.jpg?raw=true "Screenshot-1")
