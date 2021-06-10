# Os9
Os9

سوال یک:

gpasswd:

-a: gpasswd -a username groupname

این دستور یوزرنیم را به گروه اضافه میکند.

-d: gpasswd -d username groupname

این دستور یوزرنیم را از گروه حذف میکند

-A: gpasswd -A username groupname

یوزرنیم را ادمین گروه میکند.

chown:

-f: برای جلوگیری از نمایش پیغام های خطا

-R: مالک یک فایل و محتویات آن را به صورت برگشتی تغییر میدهد

-v: تغییرات انجام شده در مالکیت را نمایش میدهد

سوال دوم:

با دستورات زیر میتوان نام کاربر فعلی را فهمید.

echo $USER

whoami

با دستور زیر میتوان شماره کاربر و شماره گروه را بدست آورد

id

سوال سوم:

useradd oslab: کاربر مورد نظر ساخته میشود

passwd oslab: با این دستور رمز عبور برای این کاربر تعیین میکنیم

سوال چهارم:

sudo groupadd sadjad: ساخت گروهی با نام سجاد

sudo groupadd Uni: ساخت گروهی با نام یونی

sudo usermod -G sadjad,Uni oslab: عضو کردن کاربر ساخته شده به دو گروه سجاد و یونی

sudo gpasswd -A oslab sadjad: تعیین کردن این کاربر به عنوان ادمین گروه سجاد

سوال پنجم:

sudo useradd os2: ساخت کاربر مورد نظر

sudo usermod -G sadjad os2: اضافه کردن کاربر ساخته شده به گروه سجاد

sudo userdel os2: حذف کاربر مورد نظر
