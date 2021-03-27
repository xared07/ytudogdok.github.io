---
layout: post
title:  "Websitesi için gerekli olan zımbırtılar"
date:   2020-09-07 13:05:55 +0300
image:  "https://cdn.pixabay.com/photo/2014/06/03/19/38/road-sign-361514_1280.png"
tags:   [Tutorial]
---
Bu Yazı websitesinin baştan aşağı öğretmek amacı ile yazılmıştır.

 ***

### İğrençliklere giriş...
 
#### 1-) Github

Kayıt Linki:
[GitHub kayıt linki][github-kayıt-linki]

Kayıt olduktan sonra GitHub'ın desktop app'ini indirmen gerekiyor.

[Github Desktop][github-desktop-indirme-linki]

next next next yapa yapa kurunca asıl işimiz başlıyor.

Ruby : [Ruby indirme linki][Ruby-indirme-linki]

Msys2: [msys2 indirme linki][msys2-indirme-linki]

bunların da full kurulumunu yapınca yerel kopya görüntülenebilir olacak.(ımmm sanırım.)
Son indirmemize geldik. 

 [Website Klonu][website-klonu]

sağ üstte yeşil olan indirme butonuna basıp "open with GitHub Desktop" butonuna basıp indirmek istediğiniz lokasyona indirin.
ilk bölüm bitti wp.

 ***

#### 2-) Klon

Klasörü açıp yerel linkini kopyalıyoruz.(bu benim için C:\Users\alica\Desktop\DOGDOK\galada-master)
sonra windows arama çubuğuna cmd yazıp enterlayıp komut istemini açıyoruz.

![]({{site.baseurl}}/img/cmd.png)

sonrasında ise sırasıyla şunları girip enterlıyoruz.

"ruby install"

"ruby update"

"bundler install"

"bundler update"

klon kurulumu da tamamlandı, artık erişmek için kodumuzu yazabiliriz.

"bundle exec jekyll serve --watch"

![]({{site.baseurl}}/img/cmd2.png)

"Server address: http://127.0.0.1:4000/
  Server running... press ctrl-c to stop."

böyle diyorsa artık klonunuza erişebilirsiniz demektir. well done!. gg!. wp!.

[Buraya Tıkla ve Klona Ulaş][klon]








[github-kayıt-linki]: https://github.com/join
[github-desktop-indirme-linki]: https://desktop.github.com/
[Ruby-indirme-linki]: https://github.com/oneclick/rubyinstaller2/releases/download/RubyInstaller-2.6.6-1/rubyinstaller-devkit-2.6.6-1-x64.exe
[msys2-indirme-linki]: https://repo.msys2.org/distrib/x86_64/msys2-x86_64-20200903.exe
[website-klonu]: https://github.com/xared07/ytudogdok.github.io
[klon]: http://127.0.0.1:4000/
