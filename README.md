# ADC Okuma Örneği

Bu örnek uygulama, Texas Instruments Tiva4C  mikrodenetleyici kartı üzerinde bulunan analog-dijital dönüştürücü (ADC) kullanılarak bir analog sensörden veri okuma işlemini gerçekleştirir.

## Kod Açıklaması

Bu kod bloğu aşağıdaki işlevleri gerçekleştirir:

- Mikrodenetleyici kartının ADC (analog-dijital dönüştürücü) özelliğini kullanarak, bir analog sensörden (PE3 pimine bağlı) veri okur.
- ADC dönüşümü tamamlandığında, okunan değeri konsola yazdırır.
- Örneğin işleyişi şu şekildedir:
  1. ADC dönüşümünü başlatır.
  2. Dönüşüm tamamlandığında, değeri okur ve konsola yazdırır.
  3. Belirli bir süre (1 saniye) bekler ve işlemi tekrarlar.

## Kullanılan Donanım ve Kütüphaneler

- Texas Instruments Tiva C Series TM4C1294XL mikrodenetleyici kartı
- TI-RTOS (TI Gerçek Zamanlı İşletim Sistemi)
- TI-DRIVERS Kütüphanesi
- ADC ve GPIO kütüphaneleri

