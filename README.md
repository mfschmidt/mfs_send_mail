Send gmail from the command line.

You'll need to create your own credentials with google cloud for your own gmail address.
After you have that, save the credentials in a json file to `~/.ssh/.gmail_credentials.json`.
Then you can install this project and run this python script.

```bash
mfs_send_mail \
to@gmail.com \
"subject" \
"body" 
```

Note there is no "from" or "sender" address.
The email will show up as coming from whichever address you authorized in Oauth.
