# پروژه امید

ما در پروژه امید خواهان فراهم آوردن اینترنت آزاد برای همه ایران هستیم. اینجا محفلی است برای به اشتراک گذاری تکنولوژی‌هایی که برای عبور از فیلترینگ حاکمیت ایران موثر هستند. هویت ما هیچگاه مشخص نخواهد شد و تا روز آزادی تلاش‌مان را برای گسترش اینترنت آزاد در ایران ادامه خواهیم داد. 

# اگر عجله دارید

در قسمت‌های بعدی توضیحات به نسبت کاملی در مورد تکنولوژی فیلترینگ در ایران ارائه شده است اما اگه عجله دارید خلاصه‌اش می‌شود اینکه جمهوری اسلامی سیستم فیلترینگ چینی GFW را استفاده می‌کند. در مقابل، ما هم در ایران از روش‌هایی که گروه‌های مقاومت چینی ابداع کرده‌اند بهره می‌گیریم تا سیستم فیلترینگ را دور بزنیم. به لینک‌های زیر رجوع کنید تا نحوه نصب و راه‌اندازی تکنولوژی های عبور از فیلترینگ را بیاموزید.

*  گام اول [نصب Xray](https://github.com/iranxray/hope/blob/main/install-xui.md) بر روی یک سیستم لینوکسی است.
* گام دوم، [راه اندازی Trojan](https://github.com/iranxray/hope/blob/main/create-trojan.md) و یا [راه اندازی VLESS](https://github.com/iranxray/hope/blob/main/create-vless.md) می‌باشد.
* [نصب کلاینت بر روی اندروید]() گام سوم استفاده با
* [نصب کلاینت بر روی آیفون]()
* [نصب کلاینت بر روی ویندوز]()


# دیواره آتش فیلترینگ
سامانه فیلترینگی که در ایران استفاده می‌شود، در واقع یک سیستم چینی است موسوم به [Great Firewall یا GFW](https://en.wikipedia.org/wiki/Great_Firewall). نام این هیولا، اشاره به دیوار باستانی چین دارد که بر دور کشور کشیده شد تا از دشمنانش مصون بماند. این سامانه در سال ۱۹۹۸ کلید ‌می‌خورد و ساخت فاز اولیه تا سال ۲۰۰۶ به طول می‌انجامد. به لطف سرمایه‌گذاری عظیم حزب کمونیست چین، سامانه GFW هر سال به روش‌های پیچیده‌تری برای فیلترینگ هوشمند تجهیز می‌شود و می‌تواند با جزییات بسیار بالا ترافیک عظیم جمعیت چند میلیادری چین را در لحظه مانیتور کرده، ترافیک مشکوک را ببندد و یا به مقامات به صورت خودکار گزارش ارسال کند. این دیواره آتش در واقع اژدهای هفت‌سری است که در دروازه‌های اینرنت ما هم ایستاده و از چرخش آزاد داده‌ها جلوگیری می‌کند. 

اما هر جا سیاهی باشد، جنگجویان روشنایی هم خواهند بود. داستان الهام‌بخش و البته کمترشنیده برای ما ایرانی‌ها این هست که متخصصان امنیت در تمام این سال‌ها در حال نبردی پیدا و پنهان با حزب کمونیست چین بوده‌اند. آن ها با ابداع روش‌های نوین در دور زدن GFW همواره توانسته‌اند دروازه‌های جهان آزاد را به روی مردم چین باز نگه دارند. هر بار حزب کمونیست سعی می‌کند با تقویت الگوریتم‌های GFW روش‌های ابداعی گروه مقاومت را بی‌اثر کند اما هر بار گروه مقاومت با روشی جدیدتر باز‌ می‌گردد. دانستن این نکات برای شهروند ایرانی از آن جهت حائز اهمیت هست که ما می‌توانیم از تمام این گنجینه‌ای که توسط متخصصان چینی و غربی برای فریب GFW فراهم شده استفاده کنیم تا دسترسی به اینترنت آزاد را برای مردم ایران به ارمغان بیاوریم.

شاید گفتن این نکته خالی از لطف نباشد که فیلترشکن‌هایی که در سال‌های گذشته در ایران رواج داشتند، مثل Freegate، Lantern، Ultrasurf و Psiphon همگی برنامه‌هایی بودند که توسط متخصصان برای عبور از دیواره آتش چینی طراحی شده بودند و برای همین هم در دور زدن سامانه فیلترینگ جمهوری اسلامی موثر عمل می‌کردند. حتی خیلی از این نرم‌افزار‌ها به طور پیشفرض از الفبای چینی استفاده می‌کردند، چون اساسا برای مخاطب چینی پیاده‌سازی شده بودند. اما به هر روی، همین نرم‌افزار‌ها در سال ۸۸ و پس از آن از ابزارهای اصلی مردم ایران برای دور زدن فیلترینگ جمهوری اسلامی بوده اند.

نحوه کارکرد GFW به طور دقیق مشخص نیست. مقاله‌های آکادمیک متعددی سعی کرده‌اند تا با آزمایش‌های متعدد از درون شبکه داخلی چین بتوانند از روی بروز رفتار بیرونی GFW به جزییات درونی سیستم آگاهی پیدا بکنند. از خلال این آزمایش‌ها، درک عظیمی نسبت به کارکرد این هیولا به دست آمده و منجر به تولد روش‌های موثر عبور از فیلترینگ هم شده. اما در این بازی موش و گربه، همواره GFW هم تلاش کرده تا با پیچیده‌تر کردن مکانیزم‌های فیلترینگ روش‌های دور زدن را یکی بعد از دیگری ابطال کند. برای همین، روشی که سال‌ها پیش موثر بوده، دیگر کارا نیست. روشی هم که امروز موثر هست، احتمالا فردا بسته خواهد شد. چیزی که به ما امید می‌دهد این هست که با همه دشواری‌ها در این تعقیب و گریز، بهترین و [فداکارترین متخصصان](https://gfw.report/) هر بار راهی پیدا خواهند کرد تا یک قدم جلوتر از سرکوب‌گران آزادی قرار بگیرند و مجراهای اطلاعاتی هیچ‌گاه به طور کامل بسته نخواهد بود. مقالات زیر درک دقیق‌تری از نحوه کارکرد GFW به ما می‌دهند.

* [تحلیل عمقی از ساختار GFW، تهیه شده در سال ۲۰۱۶](https://www.cs.tufts.edu/comp/116/archive/fall2016/ctang.pdf)
* [کشف گروه تحقیقی دانشگاه Maryland در مورد چگونگی فیلتر کردن ترافیک HTTPS](https://therecord.media/academics-discover-hidden-layer-in-chinas-great-firewall/)
* [مقاله تحقیقی دانشگاه تورنتو در مورد تغییرات شبکه GFW](https://therecord.media/academics-discover-hidden-layer-in-chinas-great-firewall/)
* [تحقیقی که مشخص می‌کند GFW ترافیک TSL 1.3 را بدون استثنا فیلتر می‌کند](https://gfw.report/blog/gfw_esni_blocking/en/)

## مکانیزم فیلترینگ در GFW

مهم‌ترین ابزارهای فیلترینگ در GFW به شرح زیر هستند.

* حمله DNS Spoofing
* بستن IP
* ‌بررسی حضور کلیدواژه‌های حساس
* [تکنیک Deep Packet Inspection](https://en.wikipedia.org/wiki/Deep_packet_inspection): این روز‌ها قسمتی اعظمی از ترافیک اینترنت بر روی پروتکل ایمن HTTPS منتقل می‌شود. مزیت این پروتکل این می‌باشد که تمامی داده‌های ارسالی و دریافتی کاربر را رمز می‌کند. در نتیجه، دیگر GFW قادر به مشاهده محتویات داده‌های کاربر نیست. مثلا، به علت اینکه اپلیکیشن Twitter تماما از HTTPS‌ استفاده می کند، GFW هیچ راهی نخواهد داشت که بفهمد شما بر روی این پلتفرم چه فعالیتی انجام می‌دهید. دقیقا همینجاست که تکنیک Deep Packet Inspection به کمک GFW می‌آید. این تکنیک پیشرفته به GFW این امکان را می‌دهد که با استفاده از الگوهای مدرن Machine Learning داده‌های رمزنگاری شده را اسکن کند تا به یک تحلیل کلی راجع به داده کاربر دست پیدا کند. اگر خروجی این تحلیل این باشد که این داده غیرمجاز است، آنگاه از انتقال داده جلوگیری می‌شود. تاکید می‌کنیم، که این روش راهی برای پی بردن به داده کاربر نیست. فقط براساس حدس‌هایی می‌تواند داده را به مجاز و غیرمجاز تقسیم می‌کند.



# مکانیزم‌های دور زدن GFW
در این قسمت روش‌هایی را که برای عبور از دیواره آتش GFW وجود دارد به طور خلاصه مرور می ‌کنیم. پیش از بررسی، روش‌های مختلف لازم هست این نکته را ذکر کنیم که پروتکل‌های VPN به آسانی توسط GFW شناسایی می‌شوند. پروتکل‌هایی که ما در ادامه تشریح خواهیم کرد، از نظر علمی و فنی VPN نمی‌باشند، هر چند که همه روش‌های عبور از فیلترینگ در عامه به عنوان VPN شناخته می شود.

البته بر روی اینترنت [گزارش‌هایی](https://therecord.media/academics-discover-hidden-layer-in-chinas-great-firewall/) هست که برخی VPN های تجاری مانند ExpressVPN به خوبی در چین کار می‌کنند. دلیل این امر چندان مشخص نیست. در ایران هم ExpressVPN از معدود روش‌های تجاری است که می‌توانید استفاده کنید.

همه روش هایی که در زیر توضیح داده می‌شوند از یک ایده کلی پیروی می‌کنند. در همه این‌ها راه حل مبتنی بر این ایده پیاده سازی شده که بتواند مکانیزم Deep Packet Inspection تعبیه شده در GFW را فریب بدهد. به طور دقیق‌تر، روش‌های ذیل با تغییر ظاهر داده‌های کاربر سعی می‌کنند به GFW تلقین کنند که داده کاربر مجاز می‌باشد. شبیه این که اگر پلیس دنبال شخصی باشد، شما شاید با گریم و تغییر ظاهر مطنون بتوانید پلیس را فریب دهید. این روش‌ها بر این فرض استوار شده‌اند که GFW فقط وقتی مانع از خروج داده می‌شود که با درصد بسیار بالایی نسبت به غیرمجاز بودن آن اطمینان داشته باشد. از آنجایی که روش Deep Packet Inspection مبتنی بر حدس و گمان می‌باشد، قطع داده‌ها بدون اطمینان بسیار بالا می‌تواند منجر به قطع کلی ارتباط با خارج شود. این هزینه بسیار هنگفتی را به کشور وارد می‌کند و حزب کمونیست چین مایل به قرار گرفتن در این سناریو نیست.


## پروتکل Shadowsocks (غیر ایمن :skull:)
این پروژه در سال ۲۰۱۲ شروع به کار کرد تا یکی از اولین پروتکل‌هایی باشد که در چین برای بالا پریدن از دیوار GFW طراحی می‌شود. علی‌رغم موفقیت بالا، برنامه‌نویس ناشناس این پروژه با شناسه clowwindy به دلایل نامعلومی مجبور شد که این پروژه را متوقف کند. امروز استفاده از Shadaowsocks به هیچ عنوان توصیه نمی‌شود، چون GFW به حدی توانمند شده که ترافیک این پروکسی دیگر از چشم‌هایش پنهان نماند. این امر می‌تواند خطر امنیتی برای مصرف‌کننده به همراه داشته باشد. نسل دوم این پروژه به نام ShadowsocksR تعدادی از مشکلات امنیتی نسل اول را برطرف کرده ولی حتی با این حال استفاده از آن توصیه نمی‌شود. از مزایای مهم Shadowsocks این می‌باشد که می‌تواند بر روی هر دو بستر انتقال TCP و UDP کار کند.


## پلتفرم V2Ray
در سال ۲۰۱۵ این [پروژه‌](https://github.com/v2fly/v2ray-core) توسط گروه ناشناس Project V معرفی می‌شود تا جایگزینی برای Shadowsocks باشد. برخلاف Shadowsocks، این پروژه صرفا یک پروتکل برای دور زدن GFW نیست بلکه یک پلتفرم است. پلتفرم بودن به این معنا است که این پروژه محدود به یک پروتکل مشخص نیست بلکه این امکان را فراهم می‌آورد که پروتکل‌های مختلف به صورت plug and play به سیستم اضافه بشوند. این پروژه با این ذهنیت متولد شد که دیر یا زود GFW در شکار هر پروتکلی موفق خواهد شد، پس ما باید پلتفرمی طراحی کنیم که این امکان را فراهم کند تا متخصصین بتوانند به آسانی پروتکل‌های جدید‌شان را به پلتفرم V2Ray اضافه کنند. این چابکی به V2Ray اجازه می‌داد تا به سرعت تغییرات جدید را در اختیار همگان قرار بگذارد.

با استفاده از این پلتفرم می‌توانیم پروتکل‌هایی نظیر SOCKS4، SOCKS5، ShadowSocks، پروکسی تلگرام MTProto و VMESS را برای کاربران بسازیم.


### پروتکل VMESS (غیر ایمن :skull:)
این پروتکل در سال ۲۰۱۵ توسط گروه Project V طراحی شد تا به عنوان جایگزین Shadowsocks در پلتفرم V2Ray مورد استفاده قرار بگیرد. گاهی V2Ray و VMESS به جای یکدیگر در متون استفاده می‌شوند اما لازم است تاکید کنیم که این اشتباهی مصطلح هست. یکی پلتفرم هست و دیگری پروتکل. در زمان تولد، VMESS قادر بود تا با تغییر محتویات بسته‌های داده از اسکن Deep Packet Inspection که توسط GFW انجام می‌گرفت فرار کند. اما این پروتکل از سال ۲۰۲۰ به این سو دیگر [امن در نظر گرفته نمی‌شود](https://github.com/net4people/bbs/issues/36#issuecomment-644929739) و ترافیک آن توسط GFW قابل شناسایی است. در [مقاله‌ای ضعف‌های امنیتی VMESS](
https://gfw.report/blog/v2ray_weaknesses/en/) به تشریح آورده شده اند. 


:star:
به هر روی، ویژگی‌های جالب این پروتکل به شرح زیر می‌باشد.

۱. رمزنگاری یا Encryption: پروتکل VMESS از یک روش رمزنگاری استفاده می‌کند تا داده‌ها را از GFW پنهان نگه دارد.

۲. در این پروتکل، کاربران نیازی به استفاده از پسورد ندارند تا بتوانند به server‌ متصل شوند. در VMESS به هر کاربر یک شناسه کاربری داده می‌شود که همان و فقط همان برای اتصال به server کافی است.

۳. پروتکل VMESS الزام می‌کند که زمان سیستم کاربر و server بیشتر از ۹۰ ثانیه اختلاف نداشته باشند. اگر اختلاف زمانی در محدوده مجاز نباشد، آنگاه پروتکل تمام درخواست‌های کاربر را قطع خواهد کرد. این پروتکل، از زمان برای رمزنگاری داده‌ها استفاده می‌کند.

۴. پروتکل VMESS برای نقل و انتقال داده از لایه TCP استفاده می‌کند. ترافیکی که به UDP نیاز داشته باشد با تکنیک UDP over TCP منتقل خواهد شد. این موضوع یکی از تفاوت‌ها با Shadowsocks می‌باشد که قادر بود بر روی هر دو بستر TCP و UDP داده‌ها را منتقل کند.


## پلتفرم Xray
در نوامبر ۲۰۲۰، گروهی ناشناس به نام Project X پروژه V2Ray را fork می‌کنند تا با رفع یک سری کاستی‌ها نسخه‌ خودشان به نام [پروژه Xray](https://github.com/XTLS/Xray-core) را عرضه کنند. در واقع، پلتفرم Xray superset پلتفرم V2Ray می‌باشد که با داشتن همه خوبی‌های آن و رفع نواقصش تبدیل به پلتفرم غالب شده است. از نقاط قوت این پلتفرم جدید می توان این را گفت که Xray تا ۳۰ درصد کارایی بهتری نسبت به V2Ray دارد. همچنین، با ابداع پروتکلی جایگزین برای TLS‌ به نام XTLS این اجازه را می‌دهد تا داده‌های کاربران از امنیت بالاتری برخوردار باشند. برای دیدن اینکه چه پروتکل‌هایی بر روی پلتفرم Xray قابلیت تنظیم دارند، [به اینجا رجوع کنید](
https://github.com/XTLS/Xray-examples).

### پروتکل VLESS (ایمن :sunglasses:)
در همان نوامبر ۲۰۲۰، گروه ناشناس Project X، پروتکل VLESS را به عنوان جایگزینی برای پروتکل VMESS طراحی کرد. این پروتکل هیچ کدام از معایت امنیتی VMESS را ندارد و هنوز GFW قادر به شناسایی داده‌های رمزنگاری شده با VLESS‌ نیست. بعلاوه، VLESS به گونه‌ای بسیار کاراتر طراحی شده و به server اجازه می‌دهد تا به نسبت VMESS تعداد کاربران بیشتری را بر روی یک server میزبانی کند. دقت کنید که به عنوان یه اشتباه مصطلح گاهی در متون Xray و VLESS به جای یکدیگر استفاده می‌شوند بااینکه یکی پلتفرم هست و دیگری پروتکل.

در این لحظه پروتکل VLESS به همراه XTLS و بر روی TCP یکی از روش‌های کارا برای دور زدن GFW در ایران می‌باشد. می‌توانید به [مقاله ما برای راه‌اندازی VLESS](https://github.com/iranxray/hope/blob/main/create-configs.md) امن رجوع کنید.

:star:
برخلاف VMESS، در این پروتکل رمزنگاری بر روی داده انجام نمی‌شود. پس حتما برای آنکه از امنیت کاربران‌تان مطمئن شوید باید ترافیک VLESS را بر روی بستر XTLS‌ عبور دهید.


:star:
یک نکته جالب دیگر در مورد VLESS، وجود این نکته هست که می‌توانید آن را بر روی پورت 443 میزبانی کنید. این به شما اجازه می‌دهد که برای پنهان سازی بیشتر از GFW یک وب سایت عادی بر روی پورت 443 بالا بیاورید. وقتی کاربر با مرورگر به آدرس شما می‌رود، یک وب‌سایت مجاز می‌بیند. اما در پشت پرده، کاربران می‌توانند از این پورت به عنوان دری پنهان استفاده کنند. [این تکنیک در این مقاله](https://henrywithu.com/coexistence-of-web-applications-and-vless-tcp-xtls/
) توضیح داده شده است.

:star:
 لینک‌های مفید:

* [وب سایت Project X](https://xtls.github.io/)
* [توضیحات فنی برای تنظیمات Xray](https://xtls.github.io/config/)


### پروتکل Trojan (ایمن :sunglasses:)
در ۲۰۱۷، [پروتکل Trojan](https://github.com/trojan-gfw/trojan) توسعه داده شد و تا امروز هم در کنار VLESS روش بسیار موثر دیگری برای دور زدن GFW می‌باشد. پروتکل Trojan ترافیک داده عبوری را به شکل ترافیک HTTPS مچاز درمیاورد تا مکانیزم Deep Packet Inspection در GFW داده را به عنوان ترافیک مجاز در نظر بگیرد. مطابق بر این پروتکل، در آغاز TLS Handshake به صورت کامل انجام می‌گیرد تا GFW تصور کند که ترافیک عبور HTTPS‌ مجاز می‌باشد. به طور خلاصه، عملکرد یک Trojan Server از نظر ناظر بیرونی کاملا شبیه به یک Web Server عادی به نظر می‌رسد و همین کمک می‌کند که GFW به Server شما مشکوک نشود. این پروتکل هر دو لایه انتقال TCP و UDP رو پشتیبانی می‌کند. می‌توانید به [مقاله ما برای راه‌اندازه Trojan](https://github.com/iranxray/hope/blob/main/create-trojan.md) رجوع کنید. 

:star:
لینک‌های مفید:
* [پروژه Trojan در GitHub](https://github.com/trojan-gfw/trojan)
* [نخستین Issue بر روی GitHub پروژه که دلایل تولد Trojan را توضیح می‌دهد](https://github.com/trojan-gfw/trojan/issues/14)
* [تشریح پروتکل](https://trojan-gfw.github.io/trojan/protocol.html)

:star:
[پروژه‌ دیگری به نام Trojan-Go](https://github.com/p4gefau1t/trojan-go
) بر پایه پروژه Trojan و با زبان GO نوشته شده است. این پروژه نسبت به نسخه اولیه امکاناتی نظیر پشتیبانی از WebSocket و استفاده از CDN را هم اضافه کرده است.


