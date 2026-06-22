EN 

# YouTube Comment Analysis - NLP Classification Project

This project was developed to analyze YouTube comments using Natural Language Processing (NLP) techniques and classify them based on their meanings.

In traditional sentiment analysis projects, comments are usually classified only as `positive`, `negative`, and `neutral`. In this project, a more detailed and product-oriented structure was targeted. Therefore, comments were classified into 5 different categories:

- Positive
- Negative
- Neutral
- Suggestion / Recommendation
- Complaint

## Project Purpose

YouTube channels receive a large number of comments. Manually reviewing these comments is time-consuming and costly. This project helps content creators understand audience feedback faster by automatically analyzing comments.

The goal is not only to determine whether a comment is positive or negative, but also to identify whether the user is making a suggestion, expressing a complaint, or writing a neutral comment.

## Target Users

This project was especially developed for:

- YouTube content creators
- Social media managers
- Brand and product teams
- Digital marketing teams
- Channels with high comment volume

## Model and Method

A transformer-based `XLM-RoBERTa` model was used in this project.

Base model used:

```text
cardiffnlp/twitter-xlm-roberta-base-sentiment
```

TR

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
