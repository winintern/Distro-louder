# ubuntu-iso-downlouder
Ubuntu 22.04.5 ISO Downloader
Консольное приложение, которое скачивает официальный ISO-образ Ubuntu 22.04.5 LTS напрямую с серверов releases.ubuntu.com.
Никакой рекламы, никаких лишних кликов, никакой эмуляции сайтов. Просто меню, прогресс-бар
Что это и зачем?
Иногда хочется понастольгировать, иногда вдохнуть жизнь в старенький ноутбук, а иногда  просто получить чистый ISO без лишнего мусора. Это приложение делает ровно это скачивает Ubuntu 22.04.5 (Jammy Jellyfish) с официального зеркала и сохраняет на ваш диск.
Куда сохраняется файл?
Образ сохраняется в папку C:\Downloads, которая создаётся автоматически в корневом каталоге диска.
Почему именно там? Потому что я так решил. Это просто, удобно и не надо гадать, куда делся файл. Как это работает?
Программа использует WinINet и не требует никаких дополнительных библиотек.
Я написал эту программу на Pascal (Free Pascal). На это ушло полдня мучений с компилятором, HTTPS и разными библиотеками. Но оно того стоило теперь можно скачать Ubuntu 22.04.5 одной кнопкой, без посещения сайта. Я буду рад, если вы скажете спасибо за мои старания хотя бы мысленно. Хех.
Я не ворую и не присваиваю себе продукт компании Canonical. Вся интеллектуальная собственность, права на дистрибутив и торговые марки принадлежат Canonical Ltd. и сообществу Ubuntu. Это приложение всего лишь альтернативный способ скачать официальный ISO-образ напрямую, сделанный чисто из любопытства и желания помочь. Никакого мошенничества или пиратства.
A tiny Windows console tool that downloads the official Ubuntu 22.04.5 LTS ISO image directly from releases.ubuntu.com. No ads, no extra clicks, no site emulation just a menu, a progress bar
Why?
Sometimes you want a clean ISO for an old laptop, or you just miss the good old days when things worked. This app fetches the image straight from the official mirror, with zero junk.
Where the file goes?
The ISO is saved into C:\Downloads, which is automatically created in the root of your drive.
Why there? Because I decided so. It's simple, predictable, and you won't lose your file.
Important note
I do not steal or misappropriate Canonical's product. All intellectual property, distribution rights, and trademarks belong to Canonical Ltd. and the Ubuntu community. This application is merely an alternative way to download the official ISO image directly, made purely out of curiosity. No fraud or piracy involved.
How it works?
It uses WinINet
I wrote this tool in Pascal (Free Pascal). It took me half a day of fighting the compiler, HTTPS, and various DLLs. But it was worth it: now you can download Ubuntu 22.04.5 with one click. I'd really appreciate it if you said thanks for my effort even if just in your head. Heh.
