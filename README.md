این روش در حال حاضر مسدود شده است.
🔴 لطفا ویدیو جدید را ببینید:
https://youtu.be/nXizFiThGl0

------------------

راه اندازی سرور فیلترشکن شخصی

لینک ویدیو آموزشی: # 

ساخت یک سرور با سیستم عامل: Centos 7 x86 (or) Centos 7 x64

لاگین کردن به سرور با نرم افزار putty و اجرای دستور زیر:

cd /tmp/ && yum install git -y && git clone https://github.com/m9h4s/Personal-vpn.git && cd Personal-vpn/ && sed -i -e 's/\r$//' centos7.sh && chmod 755 centos7.sh && ./centos7.sh 

دستورات زیر برای اضافه کردن کاربر به سرور:

useradd [username] - 
passwd [username]
