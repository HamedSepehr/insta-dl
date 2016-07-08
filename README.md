# instadl (instagram downloader)
Instagram downloader bash script.


# Installation:

```
# wget https://raw.githubusercontent.com/mashhadlug/instadl/master/instadl -O /usr/local/bin/instadl
# chmod +x /usr/local/bin/instadl
```
Hint: you need root permissions (`sudo` may do well).

# Usage:

```
Usage: instadl [-h] [Instagram Share URL] [-u UserName]
Example: instadl https://instagram.com/p/9aagaUKT7-/
Example: instadl -u UserName

Try ‘instadl -h’ for help.
```

# Author
- hamedsepehry[at]yahoo[dot]com

# CHANGELOG
- version 0.1.2
 - added get all media by username.
 - used better outputs (colorify).

- version 0.1.1
 - added proper exit statuses.
 - used better outputs.
 - added network timeout checks.
