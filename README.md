[![made-with-bash](https://img.shields.io/badge/Made%20with-Bash-1f425f.svg)](https://www.gnu.org/software/bash/)

# Random Password Generator
## About:
This script can be used to generate a random password.  
Inspired by this: https://delinea.com/resources/password-generator-it-tool

## Usage:
```bash
pwdgen [options] [password_length]
```
## Options:
```
    --nosymbols      Exclude symbols (!@#$%^&*()+) from the password
    --nonumbers      Exclude numbers from the password
    --nolowercase    Exclude lowercase letters from the password
    --nouppercase    Exclude uppercase letters from the password
    --ignoresimilar  Ignore similar characters (oO0il1)
    --duplicates     Allow duplicate characters in the password
    --includespecific <characters> Include specific characters in the password
    --help            Show this help message

```