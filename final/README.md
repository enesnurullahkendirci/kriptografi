# kriptografi
Kriptografi dersi kodları

Kriptografi Final Ödevi
Teslim tarihi: 12 Haziran 2020
Gönderim şekli: https://github.com/nyucel/kriptografi adresine Pull Request olarak
gönderilmelidir. Yazacağınız kod öğrenci numaranız isimli bir dizinde (örneğin 050401001)
gönderilmeli ve kodun bulunduğu dosyanın adı final.py olmalıdır.
Programlama dili: Yazacağınız kodları python3 ile yazmanız gerekmektedir.
Kullanılabilecek modüller: Temel python kitaplıklarının yanında gerekli yeni fonksiyonları
kendiniz yazıp kullanabilirsiniz. pip benzeri paket yöneticileri ile ilave bir modül yüklemeden önce
mutlaka elektronik posta ile bana sorun.
Ödev:
• Girdi olarak bulunduğu dizindeki bir dosyayı alan ve çıktı olarak 32 bitlik bir özet değeri
oluşturan final isimli bir fonksiyon yazmalısınız. Bu fonksiyon bir dosya için her
çalıştırılmasında aynı değeri üretmelidir. Dosyadaki küçük bir değişiklik özet değerinde
tahmin edilemeyecek bir değişikliğe neden olmalıdır. (50 puan)
• Yazdığınız bu fonksiyonu kullanarak aşağıdaki işlemleri gerçekleştiren bir blokzincir
mekanizması kurmalısınız (50 puan):
◦ İlk blok, içinde sadece öğrenci numaranızın olduğu 001.txt isimli dosya olmalıdır.
Sıradaki herbir blok kendinden önceki bloğun özet değeri + rastgele 32 bitlik bir sayı ile
elde edilmelidir öyle ki bu bloğun özet değerinin ilk 8 biti sıfırlardan oluşsun (örneğin
00000000010110110010000011100011 bu değere sahip bir blok kabul edilebilir bir
bloktur).
◦ Programınız çalıştırılmaya başladığında bulunduğu dizinde sadece 001.txt dosyası
olmalı ve sonlanana dek 100.txt dosyasına kadar 99 dosyayı daha yukarıdaki koşula
uygun şekilde oluşturmalıdır.
◦ HASHSUM isimli bir dosyaya her blok oluşturulurken eklenen rastgele sayı ve bloğun
özet değeri birer satırda yazılmalıdır.
◦ Programın çalışma süresi en fazla 10dk olmalıdır. Bu sürede bütün dosyalar
oluşturulamamış olsa bile program zamanlanmış bir şekilde sonlanmalıdır.
