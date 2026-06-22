
# YouTube Yorum Analizi - NLP Sınıflandırma Projesi

Bu proje, YouTube yorumlarını doğal dil işleme (NLP) yöntemleriyle analiz etmek ve yorumları anlamlarına göre sınıflandırmak amacıyla geliştirilmiştir.

Klasik duygu analizi projelerinde yorumlar genellikle sadece `olumlu`, `olumsuz` ve `nötr` olarak ayrılır. Bu projede ise daha detaylı ve ürünleştirilebilir bir yapı hedeflenmiştir. Bu nedenle yorumlar 5 farklı sınıfa ayrılmıştır:

- Olumlu
- Olumsuz
- Nötr
- Öneri / Tavsiye
- Şikayet

## Projenin Amacı

YouTube kanallarına çok sayıda yorum gelmektedir. Bu yorumların tek tek incelenmesi zaman alıcı ve maliyetlidir. Bu proje, yorumları otomatik olarak analiz ederek içerik üreticilerinin izleyici geri bildirimlerini daha hızlı anlamasını sağlar.

Amaç yalnızca yorumun olumlu ya da olumsuz olduğunu bulmak değil; aynı zamanda kullanıcının öneri mi sunduğunu, şikayet mi ettiğini veya nötr bir yorum mu yaptığını da tespit etmektir.

## Hedef Kullanıcı Kitlesi

Bu proje özellikle şu kullanıcılar için geliştirilmiştir:

- YouTube içerik üreticileri
- Sosyal medya yöneticileri
- Marka ve ürün ekipleri
- Dijital pazarlama ekipleri
- Yüksek yorum hacmine sahip kanallar

## Kullanılan Model ve Yöntem

Projede transformer tabanlı `XLM-RoBERTa` modeli kullanılmıştır.

Kullanılan temel model:

```text
cardiffnlp/twitter-xlm-roberta-base-sentiment
