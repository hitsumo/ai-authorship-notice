# AI ile yazdım. Ama bunu nasıl söylerim?

*Küçük bir şablon, büyük olmayan bir fikir.*

---

Son birkaç yıldır kod yazıyorum, ama yalnız değilim. AI araçları —
Claude, ChatGPT, Abacus AI — sürekli işin içinde. Bir şey isteyince
yazıyorlar, hata bulunca düzeltmek için geri dönüyoruz. Yazı
bittiğinde elimde çalışır bir şey oluyor. Ama şöyle bir soru kalıyor
geriye: **kim yazdı?**

Ben mi? Onlar mı? İkimiz mi?

Bu sorunun sağlıklı bir cevabı yok aslında. Lisans dosyasında "AI
kullandım" diye yazılan bir alan yok. README'lerde "teşekkürler"
bölümüne AI'ı koymak garip geliyor. About sayfasına "Abacus AI ile
geliştirildi" yazmak yetiyor mu, bilmiyorum. Yazılım dünyasının
bunun için bir alışkanlığı henüz yok.

## Niye bir şey yaptım

Çünkü eksik geliyordu. Kendi projemi yazarken durdum: "Bu kodu ben
mi yazdım?" Hayır, AI yazdı. "Peki ben ne yaptım?" Mimariye karar
verdim, neyi nasıl isteyeceğimi düşündüm, yanlış şeyleri reddettim,
test ettim, entegre ettim. Bu **bir şey**, ama "kod yazdım"
demekten farklı bir şey.

Bu farkın bir adı olması gerektiğini düşündüm. Olmayınca, bir
şablon yaptım. Adı: **ai-authorship-notice**.

## Şablon ne yapıyor

Üç maddeden ibaret küçük bir markdown dosyası:

1. **Hangi AI araçlarını kullandım**
2. **Ben hangi kararları verdim**
3. **Bu beyan benim lisansımı etkilemez**

Hepsi bu. Hukuki bir metin değil, sözleşme değil. Sadece bir
**beyan** — projenin nasıl üretildiğine dair dürüst bir not. CC0
lisanslı, yani herkes alıp değiştirip kendi projesinde
kullanabilir.

GitHub'da: github.com/hitsumo/ai-authorship-notice

## Şablon ne yapamaz

Çok şeyi yapamaz, dürüst olalım:

- **Birisi kodumu çalarsa korumaz.** Onun için git geçmişi ve
  tarihli yayınlar var.
- **Hukuki yükümlülük getirmez.** Beyan, sözleşme değildir.
- **Hiçbir tartışmayı kapatmaz.** AI ile üretilen şeyin "telifi
  kimde" sorusu hâlâ açık bir hukuki konu.
- **Herkesin kullanması gereken bir şey değil.** Kapalı kaynak ticari
  işler, NDA altındaki projeler, "AI kullanılmayacak" sözleşmeleri
  varsa **kullanılmamalı**.

## Şablon ne yapabilir

Belki birkaç şey:

- **Norm başlatır.** Yeterince insan kullanırsa, "AI beyanı" sıra
  dışı olmayan bir alışkanlık haline gelebilir. Yaygın lisanslar
  da böyle bir süreçten geçti — kimse zorlamadı, yaygın olunca
  standart oldu.
- **Düşünmeye zorlar.** Şablonu doldururken kendine sormak zorunda
  kalıyorsun: "Ben gerçekten ne yaptım?" Bu soru iyi bir soru.
- **Karşı tarafa farkındalık verir.** Senin kodunla çalışan biri
  görüyor: bu kodun bir kısmı AI ile üretildi, ben de değişiklik
  yaparken aynı şeyi düşünmeliyim.

## Belki hiçbir şey olmaz

Belki bu şablon raflarda kalır. Belki birkaç proje kullanır, sonra
unutulur. Belki kimse umursamaz.

Olsun. Bilgisayarıma geri dönerim, bir şey kaybetmedim. Ama denemek,
denememekten daha iyi geldi.

Eğer sen de AI ile çalışıyorsan ve "bunu nasıl söylerim" diye
düşündüysen, şablonu bulursun. Kullanırsın, kullanmazsın, başka
bir şey yaparsın. Karar senin.

Tek isteyeceğim şey: **bunu konuşalım**. AI ile insan emeğini ayırt
etmenin sağlıklı bir yolu yok henüz, ve bu yolun bulunması tek bir
kişinin işi değil.

---

**Şablon:** github.com/hitsumo/ai-authorship-notice
**Lisans:** CC0 (kamu malı, atıf zorunlu değil)
**Yazar:** Okan Sümer
**Tarih:** 2026-05-12
