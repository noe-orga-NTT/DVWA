# ***REMOVED***

إن  Damn Vulnerable Web Application (DVWA) هو تطبيق ويب تم إضعافه عمداً ومصمم بـ PHP / MySQL. الهدف الرئيسي هو مساعدة مختصي أمن المعلومات وذلك باختبار مهاراتهم وأدواتهم في بيئة تشبه البيئة الحقيقية، ومساعدة مطوري الويب على فهم طرق تأمين تطبيقات الويب بشكل أفضل ومساعدة كل من الطلاب والمدرسين في التعرف على أمان تطبيقات الويب في بيئة محكمة.

الهدف من DVWA هو **التدرب على بعض نقاط الضعف على الويب الأكثر شيوعًا** ، ضمن **مستويات مختلفة من الصعوبة** ، بواجهة بسيطة ومباشرة.
يرجى ملاحظة أن هناك ** ثغرات موثقة وغير موثقة ** في هذا التطبيق. هذا متعمد. نحن نشجع على محاولة اكتشاف أكبر عدد ممكن من المشكلات.
- - -

## تحذير!

إن  Damn Vulnerable Web Application (DVWA) ضعيف للغاية أمنياً! **لا تضعه في مجلد html العام لمزود الاستضافة الخاص بك أو الخوادم التي تعمل على الانترنت** ، إذ أنه سيتم اختراقها. يُوصى باستخدام كيان افتراضي (مثل [VirtualBox] (https://www.virtualbox.org/)  أو [VMware] (https://www.vmware.com/)) ، ويتم تعيينه على وضع شبكة NAT، يمكنك تنزيل وتثبيت [XAMPP] (https://www.apachefriends.org/en/xampp.html) لخادم الويب وقاعدة البيانات.


### إخلاء مسؤولية

نحن لا نتحمل مسؤولية الطريقة التي يستخدم بها أي شخص هذا التطبيق (DVWA). إذ أننا أوضحنا أغراض التطبيق ولا ينبغي استخدامه بشكل ضار. لقد أصدرنا تحذيرات واتخذنا تدابير لمنع المستخدمين من تثبيت DVWA على خوادم الويب الحقيقية. إذا تم اختراق خادم الويب الخاص بك عن طريق تثبيت DVWA ، فهذه ليست مسؤوليتنا ، بل تقع على عاتق الشخص / الأشخاص الذين قاموا بتحميله وتثبيته.

- - -

## ترخيص

هذا الملف جزء من Damn Vulnerable Web Application (DVWA).

يعد تطبيق Damn Vulnerable Web Application (DVWA) برنامجًا مجانيًا: يمكنك إعادة توزيعه و / أو تعديله
بموجب شروط   GNU General Public License  كما تم نشرها بواسطة
Free Software Foundation ، إما الإصدار 3 من الترخيص ، أو 
(حسب اختيارك) أي إصدار لاحق.

يتم توزيع Damn Vulnerable Web Application (DVWA) لتحقيق الفائدة ، 
ولكن دون أي ضمان ؛ حتى بدون الضمان الضمني لـ 
القابلية للتسويق أو الملاءمة لغرض معين. يرجى الاطلاع على 
ترخيص  GNU General Public License لمزيد من التفاصيل.


يجب أن تكون قد تلقيت نسخة من ترخيص    GNU General Public License 
مع   Damn Vulnerable Web Application (DVWA)، إذا لم تتلقى هذه الرخصة، يرجى الاطلاع  على   <https://www.gnu.org/licenses/>.

- - -

## الترجمة

هذا الملف متوفر بعدة لغات:

- الصينية: [简体中文](README.zh.md)
- التركية: [Türkçe](README.tr.md)
- االعربية: [العربية](README.ar.md)

إذا كنت ترغب في المساهمة في ترجمة ، يرجى تقديم PR . ولا يعني ذلك مجرد استخدام خدمة الترجمة من Google وإرسال المساهمة ، فسيتم رفضها.

- - -

## التحميل

توجد إصدارات مختلفة من DVWA حولها ، والإصدار الوحيد المدعوم هو أحدث مصدر من مستودع GitHub الرسمي. يمكنك إما سحب نسخة clone من الريبو Repo:

```
git clone https://github.com/digininja/DVWA.git
```

أو  [تحميل ملف ZIP للملفات](https://github.com/digininja/DVWA/archive/master.zip).

- - -

## التثبيت

**يرجى التأكد من وجود ملف config / config.inc.php الخاص بك. إن وجود ملف config.inc.php.dist بمفرده لن يكون كافيًا ويجب عليك تعديله ليلائم بيئتك وإعادة تسميته إلى config.inc.php ، قد يخفي Windows امتدادات الملفات، يجب عليك إظهارها لتعديل امتداد الملف.](https://www.howtogeek.com/205086/beginner-how-to-make-windows-show-file-extensions/)**

### فيديو التثبيت

- [تثبيت Damn Vulnerable Web Application (DVWA)  على نظام التشغيل Windows 10 ](https://www.youtube.com/watch?v=cak2lQvBRAo) [12:39 دقيقة]

### Windows + XAMPP

أسهل طريقة لتثبيت DVWA هي تحميل [XAMPP] وتثبيته (https://www.apachefriends.org/en/xampp.html) إذا لم يكن لديك خادم الويب جاهز ومعد مسبقاً.

XAMPP هو وسيلة سهلة لتثبيت Apache Distribution لأنظمة Linux و Solaris و Windows و Mac OS X. تتضمن الحزمة خادم الويب Apache و MySQL و PHP و Perl وخادم FTP و phpMyAdmin.

يمكن تحميل XAMPP من هنا:
<https://www.apachefriends.org/en/xampp.html>

ببساطة قم بفك ضغط dvwa.zip ، ضع الملفات التي تم فك ضغطها في مجلد html العام ، ثم اطلب العنوان التالي من المتصفح: `http://127.0.0.1/dvwa/setup.php`

### Linux Packages
إذا كنت تستخدم توزيعة Linux مبنية على Debian ، فستحتاج إلى تثبيت الحزم التالية _ (أو ما يكافئها) _:

`apt-get -y install apache2 mariadb-server php php-mysqli php-gd libapache2-mod-php`

سيعمل الموقع مع MySQL بدلاً من MariaDB لكننا نوصي بشدة باستخدام MariaDB لأنه يعمل خارج الصندوق، سيتعين عليك إجراء تغييرات لتمكين  MySQL  من العمل بشكل صحيح.

### إعداد قواعد البيانات

لإعداد قاعدة البيانات ، ما عليك سوى الضغط على الزر `Setup DVWA` في القائمة الرئيسية ، ثم االضغط على الزر `Create / Reset Database`. سيؤدي هذا إلى إنشاء / إعادة تعيين قاعدة البيانات وإضافة بعض البيانات.

إذا ظهر خطأ أثناء محاولة إنشاء قاعدة البيانات، فتأكد من صحة بيانات الدخول قاعدة البيانات (اسم المستخدم وكلمة المرور) في الملف `./config/config.inc.php` * وهذا الملف يختلف عن config.inc.php.dist والذي يعتبر مثال.*

تم ضبط قيم المتحولات التالية افتراضياً وفق ما يلي:

```php
$_DVWA[ 'db_server'] = '127.0.0.1';
$_DVWA[ 'db_port'] = '3306';
$_DVWA[ 'db_user' ] = 'dvwa';
$_DVWA[ 'db_password' ] = 'p@ssw0rd';
$_DVWA[ 'db_database' ] = 'dvwa';
```

ملاحظة ، إذا كنت تستخدم MariaDB بدلاً من MySQL (يعد MariaDB افتراضيًا في Kali) ، فلا يمكنك استخدام root كمستخدم، يجب عليك إنشاء مستخدم قاعدة بيانات جديد. للقيام بذلك ، اتصل بقاعدة البيانات بصفتك المستخدم root، ونفذ الأوامر التالية:

```mysql
mysql> create database dvwa;
Query OK, 1 row affected (0.00 sec)

mysql> create user dvwa@localhost identified by 'p@ssw0rd';
Query OK, 0 rows affected (0.01 sec)

mysql> grant all on dvwa.* to dvwa@localhost;
Query OK, 0 rows affected (0.01 sec)

mysql> flush privileges;
Query OK, 0 rows affected (0.00 sec)
```

### تكوينات  أخرى

اعتمادًا على نظام التشغيل الخاص بك وإصدار PHP ، قد ترغب في تغيير التكوين الافتراضي default configuration. سيكون موقع الملفات مختلفًا حسب كل جهاز.

**سمايات المجلد**:

* `./hackable/uploads/` - يجب أن تستطيع خدمة الويب الكتابة على هذا الملف (لتنفيذ وظيفة تحميل الملف).
* `./external/phpids/0.6/lib/IDS/tmp/phpids_log.txt` - يجب أن تستطيع خدمة الويب الكتابة على هذا الملف (إذا كنت ترغب باستخدام PHPIDS).

**PHP تكوين**:

* `allow_url_include = on` - السماح بتضمين الملفات عن بعد  Remote File Inclusions (RFI)   [[allow_url_include](https://secure.php.net/manual/en/filesystem.configuration.php#ini.allow-url-include)]
* `allow_url_fopen = on` -  السماح بتضمين الملفات عن بعد  Remote File Inclusions (RFI)    [[allow_url_fopen](https://secure.php.net/manual/en/filesystem.configuration.php#ini.allow-url-fopen)]
* `safe_mode = off` - (إذا كان إصدار PHP أقل من أو يساوي 5.4) السماح بحقن SQL  - SQL Injection (SQLi) [[safe_mode](https://secure.php.net/manual/en/features.safe-mode.php)]
* `magic_quotes_gpc = off` - (إذا كان إصدار PHP أقل من أو يساوي 5.4) السماح بحقن SQL  - SQL Injection (SQLi) [[magic_quotes_gpc](https://secure.php.net/manual/en/security.magicquotes.php)]
* `display_errors = off` - (اختياري)  إخفاء رسائل تحذير PHP لجعلها أقل إسهابًا  [[display_errors](https://secure.php.net/manual/en/errorfunc.configuration.php#ini.display-errors)]

**الملف:  `config/config.inc.php`**:

* `$_DVWA[ 'recaptcha_public_key' ]` & `$_DVWA[ 'recaptcha_private_key' ]` - يجب توليد قيم هذه المتحولات وذلك من خلال:  https://www.google.com/recaptcha/admin/create

### بيانات الدخول الافتراضية

**اسم المستخدم لاافتراضي  = `admin`**

**كلمة المرور الافتراضية  = `password`**

_...يمكن بسهولة تخمينها باستخدام هجوم Brute Force ;)_

رابط تسجيل الدخول : http://127.0.0.1/login.php

_ملاحظة: سيختلف الرابط في حال تثبيت DVWA في مسار مختلف._

- - -

## Docker حاوية

- [dockerhub صفحة](https://hub.docker.com/r/vulnerables/web-dvwa/)
`docker run --rm -it -p 80:80 vulnerables/web-dvwa`

يرجى التأكد من أنك تستخدم aufs بسبب مشاكل MySQL السابقة. نفذ الأمر `docker info` للتحقق من storage driver. إذا لم يكن aufs ، يرجى تغييره على هذا النحو. هناك أدلة لكل نظام تشغيل حول كيفية القيام بذلك ، لكنها مختلفة تمامًا لذا لن نغطي ذلك هنا.

- - -

## استكشاف الأخطاء وإصلاحها

يفترض هذا أنك تستخدم توزيعة قائمة على Debian ، كـ Debian و Ubuntu و Kali. بالنسبة إلى التوزيعات الأخرى ، اتبع ذلك ، ولكن قم بتعديل الأمر عند الضرورة.

### الحصول على استجابة 40 عند تصفح الموقع

إذا كنت تواجه هذه المشكلة ، فأنت بحاجة إلى فهم مواقع الملفات. بشكل افتراضي ، جذر مستندات Apache (Apache document root  هو المكان الذي يبدأ فيه البحث عن محتوى الويب) هو  `/var/www/html` إذا وضعت الملف `hello.txt` في هذا المجلد، يمكن الوصول إليه بطلب `http://localhost/hello.txt` من المتصفح.

إذا أنشأت مجلد ووضعت الملف فيه - `/var/www/html/mydir/hello.txt` فيمكنك الوصول إلى الملف من الخلال المتصفح بزيارة `http://localhost/mydir/hello.txt`.

يعتبر Linux بشكل افتراضي حساسًا لحالة الأحرف ، وبالتالي في المثال أعلاه ، إذا حاولت التصفح للوصول إلى أي من الروابط التالية، فستحصل على  `404 Not Found`:

- `http://localhost/MyDir/hello.txt`
- `http://localhost/mydir/Hello.txt`
- `http://localhost/MYDIR/hello.txt`

How does this affect DVWA? Most people use git to checkout DVWA into `/var/www/html`, this gives them the directory `/var/www/html/DVWA/` with all the DVWA files inside it. They then browse to `http://localhost/` and get either a `404` or the default Apache welcome page. As the files are in DVWA, you must browse to `http://localhost/DVWA`.

The other common mistake is to browse to `http://localhost/dvwa` which will give a `404` because `dvwa` is not `DVWA` as far as Linux directory matching is concerned.

So after setup, if you try to visit the site and get a `404`, think about where you installed the files to, where they are relative to the document root, and what the case of the directory you used is.

### "Access denied" running setup

إذا رأيت ما يلي عند تشغيل البرنامج النصي للإعداد setup script ، فهذا يعني أن اسم المستخدم أو كلمة المرور في ملف التكوين لا يتطابقان مع تلك التي تم تكوينها في قاعدة البيانات:

```
Database Error #1045: Access denied for user 'notdvwa'@'localhost' (using password: YES).
```

The error is telling you that you are using the username `notdvwa`.

يشير الخطأ التالي إلى أنك وجهت ملف التكوين إلى قاعدة البيانات الخاطئة.

```
SQL: Access denied for user 'dvwa'@'localhost' to database 'notdvwa'
```

إنه يقول أنك تستخدم المستخدم `dvwa` وتحاول الاتصال بقاعدة البيانات` notdvwa`.

أول شيء يجب القيام به هو التحقق مرة أخرى مما تعتقد أنك قد وضعته في ملف التكوين صحيح ومطابق للبيانات الفعلية.

إذا كان يتطابق مع ما تتوقعه ، فإن الشيء التالي الذي يجب فعله هو التحقق من أنه يمكنك تسجيل الدخول كمستخدم في محرر الأوامر command line. بافتراض أن لديك مستخدم قاعدة بيانات لـ `dvwa` وكلمة مرور هي `p@ssw0rd`، قم بتنفيذ الأمر التالي:

```
mysql -u dvwa -pp@ssw0rd -D dvwa
```

*ملاحظة: لا يوجد مسافة بعد  -p*

إذا ظهر الخرج التالي، فكلمة المرور صحيحة:

```
Welcome to the MariaDB monitor.  Commands end with ; or \g.
Your MariaDB connection id is 14
Server version: 10.3.22-MariaDB-0ubuntu0.19.10.1 Ubuntu 19.10

Copyright (c) 2000, 2018, Oracle, MariaDB Corporation Ab and others.

Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.

MariaDB [dvwa]>
```

نظرًا لأنه يمكنك الاتصال في سطر الأوامر ، فمن المحتمل أن يكون هناك خطأ ما في ملف التكوين ، تحقق مرة أخرى من ذلك ثم قم بإنشاء تذكرة للمشكلة إذا كنت لا تزال غير قادر على التشغيل.

If you see the following, the username or password you are using is wrong. Repeat the [Database Setup](#database-setup) steps and make sure you use the same username and password throughout the process.

```
ERROR 1045 (28000): Access denied for user 'dvwa'@'localhost' (using password: YES)
```

If you get the following, the user credentials are correct but the user does not have access to the database. Again, repeat the setup steps and check the database name you are using.

```
ERROR 1044 (42000): Access denied for user 'dvwa'@'localhost' to database 'dvwa'
```

الخطأ النهائي  الذي يمكن أن تحصل عليه هو :

```
ERROR 2002 (HY000): Can't connect to local MySQL server through socket '/var/run/mysqld/mysqld.sock' (2)
```

هذه ليست مشكلة مصادقة ولكنها تخبرك أن خادم قاعدة البيانات لا يعمل. يمكنك تشغيله بتنفيذ الأمر التالي

```sh
sudo service mysql start
```

### Unknown authentication method

With the most recent versions of MySQL, PHP can no longer talk to the database in its default configuration. If you try to run the setup script and get the following message it means you have configuration.

```
Database Error #2054: The server requested authentication method unknown to the client.
```

You have two options, the easiest is to uninstall MySQL and install MariaDB. The following is the official guide from the MariaDB project:

<https://mariadb.com/resources/blog/how-to-migrate-from-mysql-to-mariadb-on-linux-in-five-steps/>

بدلاً من ذلك، اتبع الخطوات التالية:

1. As root, edit the following file: `/etc/mysql/mysql.conf.d/mysqld.cnf`
1. Under the line `[mysqld]`, add the following:
  `default-authentication-plugin=mysql_native_password`
1. Restart the database: `sudo service mysql restart`
1. Check the authentication method for your database user:

    ```sql
    mysql> select Host,User, plugin from mysql.user where mysql.user.User = 'dvwa';
    +-----------+------------------+-----------------------+
    | Host      | User             | plugin                |
    +-----------+------------------+-----------------------+
    | localhost | dvwa             | caching_sha2_password |
    +-----------+------------------+-----------------------+
    1 rows in set (0.00 sec)
    ```

1. You'll likely see `caching_sha2_password`. If you do, run the following command:

    ```sql
    mysql> ALTER USER dvwa@localhost IDENTIFIED WITH mysql_native_password BY 'p@ssw0rd';
    ```

1. Re-running the check, you should now see `mysql_native_password`.

    ```sql
    mysql> select Host,User, plugin from mysql.user where mysql.user.User = 'dvwa';
    +-----------+------+-----------------------+
    | Host      | User | plugin                |
    +-----------+------+-----------------------+
    | localhost | dvwa | mysql_native_password |
    +-----------+------+-----------------------+
    1 row in set (0.00 sec)
    ```

بعد كل ما سبق، يجب أن تعمل عملية الإعدد بحالتها الطبيعية.

إذا كنت تريد المزيد من المعلومات يرجى الاطلاع على:  <https://www.php.net/manual/en/mysqli.requirements.php>.

### Database Error #2002: No such file or directory.

إذا كان خادم قاعدة البيانات لا يعمل. وكنت تسخدم توزيعة مبنية على Debian، يمكن القيام بذلك باستخدام:

```sh
sudo service mysql start
```

### معالجة الأخطاء  "MySQL server has gone away" و  "Packets out of order"

هناك عدة أسباب لحدوث هذه الأخطاء ، ولكن السبب المرجح هو عدم توافق إصدار خادم قاعدة البيانات مع إصار PHP.

وهو الأكثر شيوعًا عند تشغيل أحدث إصدار من MySQL و PHP ، لا يعمل التطبيق بشكل جيد. ولذلك ننصح باستبدال MySQL  بـ MariaDB  لأن هذه المشكلة لا يوجد دعم لها في الوقت الحالي.

لمزيد من المعلومات، يرجى الاطلاع على:

<https://www.ryadel.com/en/fix-mysql-server-gone-away-packets-order-similar-mysql-related-errors/>

### لا يعمل حقن SQL باستخدام  PHP v5.2.6

توقف دعم PHP 5.x منذ يناير 2019 ، لذلك نوصي بتشغيل DVWA بإصدار 7.x الحالي ، إذا كنت مضطراً لاستخدام الإصدار 5.x ..

إذا كنت تستخدم إصدار PHP v5.2.6 أو أحدث ، فستحتاج إلى القيام بما يلي حتى يعمل حقن SQL والثغرات الأمنية الأخرى.

في ملف  `.htaccess`:

استبدل الآتي:

```php
<IfModule mod_php5.c>
    php_flag magic_quotes_gpc off
    #php_flag allow_url_fopen on
    #php_flag allow_url_include on
</IfModule>
```

بهذا:

```php
<IfModule mod_php5.c>
    magic_quotes_gpc = Off
    allow_url_fopen = On
    allow_url_include = On
</IfModule>
```

### عند فشل حقن الأوامر Command Injection
قد لا يكون لدى Apache امتيازات عالية كافية لتنفيذ الأوامر على خادم الويب. إذا كنت تقوم بتشغيل DVWA على نظام Linux ، فتأكد من تسجيل الدخول كمستخدم root. أما في Windows  قم بتسجيل الدخول كـ administrator.

### Why can't the database connect on CentOS?

قد تواجه مشاكل مع SELinux، قم إما بتعطيل SELinux أو تشغيل هذا الأمر للسماح لخادم الويب بالتخاطب مع قاعدة البيانات:

```
setsebool -P httpd_can_network_connect_db 1
```

### Anything else

للحصول على أحدث معلومات استكشاف الأخطاء وإصلاحها ، يرجى قراءة كل من التذاكر المفتوحة والمغلقة في  الريبو  git repo:

<https://github.com/digininja/DVWA/issues>

قبل إرسال التذكرة ، يرجى التأكد من تشغيل أحدث إصدار من الكود من الريبو. هذا ليس أحدث إصدار ، هذا هو أحدث كود من الفرع الرئيسي master branch . 

في حالة إنشاء تذكرة ، يرجى تقديم المعلومات التالية على الأقل:

- نظام التشغيل
- آخر 5 أسطر من سجل أخطاء خادم الويب مباشرة بعد حدوث أي خطأ تقوم بالإبلاغ عنه
- إذا كانت المشكلة تتعلق بمصادقة قاعدة البيانات ، فانتقل إلى الخطوات السابقة أعلاه وقم بتصوير كل خطوة. وأرسلها مع لقطة شاشة لقسم ملف التكوين الذي يظهر مستخدم قاعدة البيانات وكلمة المرور.
- وصف كامل للخطأ الذي يحدث ، وما تتوقع حدوثه ، وما حاولت فعله لإصلاحه. "تعطل تسجيل الدخول" لا يكفي بالنسبة لنا لفهم مشكلتك والمساعدة في حلها.


- - -

## SQLite3 SQL Injection

_ الدعم لهذا الأمر محدود ، قبل طرح مشكلتك، يرجى التأكد من استعدادك للعمل على تصحيح الأخطاء ، ولا تكتب ببساطة "أنه لا يعمل" ._

بشكل افتراضي ، يتم تنفيذ SQLi و Blind SQLi على خادم MariaDB / MySQL المستخدم في الموقع ولكن من الممكن التبديل لإجراء اختبار SQLi  على SQLite3 بدلاً من ذلك.

لن نتطرق إلى كيفية تشغيل SQLite3 مع PHP ، ولكنها من المفترض أن تكون حالة بسيطة وذلك بتثبيت حزمة `php-sqlite3` والتأكد من تفعيلها.

لإجراء هذا التبديل ، قم ببساطة بتعديل ملف التكوين وإضافة أو تعديل هذه الأسطر:

```
$_DVWA["SQLI_DB"] = "sqlite";
$_DVWA["SQLITE_DB"] = "sqli.db";
```

بشكل افتراضي ، يستخدم الملف `database / sqli.db` ، إذا أحدثت خللا فيه، فما عليك سوى نسخ محتويات ملف` database / sqli.db.dist` ولصقها في الملف الذي تعمل عليه.

التحديات هي نفسها تمامًا مثل MySQL ، ولكنك الآن تنفذها في SQLite3  بدلاً من MySQL.

- - -

## روابط

الصفحة الرئيسية: <https://dvwa.co.uk/>

الصفحة الرئيسية للمشروع: <https://github.com/digininja/DVWA>

*تم إنشاؤها بواسطة فريقDVWA *
