# touch

`touch` metin dosyanı oluşturmanın en kolay yollarından biridir. Örnek olarak `touch kaan` komutu ile kaan adında bir dosya oluşturlarım.

![touch](https://github.com/kaaneeksi/Linux-Komutlari/blob/main/G%C3%B6rseller/Linux-komut-touch.png)

İstersek `touch <dosya-ismi>.txt` ile  .txt uzantılı isimde verebiliriz.

![touch](https://github.com/kaaneeksi/Linux-Komutlari/blob/main/G%C3%B6rseller/Linux-komut-touch-txt.png)

# cat

`cat <dosya-ismi>` ile bir dosyanın içini terminal ekranında okuyabiliriz, `cat > <dosya-ismi>` komutu ile de içine yazı yazabiliriz. Yazımızı yazdıktan sonra `CTRL + D ` tuşlarına basarak yazımızı kayıt edebiliriz.

![cat](https://github.com/kaaneeksi/Linux-Komutlari/blob/main/G%C3%B6rseller/Linux-komut-cat.png)

İçinde yazı olan bir dosyaya ek olarak yazı eklemek istiyorsak, yani içinde hali hazırda olan yazıların silinmemesini istiyorsak bunu

`cat >> <dosya-adı>` komutu ile yapabiliriz.

![cat](https://github.com/kaaneeksi/Linux-Komutlari/blob/main/G%C3%B6rseller/Linux-komut-cat-2.png)

Eğer **">>" yerine ">"** ile dosyanın içine yazı yazarsak kayıt edilmiş verileri sileriz.

![cat](https://github.com/kaaneeksi/Linux-Komutlari/blob/main/G%C3%B6rseller/Linux-komut-cat-3.png)

# echo
Bu komutun bir kaç farklı kullanım alanı vardır.

`echo` komutu yazılan bir ifadenin ekrana terminal üzerinden çıktısını verir.

![echo](https://github.com/kaaneeksi/Linux-Komutlari/blob/main/G%C3%B6rseller/Linux-komut-echo.png)

`echo "<yazılacak-ifade>"  >  <içine-yazdığımız-dosya>` komutu ilede bir doysanın içini açmadan uzaktan içine yazı eklememize yarar.

![echo](https://github.com/kaaneeksi/Linux-Komutlari/blob/main/G%C3%B6rseller/Linux-komut-echo-2.png)

`echo *` ile `ls` komutunda yaptığmız gibi içinde bulunduğumuz konumun içindeki dosyaları bize gösterir 

Eğer `echo k*` gibi bir komut yazarsak bize k harfi ile başlayan dosyları göstericekdir `echo t* ` yazarsakta t ile başlayan dosyaları gösterir.

![echo](https://github.com/kaaneeksi/Linux-Komutlari/blob/main/G%C3%B6rseller/Linux-komut-echo-3.png)

# grep 

`grep <parametre> <aranacak-kelime> <dosya-adı>` komutu **metin dosylarının** içerisinde arama yapmaya yarayan bir koddur.

![echo](https://github.com/kaaneeksi/Linux-Komutlari/blob/main/G%C3%B6rseller/Linux-komut-grep.png)

`grep -i`  grep komutunun küçük-büyük harf duyarlılığı vardır. Eğer bunu istemiyorsak bu parametreyi kullanabiliriz.

![echo](https://github.com/kaaneeksi/Linux-Komutlari/blob/main/G%C3%B6rseller/Linux-komut-grep-i.png)

`grep -v <istenmeyen-harf>` -a parametresi ile istemediğimiz harfi barıncıran kelimeleri listelemez.

![echo](https://github.com/kaaneeksi/Linux-Komutlari/blob/main/G%C3%B6rseller/Linux-komut-grep-v.png)

`grep -n` -n parametresi ile istenilen kelimeler satır numarası ile yazılır.

![echo](https://github.com/kaaneeksi/Linux-Komutlari/blob/main/G%C3%B6rseller/Linux-komut-grep-n.png)

# find

Zaman zaman adının yalnızca bir kısmını bildiğimiz ama bulunduğu dizini bir türlü hatırlayamadığımız dosyalar ve dizinler olur. Bu dosyaları bulmak için `find` komutunu kullanırız.

`find <dosya-yolu> -name <arancak-ifade>` şeklinde kullanılır. 

![find](https://github.com/kaaneeksi/Linux-Komutlari/blob/main/G%C3%B6rseller/Linux-komut-find.png)









