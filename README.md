# Taş, Kağıt, Makas, Kertenkele, Spock Oyunu

## Açıklama

Bu proje, klasik "Taş, Kağıt, Makas" oyununa iki ek seçenek ekleyen bir Python oyunu sunar: Kertenkele ve Spock. Oyuncuların "Taş", "Kağıt", "Makas", "Kertenkele" ve "Spock" seçeneklerinden birini seçerek karşı karşıya geldiği bu oyun, ilk iki turu kazanan oyuncunun oyunu kazandığı bir formatta tasarlanmıştır.

## Özellikler

- **Taş, Kağıt, Makas, Kertenkele, Spock:** Her seçeneğin diğer seçeneklerle olan etkileşimlerini içerir.
- **Oyun Kuralları:** Oyunun nasıl oynandığını ve her seçeneğin diğer seçeneklere karşı nasıl bir avantaj sağladığını açıklar.
- **Yardım Menüsü:** Oyunun kurallarını ve seçenekteki etkileşimleri açıkça belirtir.
- **Oyun Döngüsü:** Kullanıcı ve bilgisayarın her turda seçimini yapması, sonuçların belirlenmesi ve oyunun devam edip etmeyeceğinin kontrol edilmesini içerir.
- **Yeni Oyun Başlatma:** Oyunun sonunda kullanıcıya yeni bir oyun oynayıp oynamayacağı sorulur. Bilgisayar da bu karara göre yeni oyuna devam eder.

## Kurulum ve Çalıştırma

1. Python yüklü olduğundan emin olun. Python 3.x sürümü tavsiye edilir.
2. Bu kodu bir dosyaya yapıştırın, örneğin `tas_kagit_makas_kertenkele_spock.py`.
3. Terminal veya komut istemcisinde dosyayı çalıştırmak için şu komutu kullanın:
    ```bash
    python tas_kagit_makas_kertenkele_spock.py
    ```

## Kullanım

- Oyunun başında kurallar ve nasıl oynanacağı hakkında bilgi verilir.
- Oyuncu, bilgisayarın rastgele seçimi ile karşı karşıya gelir.
- Her turda oyuncu ve bilgisayarın seçimleri karşılaştırılır ve galip belirlenir.
- Oyuncu, oyunun sonunda toplam galibiyetlerini ve bilgisayarın galibiyetlerini görebilir.
- Yeni bir oyun oynamak isteyip istemediğiniz sorulur. Bilgisayarın yanıtına bağlı olarak yeni oyun başlatılır veya oyun sonlandırılır.

## Oyunun Kuralları

1. **Taş:** Makas ve Kertenkeleyi yener.
2. **Kağıt:** Taş ve Spock'u yener.
3. **Makas:** Kağıt ve Kertenkeleyi yener.
4. **Kertenkele:** Kağıt ve Spock'u yener.
5. **Spock:** Taş ve Makas'ı yener.

## Katkıda Bulunma

Katkıda bulunmak isterseniz, kod üzerinde değişiklik yapabilir ve pull request oluşturabilirsiniz. Herhangi bir hata raporu veya öneri için lütfen bir issue açın.


