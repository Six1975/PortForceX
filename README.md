PortForceX - Tool Description
PortForceX is a brute-force attack tool designed to test login credentials on open ports. It automates the process of trying multiple username and password combinations against a target service running on a specific port.

How It Works:
Loads a list of usernames and passwords from text files.

Attempts to authenticate to the target IP and port using brute force.

Verifies the target’s availability via a ping test before starting the attack.

Displays each login attempt and stops upon a successful authentication.

![image](https://github.com/user-attachments/assets/b6301aa9-a498-4e6b-95c4-7f60d52f6c2a)


Usage:

sh
Copy
Edit

(  python port_force.py -t <IP> -p <PORT> -u <USER_LIST> -P <PASS_LIST>  )

Example:
sh
Copy
Edit

(  python port_force.py -t 192.168.0.1 -p 22 -u users.txt -P passwords.txt  )

Arguments:
-t or --target → Target IP address

-p or --port → Port number to attack

-u or --user → File containing usernames

-P or --pass → File containing passwords

Important Notes:

⚠️ Unauthorized use of this tool is illegal and may lead to serious consequences.

✅ For ethical penetration testing only. Ensure you have permission before use.

