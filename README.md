# Background-Macro

MERHABA, SİZE OLABİLDİĞİNCE PROGRAMIN GİZLİ ÖZELLİKLERİNİ VE KULLANIMINI ANLATACAĞIM

# UYARI !

<p> Sakın ama sakın VALORANT - LOL gibi oyunlarda bu hileyi kullanmayın. hatta hile açıkken bu iki oyuna giriş bile yapmayın. kalıcı olarak yasaklanam ihtimaliniz var !

<p> AntiCheat olan bazı oyunlarda erişim engeli yiyor : Knight Online, Metin2

<p> Ben Macroyu Minecraft'ın online serverları için için tasarladım. Baya temiz çalışıyor.


# ARAYÜZ
![image](https://github.com/user-attachments/assets/393adb0c-aff3-437b-b29e-e1ab9b70282a)



# PROGRAM NE İŞE YARIYOR / DİĞER MACROLARDAN FARKI NEDİR?
<p> Bu macro diğer macro programlarından farklı olarak tuş ve mouse komutlarını direkt olarak hedef oyuna veya programa gönderir. Örneğin macro aktifken ön planda herhangi bir işle ilgilenmeniz arka plandaki oyuna tuş komutları gönderen macronun çalışmasına engel olmayacaktır. aynı şekilde macronun aktif olarak çalışıyor olmasıda sizin önplanda işler yapmanıza engel olmayacaktır.

# MACRO OLUŞTURMA VE KAYDETME

### ADIM 1

<p> KENDİ MACRONU YARAT butonuna tıkla

![image](https://github.com/user-attachments/assets/b7f7171b-50be-48ba-b07e-0b4682bd69ea)

### ADIM 2 (BURAYI OKU)

![image](https://github.com/user-attachments/assets/a4b00502-851b-4f91-a64e-a82b62c82793)

<p> Bu görselde mouse tıklamalarının 0 ms olmasının sebebi var
<p> Eğer mouse tıklamasının yada bir tuşun diğer tuşlar hala aktif olarak basmaya devam ediyorken baştan sona kadar basılı kalmasını istiyorsanız başlangıçtaki tuşu ve sondaki basmayı bırak kısmını 0 ms yapmanız gerek

### ADIM 3

<p> Bir macroyu kaydettiğinizde Background.exe hangi dizinde bulunuyorsa o dizine saved_macros adında json dosyası oluşturur. ve bütün macroları artık aynı json'a kaydeder.

![image](https://github.com/user-attachments/assets/4caf164d-d0c1-4155-b17c-d5b80ded059c)


### ADIM 4

<p> Boşluğa sağ tıkla ve oluşturduğunuz Json dosyasını bulup içe aktarın.

![image](https://github.com/user-attachments/assets/0f468420-65d6-4cbf-a1d3-0035df1632e1)

Aktif et : mevcut kaydedilmiş macroyu aktif eder ve kullanıma hazır hale getirir.

![image](https://github.com/user-attachments/assets/5f7a25c9-d061-42ee-b89d-09a12b426014)


# "ACİL DURUM BUTONU" NE İŞE YARAR?

![image](https://github.com/user-attachments/assets/fc5ed774-e74d-4816-ac1e-f6bc2031cb09)


<p> Bu tuş tamamen acil durum butonu gibi bir şey. Default ayarda basarsanız oyuna o tuşu komutu gönderir

<p> İsterseniz ok işaretiyle işaretlediğim kısımdan o tuşu yerine başka bir buton ekleyebilirsiniz

<p> NEDEN BÖYLE BİR BUTON EKLEDİM? : Çünkü ben Badlion Client kullanıyorum ve Client ayarlarından O tuşuna basınca /warp garden komutu uyguluyor. böylelikle tek bir tuşla başlangıca Teleport olabiliyorum


# MINECRAFT İÇİN KULLANACAKSANIZ BUNU OKUYUN !

<p> - Macronun arka planda çalışması için oyunun yüklü olduğu options.txt'den bir ayar yapmanız gerekiyor

<p> - Çünkü oyunu arka plana atarsanız Envanter yada ESC pause ekranı açılıyor. Bu ayar sayesinde oyunu arka plana attığınızda oyun ekranında Pause ekranı açılmayacak.

<p> - C:\Users\kullanıcı adınız\AppData\Roaming\.minecraft   (klasör sizde farklı bir yerde olabilir)

![image](https://github.com/user-attachments/assets/168093dd-0e38-4707-973a-af2a44c862c5)

BU İKİSİNİ "false" YAPIN

<p> - showInventoryAchievementHint:true
<p> - pauseOnLostFocus:true
