سلام متین محمدی هستم کلاس 108 مدرسه تلاش
1-توضیح درمورد نحوه ساخت این پروژه:
در مرحله اول:برنامه ی به نام (نودجی اس) را نصب کردیم
در مرحله دوم:برنامه ی به نام (گیت) را نصب کردیم
در مرحله سوم:وارد برنامه ی (گیت بش) شدیم و شروع به کد زدن کردیم 
ترتیب کدهایی که زدیم:
1.```npm -v```
2.```npm install -g @vue/cli```
3.```npm install npm@latest -g```
4.```npm install --global yarn```
5.```yarn --version```
6.```node --version```
7.```clear```این دستور هم صفحه ی گیت بش را تمیز میکنه
8.```cd ~```
برای اطمینان این 3 تا کد ها را هم زدیم تا از ورژن ها مطمئن بشیم.9
1.```node -v```.3```yarn -v```.3```npm -v```
10.```Set-ExecutionPolicy -ExecutionPolicy Undefined -Scope LocalMachine```
11.```cd ~```الان به ساخت پوشه ها رسیدیم
12.```mkdir projects```
13.```cd projects```
14.```mkdir talash && cd talash```
15.```ls``` List این کد برای لیست کردن محتویات پوشه است و مخفف است
16.```yarn create vite first-app --template vue```
17.```cd first-app```
18.```yarn```
19.```yarn dev```
http://localhost:3000/ :بعد از انجام این کار ها این آدرس را به ما میده
بعد از ورود به این آدرس پروژه ساخته و ران میشه
2-و توضیح کلی درمورد این برنامه frist-app محتوای پوشه
1*Mohtavaye poshe first-app:
1_.vscode
2_dist
3_node_modules
4_public
5_src
6_.gitignore
7_index.html
8_package.json
9_README.md
10_vite.config.js
11_yarn.lock
2*توضیح کلی درمورد برنامه:
است که ما کدهامون را برای ساخت یک وب سایت آنجا میزنیمindex.htmlیکی از قسمت های مهم این برنامه 
است میتونیم داخلش رنگ و فونت و سایز نوشتمون رو تغییر بدیمcomponentsوsrc که در داخل پوشه HelloWorld.vue این پروژه قسمت های مختلفی داره مثل بخش