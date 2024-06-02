# printer
Level: Easy

Description:
```
I have been trying to access the control panel for my multifunction printer but haven't had any luck remembering the password. Can you help me get logged in?
```

## Writeup
Web Exploitation challenge. The link takes you to a website. The first thing to check is the `/robots.txt` page. This reveals a disallow access to `/notes.txt`. Inside is a file that randomly generates a dev password that can be used to log in. Upon logging in, the flag is found.

**Flag** - `C1{pr1nt1ng_fl4g5}`
