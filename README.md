<div style="text-align: center;">

# PenShi 
</div>

<div style="text-align: right;">

## الدليل بالعربية 

### جدول المحتويات

- [لمحة عامة](#لمحةعامة)
- [الميزات](#الميزات)
- [التثبيت](#التثبيت)
- [المساهمة](#المساهمة)
- [الترخيص](#الترخيص)

### لمحة عامة

 سكريبت لإدارة قواعد جدار الحماية * على أنظمة لينكس . يعمل هذا سكريبت على أتمتة عملية إدارة  قواعد جدار الحماية (اضافة ، عرض ، ازالة ، نسخ إحتياطي وإستعادة ) ، مما يسهل على مديري  الأنظمة الحفاظ على أمان الشبكة.

*: iptables

### الميزات

- إضافة قواعد جدار حماية جديدة
- إزالة قواعد جدار الحماية الحالية (الكل أو قاعدة واحدة)
- سرد قواعد جدار الحماية الحالية
- النسخ الاحتياطي واستعادة القواعد


### التثبيت والإستخدام

- قُم بتزيل المستودع <br>
 إفتح الطرفية في مكانك المفضل :

```bash
git https://github.com/Lmuhammed/Penguin-SHIELD-linux-iptables.git
```

- قُم بالدخول إلى مجلد المُستودع 

```bash
   cd Penguin-SHIELD-linux-iptables/PenShi
```
- تغيير صلاحيات البرنامج، حسب حاجتك ، مثال : <br> 

 ```bash
    chmod 700 ./PenShi
```

- شغل البرنامج : 
    
 ```bash
    ./PenShi
```

### المساهمة

إذا لاحظت أي مشكلة أو درت المُساهمة في التطوير ، لا تتردد في <a href="https://github.com/Lmuhammed/Penguin-SHIELD-linux-iptables/issues">الإبلاغ غن خطأ</a>
أو قم بنسخ المُستودع وأرسل التغييرات للمُراجعة .

### الترخيص

موزعة بموجب ترخيص GPL3. انظر 'LICENSE.txt' لمزيد من المعلومات.


</div> 

# PenShi  

### A iptables Firewall Management Script

### English manual  

#### Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

## Overview

PenShi , The iptables Management Script is a Bash script designed to automate the task of managing firewall rules for the iptables. This script simplifies the process of adding, removing, and listing firewall rules, making it easier for system administrators to maintain network security.

## Features

- Add new firewall rules
- Remove existing firewall rules (all or single)
- List current firewall rules
- Backup and restore rules

## Installation

1. Clone the repository :
   ```bash
   git clone https://github.com/Lmuhammed/Penguin-SHIELD-linux-iptables

2. Navigate to the project folder :
   ```bash
   cd Penguin-SHIELD-linux-iptables/PenShi

3. Change the script's permissions, depending on your needs: 
- Example
    ```bash
    chmod 700 ./PenShi

4. Start the program : 
- Verify that BASH instaled in #!/bin/bash 
    ```bash
    ./PenShi

- Follow the instructions

#### Contributing

If you notice any issues or want to contribute to the development, feel free to  <a href="https://github.com/Lmuhammed/Penguin-SHIELD-linux-iptables/issues">report a bug</a> or  fork the repo and commit changes as PULL REQUEST

#### License

Distributed under the GPL3 License. See `LICENSE.txt` for more information.