# How To Jump In The System ? (Sistemde Nasıl Zıplama Yapılabilir ?)

Bir makinede **Meterpreterı** bir uygulama sayesinde ele geçirdik diyelim. Kullanıcı bu uygulamayı kapatırsa bizim ele geçirdiğimiz **Meterpreterda** kapanır. Bu yüzden sistemin içinde zıplama yapmamız gerekir. Bu işleme **Migrate(göç)** diyebiliriz.

İlk olarak **"getpid"** komutu ile bizim yetkimiz olan işlemin ip adresini öğreniyoruz. **"ps"** komutu ile de çalışan işlemleri görüyoruz.
>![getpid-ps-command]()

Çalışan işlemler kısmında explorer.exe'ye zıplamak çok iyi bir seçim olacaktır. Bu yüzden **"migrate 1464"** komutunu kullanarak explorer.exe'ye zıplıyoruz. Artık bizim sisteme girdiğimiz process kill olsada biz sistemin içinde olmuş olacağız.
>![migrate-command]()