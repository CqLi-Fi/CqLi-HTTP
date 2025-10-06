
# CqLi-HTTP
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
![PyPI - Python Version](https://img.shields.io/badge/Python-3.7%2B-blue)
![Message](https://img.shields.io/badge/CqLi-HTTPv0.1-8A2BE2)

Güçlü HTTP saldırı testleri için oluşturulan genişletilmiş bir flood aracıdır.

![Logo](https://i.ibb.co/3mGcpjNd/cqli-http.jpg)

## Özellikler

- 18 adet sürekli güncellenen fonksiyon ile geçmiş ve güncel tüm HTTP/HTTPS güvenlik açıklarını kapsamlı bir şekilde değerlendirme yeteneği.
- SSL sınamaları ve manipüle edilmiş sertifika denemelerini etkin bir şekilde tespit ve analiz etme kapasitesi.
- Standart ve sürekli güncellenen header referansları ile user-agent içeriklerinin kapsamlı analizi ve yönetimi.
- WAF ve benzeri güvenlik korumalarını algılama ve bunlardan etkin bir şekilde kaçınma yeteneği sağlayan gelişmiş refleks mekanizmaları.
- RestAPI bağlantılarına yönelik hedef odaklı ve yanıltıcı istek gönderimleriyle etkili test ve analiz yetkinlikleri.
- SQL sorgu isteklerinin karmaşık bir şekilde optimize edilerek sunucuya çözümlendirilmesi ve yüksek yoğunluklu yük testi oluşturulması.

## Başlangıç

```bash
  git clone https://github.com/CqLi-Fi/CqLi-HTTP.git
```
```bash
  pip install aiohttp beautifulsoup4 tqdm rich faker lxml execnet
```

```bash
  python CqLi-HTTP.py
```

## Kullanımı

```bash
  Hedef URL'yi girin (örn: http://test.com veya https://test.com)
```

```bash
  Eşzamanlı istek sayısını girin (50-2000) / Önerilen "1200"
```

```bash
  Test saldırısının başlamasını bekleyin.
```

## Uyarılar ⚠️

- Bu script, yalnızca test amaçlı ortamlar için tasarlanmıştır. Onay alınmamış herhangi bir sistemde kullanımı tamamen kullanıcının sorumluluğundadır.
- Bu script, test işlemlerinden en iyi sonuçları elde etmek amacıyla kapsamlı bir şekilde tasarlanmış, derlenmiş ve kodlanmıştır. Ana script ve ilgili tüm dosyalar, kontrolsüz düzenleme ve değiştirmelere karşı gizlilik koruması içermektedir.
- Bu script, yoğun kullanım veya denemeler sırasında yanlış uygulandığında ciddi zararlara yol açabilecek yüksek etki potansiyeline sahiptir.
- Bu script, herhangi bir devlet kurumuna ait sistemler üzerinde kullanıldığında, tüm yasal sorumluluk tamamen kullanıcıya aittir.

## Teşekkür 🖤

- USDT (ERC20) > 0xFc56338a5c6B28671A8962f52666F8F7eE6CBbAF
