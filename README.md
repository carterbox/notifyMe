#notifyMe

This is a quick little module to allow you to send yourself emails simply by writing: 
```
import notifyMe as nm
notifyMe.notifyMe("name@domain","Your message goes here")
```

The module stores your email password in plaintext, so for the *love of god* don't ever commit this without checking to make sure you've erased your password. Really, just never use this for anything actually serious.