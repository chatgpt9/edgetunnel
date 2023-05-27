سایت هایی که از cdn کلودفلر استفاده می کنن با این روش باز نمیشن. اینستا ، تلگرام، توِییتر، تیک تاک مشکلی ندارن. اگر باز نشدن میتونه مشکل dns  یا کلاینت باشه.  برای بعضی از دوستان روی v2rayng مشکل داشت.


از این روش برای کارهای مالی و کارهایی که روی آی پی حساس هستن استفاده نکنین چون آی پی استاتیک نیست همش در حال تغییر براتون مشکل درست نشه اما برای کارهای معمولی به همراه آی پی تمیز مشکلی نیست. سرعت خیلی خوبی هم داره وبه شرت آی پی خوب. موفق باشید



1.وارد آدرس زیر بشین و ریپو fork کنین  . بعد از این صفحه روی create fork بزنین. 

https://github.com/JustHussein/edgetunnel/


2.وارد کلودفلر بشین و وارد قسمت workes and pages بشید. pages انتخاب کنین و بعد connect to git.




3.ریپویی که تو مرحله اول ساختین انتخاب کنین.بعد begin setup.


4.با هیچی تو صفحه جدید کار نداریم جز 4 تا مورد . خواستین بالا میتونین اسم پروژه عوض کنین. دستور های زیر مطابق عکس وارد کنین.

Build command                    npm run cf-page-vless

Build output directory          dist/apps/cf-page-vless

![image](https://github.com/JustHussein/edgetunnel/assets/68867816/f9605383-6c0c-47c9-9969-c9405499c4cf)



5.میام پایین تر روی Add variable میزنیم تو تا مقدار میسازیم و پرشون میکنیم. uuid هم میتونید از لینک زیر بردارید.

https://www.v2fly.org/awesome/tools.html



UUID                                  053e3736-2405-4bb8-8bc5-0b3b635fc4fd

NODE_VERSION                 18

![image](https://github.com/JustHussein/edgetunnel/assets/68867816/a7c8dc47-047e-4231-b0ec-d46bad5824c5)





6.صبر می کنیم نصب تموم بشه و بعد continue to project

![image](https://github.com/JustHussein/edgetunnel/assets/68867816/e618fcf8-c861-4659-80c8-8a4a40ca0e05)

![image](https://github.com/JustHussein/edgetunnel/assets/68867816/805dc0e2-7880-4db3-9011-8534d74950c4)



7. وارد Settings بشید و builds & deployments. برید پایین 

Build system version
جفت گزینه

Configure Production build system
و

Configure Preview build system 
بزارین روی version 2 و بعد save کنین.

![image](https://github.com/JustHussein/edgetunnel/assets/68867816/d22c7ba1-01a6-4d7d-ae19-72e251e59d12)



8.آدرس ورکر بزنین تو مرورگر ازتون یوزر و پس میخواد . uuid برای جفت استفاده میشه. uuid میشه اونی تو مرحله 5 تعریف کردین


9. وارد همچین صفحه ای میشین و روی v2ray میزنین. qr code ذخیره کنین بزنین داخل کلاینت. همچین چیزی میشه. اون آدرس میبرین تو قسمت host و sni مثل عکس دوم. تو خود قسمت آدرس هم آپی تمیز یا ساب آی پی تمیز.




تو قسمت sni هم میتونین اون youre.domain.com با حروف الکی پر کنین مثل yourcnxz.domain.com اگر فیلتر شد یک حرف کم یا زیاد کنین کار میوفته . روی آدرس ورکر تست نکردم  اما روی ساب دامین جوابه. این برای فیلتر شدن sni جوتب هست دامنه فیلتر شده یا آدرس ورکر نه.

آگر براتون کار نمیکنه یعنی از آی پی و دامنه و ورکر مطمین هستین اما کار نمیکنه utls تغییر بدین اول بزارین روی random. اگر کار کرد اما توِییتر و یوتیوب باز نکرد dns تغییر بدین. برید تو تنظیمات کلاینت remote dns. چندتا میزارم تست کنین

9.9.9.9

208.67.220.220

198.153.192.1

77.88.8.8

