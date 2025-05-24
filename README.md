# EmailGenerateTemp
Install Package:
```
pkg install git
git clone https://github.com/Kuzan55/EmailGenerateTemp.git
pkg install python3
```

Run:
```
cd EmailGenerateTemp 
python3 temp_email.py
```

python:
```
import requests
import time
import random
import string
```

✅ Key Features:
1. **Uses 1secMail API** which is currently working
2. **Generates random email addresses** with different domains
3. **Monitors inbox** for new messages
4. **Provides clickable links** to read messages
5. **Simple and reliable** with proper error handling
   

🔄 Alternative Options:
If 1secMail doesn't work, try these quick alternatives:

**Option 1: GuerrillaMail**

```
response = requests.get("https://www.guerrillamail.com/ajax.php?f=get_email_address")
email = response.json()['email_addr']
```

**Option 2: Temp-Mail.io**
```
response = requests.get("https://api.temp-mail.io/v3/email/new")
email = response.json()['email']
```
