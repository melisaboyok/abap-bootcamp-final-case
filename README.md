# Uçak Kayıtları ve Uçuş Hareketleri Otomasyonu - SAP ABAP Projesi

Bu proje, SAP ABAP (Advanced Business Application Programming) dilinde geliştirilmiş bir uçak kayıtları ve uçuş hareketleri otomasyonunu içermektedir. Aşağıda, projenin gereksinimleri ve önemli kriterlerine uygun olarak nasıl kullanılacağına dair bir README dosyası önerisi bulunmaktadır.

## Proje İçeriği:

1. **Z'li Tablolar:**
   - Proje içerisinde iki adet Z'li tablo bulunmaktadır.
   - Birinci tablo, header bilgilerini, ikinci tablo ise item bilgilerini depolamaktadır.

2. **Selection Screen ve Tab Panel:**
   - Kullanıcı tarafından girilen değerlere göre veri çekim işlemi için Selection Screen tasarlanmıştır.
   - Selection Screen üzerinde Tab Panel oluşturularak, kullanıcı arayüzü geliştirilmiştir.

3. **Tablarda Key Alanları:**
   - Birinci tablo, kullanıcı tarafından belirlenen key alanları içermektedir.
   - İkinci tablo, file upload alanı ile ilgili bilgileri içermektedir.

4. **File Upload Alanı:**
   - İkinci tabda, kullanıcı tarafından seçilen Excel dosyasındaki verileri yüklemek için File Upload alanı bulunmaktadır.

5. **ALV Rapor:**
   - ALV rapor, kullanıcı tarafından girilen değerlere göre veya Excel dosyasından yüklenen verilere göre çalışmaktadır.
   - GUI Status üzerinde üç adet buton bulunmaktadır:
     - Birinci buton: ALV rapordaki verileri Z'li tablolara kaydetmek için kullanılır.
     - İkinci buton: Excel dosyasındaki verileri ALV raporunda gösterir.
     - Üçüncü buton: İkinci tabdaki file upload alanındaki dosya yolu dolu ve ALV raporda veri gösteriliyorsa, ALV rapordaki verileri Z'li tablolara kaydetmek için kullanılır.

6. **SM30 Bakım Ekranları:**
   - Her bir Z'li tablo için SM30 bakım ekranları oluşturulmuştur.
   - Bakım ekranları, ilgili Z'li tabloya erişim sağlar.

## Nasıl Kullanılır:

1. Proje dosyalarını bir SAP sistemine import edin.
2. SAP GUI üzerinden programı çalıştırın.
3. Selection Screen üzerinden gerekli parametreleri girin.
4. İlk tabdaki alanları doldurup ALV raporunu çalıştırmak için "ALV Raporu Göster" butonuna basın.
5. İkinci tabdaki Excel dosyasını yüklemek için "Excel Dosyasını Yükle" butonuna tıklayın.
6. ALV raporundaki verileri Z'li tablolara kaydetmek için "Verileri Kaydet" butonunu kullanın.

**Notlar:**
- Eğer Excel dosyası yüklenmemişse ve "Verileri Kaydet" butonuna basılırsa hata alacaksınız.
- SM30 bakım ekranları, ilgili Z'li tabloya erişim sağlamak için kullanılabilir.


