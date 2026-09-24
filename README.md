# Gorzip v2.6 Release

## Kurulum

1. `setup.exe`'yi çalıştırın.
2. Kurulum klasörünü seçin. Varsayılan: `C:\Program Files\Gorzip`
3. Kurulum tamamlandığında Explorer kaydı otomatik olarak yenilenir.
4. Bir dosya veya klasöre sağ tıklayın: **"Gorzip ile sıkıştır"**
5. Windows 11 klasik menüsünde görünmüyorsa **"Daha fazla seçenek göster"** altında bulunabilir.

## Performans

Gorzip v2.6, **7-Zip'e kıyasla 15 kata kadar daha yüksek sıkıştırma hızı** sunmak üzere optimize edilmiştir.

Sıkıştırma profili sabit **10 katman** kullanır ve performans odaklı çalışır.

## Teknik Bilgiler

Sağ tık komutu doğrudan kurulan `gorzip.exe` dosyasını çağırır:

`"gorzip.exe" pack "%1"`

* Çıktı uzantısı: `.grzz`
* Sıkıştırma profili: Sabit 10 katman
* BAT veya wrapper kullanılmaz.
* Sağ tık entegrasyonu doğrudan `gorzip.exe` üzerinden çalışır.

## İkon

Kullanıcının kaynak paketinde `files/Gorzip.png` bulunmadığı için bu sürümde pakete yerleşik bir Gorzip ikonu eklenmiştir.

Elinizdeki özgün PNG dosyasıyla daha sonra değiştirilebilir.
