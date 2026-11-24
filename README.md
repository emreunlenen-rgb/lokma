# Lokma

Sohbet benzeri metin girişiyle beslenme kaydı için ders prototipi.

## Kullanım
ZIP'i çıkarın ve index.html dosyasını tarayıcıda açın. Kurulum veya API anahtarı gerekmez.
Tema düğmesinden Adaçayı, Taze, Kayısı ve Limon seçeneklerini değiştirebilirsiniz.
Bir örnekle dene > Öğünü hazırla > miktarları kontrol et > Öğünü kaydet.

## Mevcut kapsam
- Türkçe metinde yumurta, beyaz ekmek ve şekersiz çay için sınırlı kural tabanlı ayrıştırma.
- Porsiyonları düzenleme, yaklaşık kalori ve makro toplamları, kayıt silme ve geri alma.
- Tema tercihi localStorage ile saklanır. Öğün ve profil bilgileri yalnızca açık sayfanın belleğindedir; yenilenince kaybolur. Sunucuya gönderilmez.
- Genel yapay zekâ sohbeti veya kişisel günlük enerji hedefi hesaplaması bağlı değildir.
- Tanınmayan yiyecekler kısmi hesap olarak belirtilir; sıfır kalori kabul edilmez.

Besin referansları: USDA FoodData Central, haşlanmış yumurta (173424) ve beyaz ekmek (174924). Yumurta 50 g/adet, ekmek 25 g/dilim varsayımı kullanıcıya gösterilir. Değerler yaklaşık olup marka ve hazırlamaya göre değişir. Tıbbi beslenme veya tedavi önerisi değildir.
