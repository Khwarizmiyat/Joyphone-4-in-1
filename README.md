<p align="center"><img src="assets/logo.png" width="140" alt="Joyphone"></p>

<h1 align="center">Joyphone</h1>

<p align="center"><b>Turn your Android phone into a steering wheel, flight yoke, motorcycle handlebar or gamepad for PC games.</b></p>

<p align="center"><a href="#english">English</a> · <a href="#arabic">العربية</a></p>

---

 

 
. <a name="arabic"></a>
<div dir="rtl" align="right">

## العربية

**حوّل هاتف أندرويد إلى مقود سيارة أو يوك طيران أو مقود دراجة نارية أو يد تحكم لألعاب الكمبيوتر.**

يقرأ Joyphone حساسَي التسارع والجايروسكوب في هاتفك، ويرسل النتيجة عبر الواي فاي أو USB إلى برنامج صغير على ويندوز، فيعرض لألعابك يد Xbox 360 افتراضية. وتعمل معه أي لعبة تقبل يد Xbox.

**[⬇ نزّل أحدث إصدار](../../releases/latest)** — هذا المستودع للتوثيق فقط، أما التطبيق وبرنامج الكمبيوتر فيُنشران كملفات في صفحة الإصدارات.

### الأوضاع

- **مقود السيارة:** أدر الهاتف كمقود. دواستا وقود وفرامل على الشاشة، وفرامل يد (رقمية أو تناظرية مع إمكانية التثبيت)، وتبديل الغيارات، وبوق.
- **يوك الطيران:** الميلان والدفع والسحب بإمالة الهاتف. ذراع خنق وفرامل وأزرار دفة. نمطان: واقعي وأركيد.
- **الدراجة النارية:** أدر الهاتف كمقود دراجة. خنق بلفّ القبضة، وفرامل أمامية وخلفية منفصلتان، وتبديل غيارات، وستارت، وبوق، وكاميرا، ونظر للخلف.
- **يد التحكم:** تخطيط Xbox 360 كامل (عصاتان، وأزرار الاتجاهات، وA/B/X/Y، والأكتاف، والزنادات التناظرية، وBack/Start، وL3/R3)، مع تصويب اختياري بالجايروسكوب أو بلوحة لمس.

### المزايا
-اكثر من 50 اعداد لتوفير اكبر قدر ممكن من الواقعية والراحة 
-اضافة ازرار اضافية وتعديل تخطيط او اسماء الازرار وحفظ التعديلات على شكل مجلدات يمكن فتحها لتتوافق مع كل لعبة 
- اكتشاف تلقائي عبر الواي فاي، أو إدخال عنوان IP يدوياً
- اتصال عبر USB باستخدام جسر التصحيح في أندرويد (adb) دون حاجة إلى واي فاي
- تحريك عناصر الشاشة وتغيير حجمها وإخفاؤها وإعادة تسميتها، وحفظ التخطيطات واستعادتها
- ربط عناصر التحكم بأزرار Xbox أو بمفاتيح لوحة المفاتيح
- ضبط المنطقة الميتة ومنحنى الاستجابة والتنعيم وغيرها لكل وضع، مع شرح مختصر بعلامة (؟) بجانب كل إعداد
- إيقاف اللعبة مؤقتاً عند انقطاع الاتصال بشكل اختياري (زر Start أو مفتاح Esc)
- واجهة عربية وإنجليزية
- إشعارات أذكار إسلامية اختيارية (للواجهة العربية فقط)

### القيود

- برنامج الكمبيوتر يعمل على **ويندوز فقط**.
- يحتاج إلى تعريف **ViGEmBus**، وهو تنزيل منفصل. والمشروع متوقف رسمياً، لكن التعريف ما زال يعمل.
- تختلف النتائج حسب اللعبة وحساسات الهاتف، ولم تُختبر كل الألعاب والأجهزة. استخدمه المطوّر مع BeamNG.drive وMotoGP 15 وAssetto Corsa وlive for speed 
### المتطلبات

| | |
|---|---|
| **الكمبيوتر** | ويندوز 10 أو 11 (64 بت) · تعريف ViGEmBus مثبّت · برنامج الخادم `Joyphone.exe` |
| **الهاتف** | أندرويد 7.0 أو أحدث · حساسا تسارع وجايروسكوب · واي فاي (أو تصحيح USB) |
| **الشبكة** | الكمبيوتر والهاتف على شبكة واي فاي واحدة (وليست شبكة ضيوف أو معزولة) · ملف الشبكة في ويندوز *Private* |
| **جدار الحماية** | السماح لـJoyphone على الشبكات الخاصة: TCP 8080 وUDP 8081 وUDP 9876 |
| **وضع USB** | تفعيل تصحيح USB · كابل بيانات · إنترنت في أول استخدام ليحمّل الخادم أداة adb |

### التثبيت والتشغيل الأول

