# Discord Buton & Modal Botu

Bu proje, **discord.py** kullanılarak geliştirilmiş; **buton**, **modal (form)** ve **komut** etkileşimlerini gösteren basit bir Discord botudur.

## Özellikler

* `!test` komutu ile **butonlu mesaj** gönderir
* Butona tıklanınca:

  * Kullanıcıya **DM** gönderir
  * Kanala bilgilendirme mesajı atar
  * **Modal (form)** açar
* Modal içinde:

  * Kısa metin
  * Uzun metin (paragraf)
* Form gönderilince:

  * Girilen bilgiler **mesaj içeriğine yazılır**
* Buton tıklandıktan sonra **griye döner**

## Gereksinimler

* Python 3.9+
* discord.py (2.x)

## Kurulum

```bash
pip install -U discord.py
```

## Kullanım

1. Dosyadaki `bot.run('TOKEN')` kısmına **kendi bot tokenınızı** yazın.
2. Botu çalıştırın:

```bash
python bot.py
```

3. Discord sunucusunda:

```text
!test
```

komutunu kullanın ve butona tıklayın.

## Dosya Yapısı

* `bot.py` → Botun tüm kodları (komut, buton, modal)

## Güvenlik Uyarısı

❗ **Bot tokenınızı asla herkese açık paylaşmayın.**
Token sızdıysa Discord Developer Portal üzerinden **yenileyin**.

## Amaç

Bu proje, Discord botlarında **UI bileşenleri (Button & Modal)** kullanımını öğrenmek ve örneklemek amacıyla hazırlanmıştır.

---


