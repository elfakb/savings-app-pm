# Savings App — Ürün Keşfi ve UX Araştırması Vaka Analizi

🇬🇧 [Click here for the English version](README.md)

![Genel Bakış](assets/ui/figma/figma-overview-all-screens.png)

## Proje Hakkında

Bu, portföy amacıyla hazırlanmış, uçtan uca bir ürün keşfi ve UX
araştırması sürecini simüle eden bireysel bir projedir: ham kullanıcı
içgörüsünden test edilmiş, iterasyona uğramış bir ürün konseptine kadar.

**Not:** Bu, pratik amaçlı simüle edilmiş bir vaka analizidir. Görüşmeler
ve kullanılabilirlik testleri, gerçek saha araştırması yerine, gençlerin
finansal davranışlarına dair ikincil araştırmalara ve gerçekçi davranış
kalıplarına dayanarak kurgulanmıştır. Bu durum süreç boyunca şeffafça
belirtilmiştir.

**Rol:** Ürün Yöneticisi / UX Araştırmacısı (bireysel)
**Odak alanları:** Ürün keşfi, kullanıcı araştırması, JTBD, persona
geliştirme, journey mapping, ideation, low-fidelity tasarım,
kullanılabilirlik testi

---

## Problem

18-27 yaş arası gençler finansal güvence için birikim yapmak istiyor,
ancak mevcut finansal araçlar karmaşık geliyor, güven vermiyor ve
gelir düzenine (sabit ya da düzensiz) uyum sağlamıyor. Bu da birikim
davranışının hiç başlamamasına ya da sürdürülememesine yol açıyor.

Detaylı anlatım: [`case-study.md`](case-study.md)

---


## Proje Yapısı

| Klasör | İçerik |
|---|---|
| [`01-research/`](01-research/) | Ham içgörüler, affinity mapping, JTBD |
| [`02-personas/`](02-personas/) | İki persona (sabit vs. düzensiz gelir) |
| [`03-journey-maps/`](03-journey-maps/) | Persona bazlı journey map'ler |
| [`04-problem-definition/`](04-problem-definition/) | Problem statement, How Might We |
| [`05-ideation/`](05-ideation/) | Crazy 8s ideation ve seçilen konsept |
| [`06-user-flow/`](06-user-flow/) | Metin bazlı user flow (8 ekran) |
| [`07-wireframes/`](07-wireframes/) | HTML wireframe'ler + Figma prototip linki |
| [`08-usability-testing/`](08-usability-testing/) | Test planı, bulgular, iterasyon |
| [`assets/ui/`](assets/ui/) | Ekran görüntüleri (Figma + HTML wireframe) |
| [`case-study.md`](case-study.md) | Sürecin tam anlatımı |

---

## Temel İçgörü → Çözüm Özeti

Araştırma, birbirinden farklı ihtiyaçları olan iki kullanıcı segmenti
ortaya çıkardı:

- **Sabit gelirli kullanıcılar** görünmezlik ve finansal ürünlere güven
  sorunu yaşıyor.
- **Düzensiz gelirli kullanıcılar**, sabit tarihli/sabit tutarlı birikim
  sistemleri tarafından yeterince desteklenmiyor.

Ortaya çıkan konsept; **Round-Up birikim**, **gelire duyarlı yüzdelik
kesinti**, **görsel ilerleme takibi** ve düşük gelir aylarında cezasız
duraklama sağlayan bir **"Panik Butonu"**nu bir araya getiriyor.

---

## Wireframe'ler

### Figma Prototipi
[Figma'da Görüntüle → ](07-wireframes/figma/figma-link.md)

![Dashboard](assets/ui/figma/figma-wireframe-06-dashboard.png)
![Panik Butonu Akışı](assets/ui/figma/figma-wireframe-07-low-income-alert.png)

### HTML Wireframe'ler (Low-Fidelity)
İki dilli (TR/EN) statik wireframe'ler, tarayıcıda direkt görüntülenebilir:
- [`07-wireframes/html/savings-app-en.html`](07-wireframes/html/savings-app-en.html)
- [`07-wireframes/html/savings-app-tr.html`](07-wireframes/html/savings-app-tr.html)

![HTML Wireframe Önizleme](assets/ui/html/html-wireframe-tr-full.png)

---

## Kullanılabilirlik Testi Öne Çıkanı

Simüle edilmiş kullanılabilirlik testi, en yenilikçi özellik olan
**Panik Butonu**'nun bazı katılımcılar tarafından fark edilmediğini
ortaya çıkardı çünkü rutin bir bildirime benziyordu. Bu, görsel
ayırt ediciliği artırılarak iyileştirildi.

Detaylı bulgular: [`08-usability-testing/findings-iteration.md`](08-usability-testing/findings-iteration.md)

---

## Gerçek Kullanıcılarla Farklı Yapacağım Şeyler

- Simüle edilmiş içgörüleri doğrulamak için gerçek görüşmeler yapmak.
- Round-up ve yüzdelik kesinti yöntemlerini varsayılan olarak A/B test etmek.
- Panik Butonu'nu daha geniş bir "finansal dayanıklılık" özellik setine
  genişletmeyi araştırmak.

---

## Tam Vaka Analizini Okuyun

👉 [`case-study.md`](case-study.md) — problemden çözüme ve
değerlendirmeye kadar sürecin tam anlatımı.

