# CONSOLE-BASED-OTP-VERIFICATION-
This Python script allows you to send a one-time password (OTP) to a specified email address for verification using the SMTP protocol. It utilizes smtplib for sending emails and random for OTP generation
<h1>Features</h1>
<ul type = "disc">
  <li>Genetrates a random 4-digit OTP.</li>
  <li>Sends OTP via Gmail's SMTP server.</li>
  <li>Verifies the OTP entered by the user.</li>
  <li>Ensures secure email transmission with TLS encryption</li>
  </ul>

<h1>Prerequisites</h1>
<ul type ="disc">
 <li>Python 3 installed on your system</li>
 <li>A Gmail account with Less Secure Apps acess enabled or an App Password for authentiction</li>
 <li>requred Python libraries installed</li>
</ul>
<pre>  pio install smtplib email </pre>

<h1>How to Use </h1>
<ol type = "1">
<li>Clone the repository:</li>
<pre> git clone https://github.com/your-username/your-repo.git
cd your-repo</pre>
<li>Open the script and replace your-email@gmail.com and your-app-password in server.login()</li>
<li>Run the script:</li>
<pre>python otp_verification.py</pre>
</ol>
