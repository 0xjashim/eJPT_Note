eJPT Exam Questions & Challenges 
✅ <span style="color:limegreen">Answered Questions</span>

    What is the IP address of the host running SAMBA?
    <span style="color:deepskyblue">192.168.100.52</span>

    What is the IP address of the host running WordPress?
    <span style="color:deepskyblue">192.168.100.50</span>

    What version of MySQL is running on the system hosting a Drupal site?
    <span style="color:deepskyblue">MySQL 5.5.5</span>

    How many hosts on the DMZ network are running a web server on port 80?
    <span style="color:deepskyblue">4</span>

    What Linux distribution is running on the host running the Drupal site?
    <span style="color:deepskyblue">Ubuntu</span>

    What services does Syntex provide to companies?
    <span style="color:deepskyblue">Workflow Development</span>

    What is the email of the admin user on the Drupal site?
    <span style="color:deepskyblue">admin@syntex.com</span>

    What is the name of the active theme on the WordPress site?
    <span style="color:deepskyblue">spintech</span>

    How many systems on the target network have FTP servers with anonymous access enabled?
    <span style="color:deepskyblue">2</span>

    How many user accounts can be enumerated from the SAMBA server running on the system hosting Drupal?
    <span style="color:deepskyblue">3</span>

    What type of vulnerability can be exploited on the Drupal site?
    <span style="color:orangered">RCE (Drupalgeddon 2)</span>

    Which one of the following meterpreter commands can be used to add a network route?
    <span style="color:deepskyblue">autoroute</span>

    What is the subnet of the internal network?
    <span style="color:deepskyblue">192.168.0.50</span>

    What is the password of the user account "dbadmin" on the Linux server hosting Drupal?
    <span style="color:orangered">sayang</span>

    What is the CVSS V3.x rating for the Drupalgeddon2 vulnerability?
    <span style="color:orangered">9.8</span>

    What host within the DMZ network can be exploited via command injection?
    <span style="color:orangered">WINSERVER-02</span>

    How many Drupal accounts exist on the Drupal site?
    <span style="color:deepskyblue">4</span>

    What version of WordPress is running on WINSERVER-01?
    <span style="color:deepskyblue">5.9.3</span>

    How many plugins are installed on the WordPress site?
    <span style="color:deepskyblue">3</span>

    What WordPress file stores the database configuration?
    <span style="color:deepskyblue">wp-config.php</span>

    Excluding the guest account, how many user accounts are present on WINSERVER-01?
    <span style="color:deepskyblue">4</span>

    What is the total number of open TCP ports running on WINSERVER-02?
    <span style="color:deepskyblue">14</span>

    What Windows utility can be used to download files from a remote web server?
    <span style="color:deepskyblue">certutil</span>

🧪 <span style="color:gold">Questions with Methodology</span>

    How many hosts on the DMZ network are running Windows?
    <span style="color:gold">Method:</span> Check OS fingerprinting results from nmap.

    How many hosts on the DMZ network are running a database server?
    <span style="color:gold">Method:</span> Scan ports 3306, 5432, 1433, 1521, 27017.

    What version of Windows is running on the host running WordPress?
    <span style="color:deepskyblue">Windows Server 2012</span>

    What is the IP address of the host vulnerable to an SSH brute force attack?
    <span style="color:gold">Method:</span> Identify host with open port 22 and weak credentials.

    What is the IP address of the FTP server that contains a file called updates.txt?
    <span style="color:deepskyblue">192.168.100.52</span>

    What host on the DMZ network is running a database server on port 3307?
    <span style="color:deepskyblue">192.168.100.50</span>

❓ <span style="color:red">Unanswered Questions (Need Further Enumeration)</span>

    What is the password of the user account "mary" on WINSERVER-03?
    <span style="color:red">Requires credential dumping or cracking</span>

    What is the root password of the MySQL database on the server running Drupal?
    <span style="color:red">Check my.cnf or memory scraping</span>

    What user account is a member of the local administrators group on WINSERVER-03?
    <span style="color:red">Run net localgroup administrators post-exploitation</span>

    What is the hashing algorithm used to hash user account passwords on both Linux servers?
    <span style="color:red">Inspect /etc/shadow – likely SHA-512 ($6$)</span>

    What is the value of the flag C:\Users\mike\Documents\flag.txt?
    <span style="color:red">Access host and read the file</span>

    What is the value of the flag /home/auditor/flag.txt on the Drupal server?
    <span style="color:red">Local access needed</span>

    What is the value of the flag C:\Users\Administrator\flag.txt on WINSERVER-03?
    <span style="color:red">Post-exploitation required</span>