1. **الكمبيوتر:** ثبّت [تعريف ViGEmBus]() (يحتاج موافقة المسؤول، وأعد التشغيل إن طُلب). نزّل ملف `Joyphone-Server-…-win64.zip` من صفحة الإصدارات وفك ضغطه، ثم شغّل `Joyphone.exe` واسمح له في جدار الحماية على الشبكات الخاصة.
2. **الهاتف:** نزّل ملف `Joyphone-….apk` وافتحه، واسمح بالتثبيت من هذا المصدر عندما يطلب أندرويد، ثم افتح Joyphone.
3. **الاتصال:** إذا كان الجهازان على الواي فاي نفسه فسيجد الهاتف الكمبيوتر تلقائياً، أو اكتب عنوان IP الظاهر في نافذة الخادم. وللاتصال عبر USB: فعّل «تصحيح USB» من خيارات المطوّر في الهاتف، ووصّل الكابل، ووافق على الرسالة التي تظهر في الهاتف.
4. اختر وضعاً، واضغط **معايرة** وأنت تمسك الهاتف بالطريقة التي ستلعب بها، في بعض الاحيان يجب ان تختار يد Xbox داخل اللعبة.

الربط الافتراضي:

| الوضع | الربط |
|---|---|
| المقود | التوجيه ← العصا اليسرى X · الوقود ← RT · الفرامل ← LT · فرامل اليد التناظرية ← العصا اليمنى Y |
| يوك الطيران | Ailerons ← العصا اليسرى X · Elevator ← العصا اليسرى Y · Throttle ← العصا اليمنى Y · Rudder ← العصا اليمنى X · الفرامل ← LT |
| الدراجة | التوجيه ← العصا اليسرى X · الخنق ← RT · الفرامل الأمامية ← LT · الفرامل الخلفية ← العصا اليمنى Y |

### حل المشكلات

- **«Windows protected your PC»:** البرنامج غير موقّع رقمياً. اختر *More info* ثم *Run anyway* بعد التحقق من قيمة SHA-256 (أدناه).
- **تحذير مضاد الفيروسات:** البرامج المغلّفة بـPyInstaller تُصنَّف أحياناً خطأً. قارن قيمة التحقق بملف `SHA256SUMS.txt` قبل التشغيل.
- **الهاتف لا يتصل:** تأكد أن الجهازين على الشبكة نفسها، وأن ويندوز يعدّها *Private*، وأن جدار الحماية يسمح لـJoyphone، وأنه لا توجد شبكة VPN أو ضيوف تعترض. وللاختبار افتح `http://<عنوان-الكمبيوتر>:8080` في متصفح الهاتف؛ فإن لم تُفتح الصفحة فالشبكة أو جدار الحماية يمنع الوصول.
- **اللعبة لا ترى يد التحكم:** تأكد من تثبيت ViGEmBus، وأعد تشغيل اللعبة، واختر يد Xbox.
- **الإيقاف بمفتاح Esc لا يعمل:** يمنع ويندوز المفاتيح المحاكاة عن الألعاب التي تعمل بصلاحية المسؤول.
- **لا تصل إشعارات الأذكار:** اسمح بالإشعارات لـJoyphone وأزل قيود البطارية عن التطبيق


###هل يحوي البرنامج على اي فيروسات ؟؟ , قطعا لا وان كنت تشعر بالشك فابمكانك ارسال الملفات الى موقع virusttottal للتاكد بنفسك 
### التحقق من الملف

```
certutil -hashfile Joyphone-Server-v7.22-win64.zip SHA256
```
قارن الناتج بملف `SHA256SUMS.txt` من الإصدار نفسه.

### الخصوصية

لا يجمع Joyphone أي بيانات شخصية، وليس فيه تحليلات ولا إعلانات ولا حسابات. وتبقى البيانات بين الهاتف والكمبيوتر على شبكتك المحلية أو كابل USB. وقد ينزّل الخادم أداة adb من Google عند أول استخدام لـUSB. والروابط داخل التطبيق (الدعم وتيليجرام والبريد) لا تُفتح إلا عندما تضغط عليها.

### الترخيص

Joyphone برنامج مجاني مغلق المصدر — انظر ملف [LICENSE](LICENSE). ومكوّنات الأطراف الثالثة مذكورة في [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt).

### الدعم والتواصل

