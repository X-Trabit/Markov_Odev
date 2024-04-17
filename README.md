
---

# **Olasılıksal Süreç 1. Vize**



## Proje Ekibi

- Sidar Deniz Topaloğlu 2210329107
- Emir Cahit Bulut 2210329134

## İçindekiler

- [Giriş](#giriş)
- [Veri Seti ve Ön İşleme](#veri-seti-ve-ön-i̇şleme)
- [Durum Uzayı ve Zaman Parametresi](#durum-uzayı-ve-zaman-parametresi)
- [Bir Adım Geçiş Matrisi](#bir-adım-geçiş-matrisi)
- [Geçiş Diyagramı](#geçiş-diyagramı)
- [Denge Dağılımını Bulma](#denge-dağılımını-bulma)
- [İki Adım Geçiş Matrisi](#iki-adım-geçiş-matrisi)
- [Periyodik Durumlar ve Geçiş Matrisi](#periyodik-durumlar-ve-geçiş-matrisi)
- [Yutucu Durumlar ve Geçiş Matrisi](#yutucu-durumlar-ve-geçiş-matrisi)
- [Kapalı Küme ve Geçiş Matrisi](#kapalı-küme-ve-geçiş-matrisi)
- [Markov Zinciri için Geçiş Matrisi ve İlk Olasılık Vektörü](#markov-zinciri-için-geçiş-matrisi-ve-i̇lk-olasılık-vektörü)
- [Kaynakça](#Kaynakça)

## Giriş

Yaptığımız bu ödev, Kaggle'den alınmış bir hava durumu verisetiyle ilgilenilerek Markov Zincirleri başlığı altında verilen ödevin gereksinimlerini yapmayı amaçlar

## Veri Seti ve Ön İşleme

Veri seti, 1996'dan 2017'ye kadar olan hava durumu verilerini içerir. Her günün 15:00'teki hava durumu verileri seçilmiştir. Veri setindeki boşlukları ve tarih formatını uygun bir şekilde düzeltmek için veri ön işlemleri yapılmıştır.

## Durum Uzayı ve Zaman Parametresi

- **Durum Uzayı:** Hava durumu koşullarının kümesi: Haze, Mist, Smoke, Widespread Dust, Light Rain, Clear.
- **Zaman Parametresi:** Veri setindeki satır sayısına göre belirlenir; belirli bir süre boyunca toplanan gün gün hava durumu verilerini temsil eder.

## Bir Adım Geçiş Matrisi

Hava durumu koşulları arasında bir günden diğerine olan geçiş olasılıklarının matrisi hesaplanmıştır.

## Geçiş Diyagramı

Bir adım geçiş matrisi kullanılarak, hava durumu koşulları arasındaki geçişlerin görselleştirildiği bir geçiş diyagramı çizilmiştir.

## Denge Dağılımını Bulma

Bir adım geçiş matrisinden faydalanarak denge dağılımı (steady state distribution) hesaplanmıştır.

## İki Adım Geçiş Matrisi

Bir adım geçiş matrisinin karelenmesiyle iki adım geçiş matrisi elde edilmiştir.

## Periyodik Durumlar ve Geçiş Matrisi

Markov zinciri içinde periyodik durumlar içeren geçiş olasılıkları incelenmiştir.

## Yutucu Durumlar ve Geçiş Matrisi

Yutucu durumlar içeren bir Markov zincirine ait geçiş olasılıkları incelenmiştir.

## Kapalı Küme ve Geçiş Matrisi

Kapalı küme içeren bir Markov zincirine ait olasılık diyagramı ve bir-adım geçiş matrisi analiz edilmiştir.

## Markov Zinciri için Geçiş Matrisi ve İlk Olasılık Vektörü

Durum uzayı ve bir-adım geçiş matrisi ile ilk olasılık vektörü tanımlanmış ve analiz edilmiştir.

## Kaynakça

https://www.kaggle.com/datasets/mahirkukreja/delhi-weather-data?resource=download

---
