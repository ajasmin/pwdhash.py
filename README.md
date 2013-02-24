Fork of the (mac only) [ali01/pwdhash.py][1] that uses [pyperclip][2] for cross platform clipboard access.

**Usage:**

    pwdhash.py example.com  # Use domain from command line, prompt for password
                            # and copy the resulting hashed password to clipboard


    pwdhash.py -c           # Use the site URL from clipboard, prompt for password
                            # and copy the resulting hashed password to clipboard


    pwdhash.py              # Prompt for site URL and password and copy the
                            # resulting hashed password to clipboard



For details on PwdHash see https://www.pwdhash.com/

[1]: https://github.com/ali01/pwdhash.py
[2]: http://coffeeghost.net/2010/10/09/pyperclip-a-cross-platform-clipboard-module-for-python/
