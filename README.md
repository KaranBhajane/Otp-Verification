# Otp-Verification
<h1>One-Time Password (OTP) Verification System using Python</h1>
<h4>Project Description:</h4>
<p>This project implements a simple OTP (One-Time Password) verification system using Python. The primary goal is to provide a secure and convenient way to verify user identity through a one-time password sent via email. The project utilizes the PyCharm IDE and the following libraries: random for OTP generation and smtplib for sending emails.</p>

<h4>Features:</h4>
<p><b>OTP Generation:</b> The system generates a random numeric OTP whenever verification is required.</p>

<b>Email Integration:</b> The generated OTP is sent to the user's email address for verification purposes.

<b>Secure Communication:</b> The use of OTP adds an extra layer of security, making it difficult for unauthorized users to gain access.

<h4>Software Used:</h4>
<b>PyCharm</b>: An integrated development environment used for coding, testing, and debugging the Python script.
<h4>Libraries Used:</h4>
<b>random:</b> Used to generate random numbers for OTP creation.

<b>smtplib:</b> Utilized for sending emails through the Simple Mail Transfer Protocol (SMTP).

<h4>Setup and Configuration:</h4>
<p>Clone the repository to your local machine.
<ul type ="dot">
<li>bash</li>
<li>Copy code</li>
<li>git clone https://github.com/karanbhajane/otp-verification-python.git</li>
<li>Open the project in PyCharm.</li> </ul> </p>

<h4>Install the required libraries using the following command:</h4>
<ul type="dot">
<li> bash</li>
<li>Copy code</li>
<li>pip install -r requirements.txt</li>
<li>Configure your email server settings in the script for the smtplib to work.</li>
</ul>

<h4>Run the script and follow the instructions for OTP verification.</h4>

Usage:
Run the script, and it will prompt you to enter your email address.

An OTP will be generated and sent to the provided email address.

Enter the received OTP for verification.

If the OTP is valid, the user is successfully verified; otherwise, an error message is displayed.

Contribution:
Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.

License:
This project is licensed under the MIT License - see the LICENSE file for details.
