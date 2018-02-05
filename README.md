# pttracker
A ProfitTrailer addon that uses PT data files to automatically track your daily and monthly profits in real time.

<a href="https://ibb.co/iYGJR6"><img src="https://preview.ibb.co/d1UuzR/Screenshot_2018_02_03_12_19_08.jpg" alt="Screenshot_2018_02_03_12_19_08" border="0"></a>

<h1>Installing PtTracker</h1>
1. Save files in your ProfitTrailer Folder. (Same folder as application.properties)<br>
2. Open PtTracker.json in a text editor, add your username, license key, starting value, and then save.
(Note: Your license key has single user access. If you give it to someone else, your tracker will no longer work.)<br>
3. (skip this step if you want to run your own local webserver) <a href="https://cesanta.com/binary.html">Download Mongoose (Windows)</a> and place the .exe file in the same folder.

<h1>Running PtTracker using Mongoose (Windows) </h1>

Open Mongoose (exe file) in your ProfitTrailer folder.<br>
(Mongoose is a standalone web server. Block port 8084 in your firewall for security)

<h1>Running PtTracker (Linux)</h1>

Coming soon

<h1>Running PtTracker (Raspberry Pi)</h1>
<h2>Python 2</h2>

Change directory into the ProfitTrailer folder using the command cd /path/to/your/folder

Start up a Python web server using the command python -m SimpleHTTPServer

This will start a web server that hosts your entire directory, which will be made accessible through the following URL: http://localhost:8000/ 

This approach is built in to any Python installation.

Point your browser to: http://localhost:8000/PtTracker.html

<h2>Python 3</h2>
Do the same steps, but use the following command instead python3 -m http.server

<h2>Security</h2>
For extra security, you can block port 8084 in your firewall and add authentication using: https://github.com/tianhuil/SimpleHTTPAuthServer

<h1>Running PtTracker using your own web server (Any OS)</h1>

Configure your webserver to serve your ProfitTrailer folder as webroot directory locally.<br>
Access with: http://localhost/PtTracker.html<br>
If you decide to serve it publicly to view PtTracker remotely, make sure you add an <a href="http://www.htaccesstools.com/htpasswd-generator/">htaccess file</a> for security.


<h1>Purchasing</h1>
1. Message me on Discord or Telegram. I will reply with the payment address.<br>
2. Send 0.005 BTC or 0.3 LTC (Send enough to cover your transfer fee)<br>
3. Once payment is confirmed, I will send your license key.

<h1>Contact</h1>
Discord: btayfla#0063<br>
Telegram: https://t.me/pt_tracker



<h1>Donate</h1>
And let me know on discord or telegram if you do so I can thank you!<br>
BTC: 13EUZ5juobs1XfZW6Ad3QTkbhvchsKbbJN<br>
LTC: LbmkWmVP1npYtcZtW44Xq1SSGJsRCFZNvC<br>
ETH: 0xAcc1416387B7C3f9AF0E93A9583C95EB441dDD6
