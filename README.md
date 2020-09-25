  ## Yaızm haatsı vaesa kusura bakmaıyn
  1. Yazılım Gereksinimleri:

     * [Visual Studio Code](https://code.visualstudio.com/download) (Kesinlikle gerekli)
  
     * [Git](https://git-scm.com/download/win) (Önemli)
     
     * [Github Desktop](https://desktop.github.com/) (Yaani ama kurun ya iyidir)

     * [Anaconda](https://www.anaconda.com/products/individual) (Şu an için değil ama yazılım için gerekli)

     * [Kite](https://www.anaconda.com/products/individual) (Zorunlu değil ama şu ana kadar insanlığın geliştirdiği en mükemmel alet)
  
  2. Mekanik Gereksinimleri:

     * [Utorrent](https://www.utorrent.com/intl/tr/downloads/win) (Tüm crack uygulamalrını indirmek için gerekli)
  
     * [SolidWorks](https://kickasstorrents.to/solidworks-2020-sp4-0-full-premium-crackzsoft-t4576205.html) (Crack)
  
  3. Tasarım (PR) Gereksinimleri:

     * [Adobe Photoshop](https://kickasstorrents.to/adobe-photoshop-cc-2015-20150529-r-88-32-64bit-crack-t1191072.html) (Crack)

     * [Adobe Illustrator](https://kickasstorrents.to/adobe-illustrator-cc-2015-19-0-0-64-bit-crack-t1191633.html) (Crack)


Crack uygulamaları indirmek için önce [Utorrent](https://www.utorrent.com/intl/tr/downloads/win)'i kurun. Daha sonra açılan siteden mıknatıs tuşuna basarak utorrent ile aç demeniz gerekmektedir. Utorrent indirmeyi yapacaktır

#### Crack uygulamaları kurmak yeni başlamışlar için biraz zor olabilir ama cidden hepsini anlatacak vaktim yok ve tecrübe iyidir.

# Visual Studio Python ve Extension kurulumları

#### Visual Studio Code'un kullanımını ve arayüzünü detaylı olarak eğitimlerde anlatacağım
Kurulumların yapılması internet hızına bağlı olabileceği için önceden yapılmasını istiyorum.

Öncelikle sol tarafta bulunan `Extensions` menüsünü açarak kurulumumuza başlayalım.

![Extensions Menu](https://i.ibb.co/qCtrfgm/step-1.png)

Açılan sayfadan `python` kelimesini aratarak gösterilen eklentileri kuralım (hepsini açıklamamış olabilirim resime güvenin)

![Python Extensions](https://i.ibb.co/Fb83c54/step-2.png)

Ben kurulumları daha önceden yaptığım için ekran biraz farklı görünebilir sizde install yazmalı. Fotoğraftaki eklentileri kurduktan sonra aşağıda verdiğim eklentileri tek tek aratıp kurmanız gerekiyor. (Biliyorum sıkıcı özür dilerim)

### Extensionlar

1. Pyhton için gerekli olanlar:
    
    * `Pyhton` (Python dilinde kod yazmanızı sağlayacak eklenti)
    * `Kite Autocompleter` (Kod yazarken sizin kod yazma tarzınızdan öğrenip öneriler sunan yardımcı, ek kurulum gerekli)
    * `Python Extension Pack`
    * `Python Test Explorer` (Pythonda yazdığınız testleri çalıştırmanızı sağlaycak, eğitimlerde anlatacğım)
    * `Python Docstring Generator` (Kodlarınızı açıklamanızı kolaylaştıran bir ekleti)
    * `Pylance` (Hata vs gösteriyor gibi bir şey)
    * `Path Intellisens` (Dosya yollarını otomatik tamamlama)

2. Kullandığımız Temalar:
    
    * `Bracket Pair Colorizer 2` (Parantezlerin karşılıklarını renklendiriyor AŞŞIRI ÖNEMLİ)
    * `Material Icon Theme` (İkon teması, çok öneririm)
    * `Shades of Purple` (Güzel mor-mavi arası bir tema, 2019 FRC'de kullanmıştık)
    * `Amethyst Themes` (Yine güzel tema ama kullanmadık)

4. Source Control (git):

    * `Gitlens`
    * `Git Project Manager`
    * `Git History`

4. Live Share:

    * `Live Share` (Uzaktan başkalarıyla kod yazmanızı sağlıyor)
    * `Live Share Extension Pack` (Live share eklentisine ses filan ekliyor)

Source Control olayı çok ayrı ona eğitimlerde gireceğim.

## Şimdi sıra projeler için bir klasör oluşturmakta

Projeleri kaydedeceğiniz yeni bir klasör oluşturun (Belgelerim içinde olmasını öneririm). Klasörün ismi `projects` ya da `projelerim` tarzı bir şey olabilir. Daha sonra bu klasörün içinde `helloWorld` adlı başka bir klasör oluşturun. Daha sonra Visual Studio Code ekranına geri dönüp; 

![File Explorer](https://i.ibb.co/XXqrNyD/Step-3.png)

Menüsüne geçin ve projelerinizin bulunduğu klasörü açmak için, <kbd>Open Folder</kbd> tuşuna basın, çıkan ekrandan projelerinizi kaydettiğiniz klasörü seçin;

![Open Folder](https://i.ibb.co/V3TXMkD/step-4.png)
![Select Folder](https://i.ibb.co/FVfwYS8/step-5.png)

Klasörü seçtikten sonra klasör içinde yeni bir dosya oluşturmak için;

![New File](https://i.ibb.co/HD695Yt/step-6.png)

tuşuna tıklayın.

![File Naming](https://i.ibb.co/pXDMbr2/step-7.png)

Daha sonra dosyanıza isim verin, `helloWorld.py` tarzı bir isim kullanabilirsiniz. Burada önemli olan nokta dosyaya verdiğiniz ismin uzantısının `.py` olması, uzantısını bu şekilde yaptığınzda VS Code, bu dosyanın bir python dosyası olduğunu anlıyor

![Bunu da okumazsın](https://i.ibb.co/bQLxHhW/step-8.png)

Dosya ismini yazıp Enter tuşuna tıkladıktan sonra ekranın sağ tarafından açılan yer kodları yazmanızı sağlayacak yer, python'ın çalışıp çalışmayacağını test etmek için,
```python
print("Hello World!", "Tuna abi", sep="\n")
```
kodunu dosya içine girin ve <kbd>Ctrl</kbd> + <kbd>F5</kbd> tuşlarına basın. Altta çıkan terminalde yazdırmaya çalıştığınız şey çıktıysa kurulum problemsiz tamamlandı demektir.

## Ee çalışmadı bu 
Python extensionlarının kurulum esnasında yüklenmesi biraz zaman alabilir, ayrıca çoğu eklenti VS Code'u yeniden başlatmanızı gerektirir, bunu direkt olarak kapatıp açarak yapabileceğiniz gibi eklenti üzerinde yazan <kbd>Reload Required</kbd> tuşuna basarak da gerçekleştirebilirsiniz. 

#### Eğer yine çalışmazsa
Önce internete sonra bana yazın (Önce bana yazmanız daha iyi olur)


# Ama daha bitmedi
## Şimdi sırada kodumuzu düzenleyen formatter ayarlaması var
Öncelikle `formatter`lar kodunuzu sizin yerinize düzenleyen bazen gerçekten çok rahatsız edici olabilen küçük programlardır diyebiliriz. Ben, daha elastik bir yapısı olduğu için Google'ın ürettiği [yapf](https://github.com/google/yapf) formatterını kullanmayı seviyorum, (düzenlemesini istemediğiniz yerlerde `# yapf: disable` diyerek kapatabiliyorsunuz) o yüzden VS Code üzerinde de bunun kurulumunu anlatacağım

Yapmasam bir şey olur mu diye sorabilirsiniz, yapmanız size çok fazla şey katmayabilir ama yazdığınız programlar karmaşıklaşmaya başladığında cidden ne kadar önemli olduğunu anlayacaksınız.

VS Code'un ayarlarına girmek için;

![Settings](https://i.ibb.co/Q6LPy4B/formatter-1.png)

Ayarlara girdikten sonra her kaydettiğinizde dosyanızın baştan düzenlenmesini sağlamak için `Format On Save` ayarını etkinleştirin;

![Format On Save](https://i.ibb.co/LJf0fMX/formatter-2.png)

Şu anda VS Code formatter olarak yapf'ı kullanmıyor. Bunu değiştirmek için;

![Python Formatting Provider](https://i.ibb.co/8nyf6nF/formatter-3.png)

Ayarını yapf'a değiştirebiliriz

Bunu yaptıktan sonra herhangi bir `Python` dosyasında bir değişiklik yapıp <kbd>Ctrl</kbd> + <kbd>S</kbd> tuşlarına basarak kaydetmeye çalıştığınızda dosyanızı düzenlemeyi deneyecektir, fakat yapf kurulu olmadığı için sağ alt köşede `Yapf not Installed` benzeri bir uyarı çıkacaktır (Maalesef resmi yok) yes diyerek kurulumu yapmasını söyleyin ve formatterınız hazır olmalı