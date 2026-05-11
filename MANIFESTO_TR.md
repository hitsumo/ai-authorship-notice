# AI ile yazdim. Ama bunu nasil soylerim?

*Kucuk bir sablon, buyuk olmayan bir fikir.*

---

Son birkac yildir kod yaziyorum, ama yalniz degilim. AI araclari —
Claude, ChatGPT, Abacus AI — surekli isin icinde. Bir sey isteyince
yaziyorlar, hata bulunca duzeltmek icin geri donuyoruz. Yazi
bittiginde elimde calisir bir sey oluyor. Ama soyle bir soru kaliyor
geriye: **kim yazdi?**

Ben mi? Onlar mi? Ikimiz mi?

Bu sorunun saglikli bir cevabi yok aslinda. Lisans dosyasinda "AI
kullandim" diye yazilan bir alan yok. README'lerde "tesekkurler"
bolumune AI'i koymak garip geliyor. About sayfasina "Abacus AI ile
gelistirildi" yazmak yetiyor mu, bilmiyorum. Yazilim dunyasinin
bunun icin bir aliskanligi henuz yok.

## Niye bir sey yaptim

Cunku eksik geliyordu. Kendi projemi yazarken durdum: "Bu kodu ben
mi yazdim?" Hayir, AI yazdi. "Peki ben ne yaptim?" Mimariye karar
verdim, neyi nasil isteyecegimi dusundum, yanlis seyleri reddettim,
test ettim, entegre ettim. Bu **bir sey**, ama "kod yazdim"
demekten farkli bir sey.

Bu farkin bir adi olmasi gerektigini dusundum. Olmayinca, bir
sablon yaptim. Adi: **ai-authorship-notice**.

## Sablon ne yapiyor

Uc maddeden ibaret kucuk bir markdown dosyasi:

1. **Hangi AI araclarini kullandim**
2. **Ben hangi kararlari verdim**
3. **Bu beyan benim lisansimi etkilemez**

Hepsi bu. Hukuki bir metin degil, sozlesme degil. Sadece bir
**beyan** — projenin nasil uretildigine dair durust bir not. CC0
lisansli, yani herkes alip degistirip kendi projesinde
kullanabilir.

GitHub'da: github.com/[KULLANICI-ADI]/ai-authorship-notice

## Sablon ne yapamaz

Cok seyi yapamaz, durust olalim:

- **Birisi kodumu calarsa korumaz.** Onun icin git gecmisi ve
  tarihli yayinlar var.
- **Hukuki yukumluluk getirmez.** Beyan, sozlesme degildir.
- **Hicbir tartismayi kapatmaz.** AI ile uretilen seyin "telifi
  kimde" sorusu hala acik bir hukuki konu.
- **Herkesin kullanmasi gereken bir sey degil.** Kapali kaynak ticari
  isler, NDA altindaki projeler, "AI kullanilmayacak" sozlesmeleri
  varsa **kullanilmamali**.

## Sablon ne yapabilir

Belki bir kac sey:

- **Norm baslatir.** Yeterince insan kullanirsa, "AI beyani" surasi
  burasi olmayan bir aliskanlik haline gelebilir. MIT lisansi da
  oyle yayildi — kimse zorlamadi, yaygin olunca standart oldu.
- **Dusunmeye zorlar.** Sablonu doldururken kendine sormak zorunda
  kaliyorsun: "Ben gercekten ne yaptim?" Bu soru iyi bir soru.
- **Karsi tarafa farkindalik verir.** Senin kodunla calisan biri
  goruyor: bu kodun bir kismi AI ile uretildi, ben de degisiklik
  yaparken ayni seyi dusunmeliyim.

## Belki hicbir sey olmaz

Belki bu sablon raflarda kalir. Belki birkac proje kullanir, sonra
unutulur. Belki kimse umursamaz.

Olsun. Bilgisayarima geri don, bir sey kaybetmedim. Ama denemek,
denememekten daha iyi geldi.

Eger sen de AI ile calisiyorsan ve "bunu nasil soylerim" diye
dusunduysen, sablonu bulursun. Kullanirsin, kullanmazsin, baska
bir sey yaparsin. Karar senin.

Tek isteyecegim sey: **bunu konusalim**. AI ile insan emegini ayirt
etmenin saglikli bir yolu yok henuz, ve bu yolun bulunmasi tek bir
kisinin isi degil.

---

**Sablon:** github.com/[KULLANICI-ADI]/ai-authorship-notice
**Lisans:** CC0 (kamu mali, atif zorunlu degil)
**Yazar:** [AD SOYAD]
**Tarih:** [YYYY-AA-GG]
