# -PENETRATION-TESTING-TOOLKIT

COMPANY NAME : CODETECH IT SOLUTION

NAME : ADITYA KUMAR DHARA

INTERN ID : CT04DZ243

DOMAIN : CYBER SECURITY AND ETHICAL HACKING

MENTOR : NEELA SANTOSH

The provided Python program is a **Penetration Testing Toolkit** that simulates the functions of commonly used security assessment tools. It integrates multiple modules—port scanning, directory brute-forcing, login brute-forcing, and subdomain enumeration—under a single interactive menu-based system. The goal of the toolkit is to give cybersecurity learners and professionals a simplified environment to understand the core concepts of penetration testing. While this script is educational in nature, it mimics real-world practices used during ethical hacking engagements, where security experts assess the resilience of a system against potential attacks.

The first module is the **Port Scanner**, which checks whether specific network ports on a given host are open. Ports such as 21 (FTP), 22 (SSH), 80 (HTTP), 443 (HTTPS), and 3306 (MySQL) are included by default. When executed, the scanner attempts to establish a connection with each port on the target system. If a connection is successful, the port is marked as open; otherwise, it is assumed closed or filtered. This is crucial because open ports can provide entry points for attackers. For instance, if an SSH port is exposed with weak credentials, it becomes a high-risk vulnerability.

The second module is the **Directory Brute-Forcer**, which aims to discover hidden or unlinked directories on a web server. Many websites host sensitive directories like “admin,” “login,” or “config” that are not directly visible but still accessible if the path is known. The brute-forcer sends requests to these common directory names appended to the base URL. If the server responds with a 200 status code, it indicates that the directory exists, potentially exposing critical administrative functions or configuration files. Such directories are often prime targets for attackers to gain unauthorized access or manipulate a system.

The third module is the **Login Brute-Forcer**, which attempts to break into web login forms using a predefined list of passwords. By sending repeated POST requests with a fixed username and different passwords, the tool checks whether the system allows access. If a successful login is detected—such as the appearance of a “Welcome” message—the password is flagged as discovered. Although simple, this module demonstrates the danger of weak password policies and highlights the importance of enforcing measures like account lockout, CAPTCHA verification, or multi-factor authentication.

The fourth module is the **Subdomain Enumerator**, which identifies active subdomains of a given domain. Many organizations host services on subdomains like “mail.example.com,” “ftp.example.com,” or “test.example.com.” If such subdomains are overlooked, they may contain outdated or unpatched applications that attackers could exploit. The enumerator checks for the existence of these subdomains by resolving them through DNS queries. If the subdomain resolves to an IP address, it is marked as discovered.

At the heart of the program is an interactive **menu-driven system** that allows users to choose which module to run. The design is user-friendly, with options ranging from port scanning to subdomain enumeration. Users can repeatedly use the toolkit until they decide to exit, making it a flexible environment for experimentation.

In summary, this penetration testing toolkit provides a consolidated demonstration of core security assessment techniques. It educates users about the significance of open ports, hidden directories, weak login credentials, and overlooked subdomains—all of which can serve as potential vulnerabilities. While simplified, the script reflects the mindset and workflow of ethical hackers, who must think like attackers to defend systems effectively. Importantly, such tools should only be used responsibly in controlled environments or with explicit permission, as unauthorized use may lead to legal consequences.

Would you like me to expand this into a **formal report format with sections like Introduction, Methodology, and Conclusion** so it looks more academic/professional?
