### Theory

OS Command Injection is a type of security vulnerability that occurs when an application executes operating system commands based on user input without proper validation or sanitization. This can allow attackers to execute arbitrary commands on the server, potentially leading to unauthorized access, data breaches, and system compromise.
<img src="./images/os.png">
<h4>Code injection </h4>
<p>Code injection is a generic term for any type of attack that involves an injection of code interpreted/executed by an application. This type of attack takes advantage of mishandling of untrusted data inputs. It is made possible by a lack of proper input/output data validation.

A key limitation of code injection attacks is that they are confined to the application or system they target. If an attacker can inject PHP code into an application and execute it, malicious code will be limited by PHP functionality and permissions granted to PHP on the host machine.</p>
<h4>Command injection </h4>
<p>Command injection typically involves executing commands in a system shell or other parts of the environment. The attacker extends the default functionality of a vulnerable application, causing it to pass commands to the system shell, without needing to inject malicious code. In many cases, command injection gives the attacker greater control over the target system.</p>