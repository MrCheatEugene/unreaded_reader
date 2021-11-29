# unreaded_reader
Python script for reading unread emails from specific person.
# How to use
Syntax is:
```py unread.py [Email/Username] [Password] [Email/Username of that specific person] [IMAP server]```

where ```[Email/Username]``` is an email or your name(may be not supported) on the service(Example. Username on example.com IMAP server, with e-mail root@example.com will be root );

where ```[Password]``` is your password from E-mail on that imap server(basically, an e-mail account password) in an unencrypted form;

where ```[Email/Username of that specific person]``` is an email of the sender;

and where ```[IMAP server]``` is an IMAP server.

Example:

```py unread.py root@example.com 12345qwerty sender@another-example.com example.com```

# License

Code distributes by Unlicense license. Basically, it's free, no attribution required, do whatever you want with it.
Fork it, Steal it, Use it.