من تطوير **شركة خوارزميات المستقلة (Khwarizmiyat)**.
[ادعمنا على باتريون](https://www.patreon.com/cw/Khwarizmiyat) · [تيليجرام](https://t.me/Khwarizmiyat) · [البريد](mailto:mmcg2027@gmail.com)

</div>

---


<a name="english"></a>
## English

Joyphone reads your phone's accelerometer and gyroscope and sends the result over Wi-Fi or USB to a small Windows program, which presents a virtual Xbox 360 controller to your games. Any game that accepts an Xbox controller can use it.

**[⬇ Download the latest release](../../releases/latest)** — this repository contains documentation only; the app and the PC program are published as release files.

### Modes

- **Steering wheel** – rotate the phone like a wheel. On-screen gas and brake pedals, handbrake (digital or analog, with optional latch), gear up/down and horn.
- **Flight yoke** – roll and pitch by tilting the phone. Throttle lever, brakes and rudder buttons. Two styles: Realistic and Arcade.
- **Motorcycle** – rotate the phone like a handlebar. Twist-grip throttle, separate front and rear brakes, gear shift, starter, horn, camera and look-back.

### Features

- Over 50 settings for maximum realism and comfort.
- The addition of "peace" (neutral/safe-state) buttons, along with the ability to customize button layouts or labels; these can be saved as profiles that can be loaded to suit any specific game.
- Automatic discovery over Wi-Fi, or manual IP entry
- USB connection through Android's debugging bridge (adb) – no Wi-Fi needed
- Move, resize, hide and rename on-screen controls; save and restore layouts
- Map controls to Xbox buttons or keyboard keys
- Adjustable deadzone, response curve, smoothing and more for each mode, with a short explanation (?) next to every setting
- Optional pause when the connection drops (Start button or Esc key)
- Arabic and English interface
- Optional Islamic dhikr reminder notifications (Arabic interface only, off by default)

### Limitations

- The PC program runs on **Windows only**.
- It needs the **ViGEmBus** driver, a separate download. The ViGEmBus project is retired, but the driver still works.
- Results depend on the game and on your phone's sensors. Not every game or device has been tested. The developer has used it with BeamNG.drive, MotoGP 15, Assetto Corsa and Live for Speed

### Requirements

| | |
|---|---|
| **PC** | Windows 10 or 11 (64-bit) · ViGEmBus driver installed · Joyphone server (`Joyphone.exe`) |
| **Phone** | Android 7.0 or newer · accelerometer and gyroscope · Wi-Fi (or USB debugging) |
| **Network** | PC and phone on the same Wi-Fi network (not a guest or isolated network) · Windows network profile set to *Private* |
| **Firewall** | Allow Joyphone on private networks: TCP 8080, UDP 8081, UDP 9876 |
| **USB mode** | USB debugging enabled · a data cable · internet access the first time, so the server can download Android platform-tools |

### Install and first run

1. **PC** – install the [ViGEmBus driver](https://github.com/nefarius/ViGEmBus/releases) (administrator approval; restart if asked). Download `Joyphone-Server-…-win64.zip` from the releases page, extract it, run `Joyphone.exe` and allow it through the firewall on *Private* networks.
2. **Phone** – download `Joyphone-….apk`, open it and allow installation from this source when Android asks, then open Joyphone.
3. **Connect** – with both devices on the same Wi-Fi the phone finds the PC automatically, or type the IP address shown in the server window. For USB: enable *USB debugging* in the phone's developer options, plug in the cable and accept the prompt on the phone.
4. Pick a mode, press **Calibrate** while holding the phone the way you will play, then choose the Xbox controller in your game.

Default bindings:

| Mode | Bindings |
|---|---|
| Wheel | Steering ← Left stick X · Gas ← RT · Brake ← LT · Analog handbrake ← Right stick Y |
| Flight yoke | Ailerons ← Left stick X · Elevator ← Left stick Y · Throttle ← Right stick Y · Rudder ← Right stick X · Brakes ← LT |
| Motorcycle | Steering ← Left stick X · Throttle ← RT · Front brake ← LT · Rear brake ← Right stick Y |

### Troubleshooting

- **"Windows protected your PC"** – the program is not code-signed. Choose *More info* → *Run anyway*, after checking the SHA-256 value (below).
- **Antivirus warning** – programs packaged with PyInstaller are sometimes flagged by mistake. Compare the checksum with `SHA256SUMS.txt` before running.
- **Phone cannot connect** – check that both devices are on the same network, that Windows treats it as *Private*, that the firewall allows Joyphone, and that no VPN or guest network is in the way. As a test, open `http://<PC-IP>:8080` in the phone's browser; if the page does not load, the network or firewall is blocking the PC.
- **The game does not see a controller** – make sure ViGEmBus is installed, restart the game, and select the Xbox controller.
- **Esc pause does not work** – Windows blocks simulated keys for games that run as administrator.
- **No reminder notifications** – allow notifications for Joyphone and remove battery restrictions for the app.

  
 ###is the app contain any virus ??? totally no, and if you doubt you can check it by yourself by sendign the files to virustottal###  website
 
### Verify your download

```
certutil -hashfile Joyphone-Server-v7.22-win64.zip SHA256
```
Compare the result with `SHA256SUMS.txt` from the same release.

### Privacy

Joyphone collects no personal data and has no analytics, ads or accounts. Traffic between the phone and the PC stays on your local network or USB cable. On first USB use the server may download Android platform-tools from Google. Links inside the app (support, Telegram, email) open only when you tap them.

 

### License

Joyphone is proprietary freeware – see [LICENSE](LICENSE). Third-party components are listed in [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt).

### Support and contact

Made by **Khwarizmiyat**, an independent company.
[Support us on Patreon](https://www.patreon.com/cw/Khwarizmiyat) · stay in touch and contact us on [Telegram](https://t.me/Khwarizmiyat) · contact us on [Email](mailto:mmcg2027@gmail.com)

</div>
