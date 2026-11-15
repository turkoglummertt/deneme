# 🐈 Kedi Hasan — Kanal Rehberi

Mahalle bakkalını 30 yıldır işleten, huysuz ama yufka yürekli turuncu kedi Hasan'ın komik günlük maceraları.
Tamamen yapay zekâ ile üretilen, 3D animasyon tarzında YouTube Shorts serisi.

---

## 1. Karakter kartı (her videoda AYNI kalmalı)

**Hasan**
- Tombul, iri, turuncu tekir (orange tabby) erkek kedi
- Burnunun ucunda küçük yuvarlak okuma gözlüğü
- Lacivert örgü yelek
- Bir patisinde kehribar tespih, önünde ince belli Türk çay bardağı
- Ahşap tezgâhın arkasında, eski bir yazar kasanın yanında oturur
- Ses: kalın, hafif hırıltılı, İstanbul esnaf ağzı. Huysuz ama içten.

**Bakkal:** "HASAN BAKKAL" yazılı küçük, sıcak, nostaljik İstanbul mahalle bakkalı. Raflarda ekmek, bisküvi, çay paketleri, tezgâhta kalın bir "VERESİYE DEFTERİ".

**Sabit sözler (kanalın imzası):**
- "Bu dükkân otuz yıldır burada evladım."
- Her videonun sonu: **"Hadi kolay gelsin."**

### Karakter komutu (her video komutunun başına aynen yapıştırın)

```
3D animated Pixar-style short film, warm cinematic lighting, vertical 9:16.
Main character: HASAN, a chubby, large orange tabby cat with a grumpy but kind face,
small round reading glasses on the tip of his nose, wearing a navy blue knitted vest,
holding amber prayer beads in one paw. He sits behind a wooden counter next to an old
cash register, a thin tulip-shaped Turkish tea glass in front of him.
Setting: a small, cozy, nostalgic Istanbul neighborhood grocery store with a sign
"HASAN BAKKAL", shelves of bread, biscuits and tea packets, a thick notebook labeled
"VERESİYE DEFTERİ" on the counter.
Hasan speaks Turkish with a deep, slightly raspy, old Istanbul shopkeeper voice.
```

> Neden 3D animasyon? Gerçekçi olmadığı açıkça belli olan animasyonlarda YouTube'un "gerçekçi sentetik içerik" etiketi zorunlu değildir, karakter de her videoda daha tutarlı çıkar. Yine de açıklamaya "yapay zekâ ile üretilmiştir" yazıyoruz.

---

## 2. Üretim akışı (video başına ~20 dk)

1. **Önce karakter görseli (bir kere):** Gemini'de (görsel üretim) yukarıdaki karakter komutunu verip Hasan'ın net bir portresini üretin. Beğendiğinizi kaydedin. Bu sizin **referans görseliniz**.
2. **Klipler:** Google Flow / Gemini Veo'da "görselden video" (ingredients / referans görsel) seçeneğiyle referans görseli ekleyin. Bölümdeki her sahne komutunu (karakter komutu + sahne komutu) ayrı ayrı üretin. Her klip ~8 saniye.
3. **Beğenmediğiniz klibi yeniden üretin.** Türkçe konuşma bazen bozuk çıkar; 2-3 deneme normaldir.
4. **CapCut:** Klipleri sırayla birleştirin → otomatik altyazı (Türkçe) ekleyin → toplam 20-35 sn.
5. **YouTube Studio:** Yükleyin → başlık/açıklama/etiketleri yapıştırın → **"Programla"** ile takvimdeki gün ve saati seçin.

**Bütçe:** Başlangıçta aylık ~0-20 $ (Gemini/Google AI Pro aboneliği veya Kling/Hailuo deneme kredileri).

---

## 3. İlk hafta yayın takvimi

| # | Bölüm | Yayın |
|---|---|---|
| 1 | Ekmek Bitti | Çarşamba 18 Kasım — 19:30 |
| 2 | Veresiye Defteri | Perşembe 19 Kasım — 12:30 |
| 3 | Telefonla Ödeme | Cuma 20 Kasım — 19:30 |
| 4 | Bozuk Yok | Cumartesi 21 Kasım — 13:00 |
| 5 | Karşıya Market Açıldı | Pazar 22 Kasım — 20:00 |
| 6 | Teyzeyle Pazarlık | Pazartesi 23 Kasım — 19:30 |
| 7 | Bir Çay İçmeden Olmaz | Salı 24 Kasım — 12:30 |

Saatler başlangıç tahminidir; 2 hafta sonra YouTube Studio → Analytics → "İzleyicilerinizin YouTube'da olduğu zamanlar" verisine göre güncelleyeceğiz.

---

## 4. Haftalık döngü

- **Hafta sonu:** 7 bölümü üret, Studio'da zamanla.
- **Haftada bir:** Studio → Analytics ekran görüntülerini (izlenme, ortalama izleme süresi, "kaydırmadan izleyenler" oranı) Claude'a at → hangi bölüm tuttu, ona benzer yeni bölümler yazılır.

Bölüm komutları: [bolumler.md](bolumler.md)
