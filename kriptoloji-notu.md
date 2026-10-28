Kriptolojinin tarihi ve mantığı
Siber güvenliğin ve dijital gizliliğin temel taşı olan kriptoloji karmaşık yazılımlardan ibaret değildir. İnsanların bilgi skalama 
ihitiyacı çok eski bir ihtiyaçtır.

Başlangıçta kriptolojinin yunanca kryptos (gizli) ve logos (bilim/kelime) sözcükelrinin birleşiminden türemiştir.
- Julius Caesar (Sezar) Şifresi: Bilinen ilk metodlardan birisidir. Askeri mesajlarını iletirken harfleri alfabede belirli bir sayı kadar kaydırarak şifrelemiştir.
- Enigma: 2.Dünya Savaşı sırasında Alman ordusu tarafından kullanılan elektro-mekanik bir şifreleme makinesidir. Alan Turing ve ekibinin Enigma'yı kırma çabaları,modern bilgisayar bilimin doğuşunu tetiklemiştir.

Günümüzde bunlar artık kağıt-kaleme değil,yüksek işlem gücüne sahip algoritmalarla dijital dünyamızı korumaktadır.

Kriptoloji iki ana kategoriye ayırırız:

1.Simetrik Şifreleme
Mantığı veriyi şifrelemek ve şifreyi çözmek için aynı gzili anahtar kullanılır çok hızlıdır ve büyü boyutlu dosyaları şifrelemek için 
idealdir.

2. Asimetrik Şifreleme
Biri Açık Anahtar, diğeri Gizli Anahtar olmak üzere iki farklı anahtar kullanılır. Herkes açık anahtarınızla size mesaj gönderebilir,
ancak bu mesajı sadece sizin gizli anahtarınız çözebilir. 
Simetrik şifrelemeye göre matematiksel olarak daha ağır olduğu için daha yavaştır.

--

Şifreleme ve Hashleme (Özetleme) Arasındaki Fark

Kriptoloji dünyasında sıkça karıştırılan iki kavram şifreleme (encryption) ve hashlemedir (hashing).
Her ikisi de veriyi korumak için kullanılır, ancak aralarındaki en temel fark çift yönlülüktür:

# Şifreleme (İki Yönlüdür): Veriyi yetkisiz kişilerden korumak için okunamaz hale getirirsiniz, ancak doğru anahtara sahipseniz şifreyi tekrar çözerek orijinal verilere geri dönebilirsiniz.
# Hashleme / Özetleme (Tek Yönlüdür): Veriyi (örneğin bir parolayı veya dosyayı) sabit uzunlukta karmaşık bir karakter dizisine dönüştürürsünüz. 
  Hashlemenin geri dönüşü yoktur , Şifrelenmiş (hash'lenmiş) metinden asla orijinal veriye ulaşılamaz
  sistemler sadece girilen verinin hash'ini karşılaştırarak doğrulama yapar.

---

Yapmış olduğum veri-sifreleme-aracına bakarak görebilirsin.
