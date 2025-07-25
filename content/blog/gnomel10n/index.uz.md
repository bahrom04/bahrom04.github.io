+++
title = "Mahalliylashtirish"
authors = ['Bahrom04']
description = "Ushbu sahifada siz GNOME va boshqa mahalliylashtirish loyihalarida ishtirok etish haqida ma’lumot olsangiz bo‘ladi"
date = 1970-01-01
[taxonomies]
tags = ["Lorem"]
[extra]
poor = true
+++

# GNOME Linux ga o‘zbek tilini qo‘shish

GNOME – bu Linux operatsion tizimida ishlatiladigan ish stoli muhiti (inglizcha: [desktop environment](https://en.wikipedia.org/wiki/Desktop_environment)).

GNOME tarkibiga kalkulyator, kalendar, kamera, soat, terminal, ob-havo kabi kunlik hayotda zarur bo‘lgan ilovalar to‘plami kiradi.

Ishda brauzer, Telegram, Microsoft Word, kalkulyator kabi dasturlardan foydalanganimizda, ko‘pchilikda ular oldindan rus yoki ingliz tilida sozlangan bo‘ladi. Agar o‘zbek tili mavjud bo‘lmasa, majburan boshqa tillardan foydalanamiz. Natijada, kundalik nutqimizga skachat, efir, podpischik, nastroyka kabi so‘zlar aralashib, ularning o‘zbekcha muqobillari yodimizdan chiqib ketishi mumkin.

2025-yil 25-mart holatiga ko‘ra, GNOME 48.0 versiyasining tarjima qilingan ulushi quyidagicha:

- Qozoq tili – 63%
- Tojik tili – 26%
- Qirg‘iz tili – 11%
- O‘zbek tili – atigi 6%

Bu holatni yaxshilash uchun har birimiz o‘z hissamizni qo‘shishimiz kerak.

> Agar biz bugun bu ishlarni qilmasak unda kim qiladi? "Keyingi avlod da bo‘lib qolar..." deydigan keyingi avloddami? - [Orzklv](https://orzklv.uz/uz)

## Ro‘yxatdan o‘tish

https://l10n.gnome.org/register havolasiga kirib kerakli ma’lumotlarni kiritamiz.

![Ro‘yxatdan o‘tish qadami](./l10n/figure-1.png)

https://l10n.gnome.org/teams/uz o‘zbek guruhiga qo‘shilamiz

![Tarjimonlar jamoasiga qo‘shilish qadami](./l10n/figure-2.png)

https://l10n.gnome.org/languages/uz/gnome-48/ui havolasiga o‘tib tarjima qilinmagan modullarni ko‘rishimiz mumkin.

![Tarjima kategoriyalari](./l10n/figure-3.png)

Ko‘rishingiz mumkin yashil va qizil ranglar qanchalik tarjima qilingan yoki qilinmaganligini bildiradi. Quyidagi “libsecret” moduli tarjima qilingan lekin “tecla” qizil rangda. “Tecla”ni tarjima qilish uchun ustiga bosamiz.

![Tarjimalar ro‘yxati](./l10n/figure-4.png)

Bizga kerakli .po faylni yuklab olamiz

![Tarjima qilish uchun faylni yuklash](./l10n/figure-5.png)

.po fayl bilan ishlash uchun [Poedit](https://poedit.net/) ishlataman va shu dasturda tarjima qilishni maslahat beraman. Quyida Ubuntu va Mac uchun yuklab olish:

### Ubuntu

```
sudo apt-get poedit -y
```

### MacOs

```
brew install --cask poedit
```

![Poedit ishlatish](./l10n/figure-6.png)

Chap tomonda inglizcha matn, o‘ng tomonda esa uning o‘zbekcha tarjimasi ko‘rsatiladi. Pastroqda joylashgan "**Translation**" maydoniga o‘zbekcha tarjimani kiritishingiz kerak. Quyidagi qoidalarga amal qilish lozim:

- Inglizcha so‘z bosh harf yoki kichik harf bilan boshlangan bo‘lsa, o‘zbekcha tarjimada ham shu tartibga rioya qilinadi.

- Agar inglizcha matn nuqta bilan tugasa, o‘zbekcha tarjima ham nuqta bilan tugashi kerak.

- Tarjima tugagach, faylni saqlang va modul sahifasida "Upload new translation" tugmasini bosib, .po faylini yuklang.

![Yangi tarjima yuklash qadami](./l10n/figure-7.png)

Qilgan tarjimangiz tez orada guruh administratori tomonidan ko‘rib chiqiladi. Sizga izoh qoldiriladi va ro‘yxatdan o‘tgan email manzilingizga xabar yuboriladi.

Agar o‘zingiz tanlagan modulni oldindan band qilib qo‘ysangiz, boshqa tarjimonlar uni ishlashga olmagan bo‘lishadi. Biroq, uni qanchada tugatishingizni izohda (kommentariyda) ko‘rsatib qo‘yish maqsadga muvofiq.

![Tarjima rezervlash qadami](./l10n/figure-8.png)

E’tiboringiz uchun rahmat !