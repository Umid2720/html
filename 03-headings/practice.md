# 4-DARS — HTML LINKS

## HTML link nima?

HTML linklar web sahifalarni bir-biriga bog‘lash uchun ishlatiladi. Internetdagi deyarli barcha saytlar linklar orqali ishlaydi. Bir sahifadan boshqasiga o‘tish aynan link yordamida amalga oshadi.

Masalan:
- boshqa sahifaga o'tish
- boshqa saytga o'tish
- email yuborish
- telefon qilish
- fayl yuklab olish

HTML da link yaratish uchun `<a>` tegi ishlatiladi.

---

## `<a>` tegi

Link yaratish sintaksisi:

```html
<a href="manzil">Link matni</a>
```

Misol:

```html
<a href="https://google.com">Google ga o'tish</a>
```

Bu yerda:
- `<a>` — link tegi
- `href` — link manzili
- `Google ga o'tish` — foydalanuvchi ko‘radigan matn

---

## href atributi

`href` — HyperText Reference degan ma'noni anglatadi. Bu atribut link qayerga olib borishini ko‘rsatadi.

Misol:

```html
<a href="https://youtube.com">YouTube</a>
```

Bu link bosilganda YouTube sayti ochiladi.

---

## Yangi tabda ochish

Ba'zan linkni yangi tabda ochish kerak bo‘ladi. Buning uchun `target` atributi ishlatiladi.

```html
<a href="https://google.com" target="_blank">Google</a>
```

`target="_blank"` — linkni yangi tabda ochadi.

---

## Ichki sahifaga link

Agar sayt ichidagi boshqa sahifaga o‘tmoqchi bo‘lsak, shu sahifaning nomini yozamiz.

Masalan saytimizda quyidagi fayllar bor:

index.html  
about.html  
contact.html  

Biz shunday link yozamiz:

```html
<a href="about.html">About sahifasi</a>
```

---

## Rasm orqali link

Link ichiga rasm ham qo‘yish mumkin.

```html
<a href="https://google.com">
<img src="google.png" alt="Google">
</a>
```

Bu holda rasm bosilganda link ishlaydi.

---

## Email link

HTML yordamida email yuborish linki yaratish mumkin.

```html
<a href="mailto:test@gmail.com">Email yuborish</a>
```

Bu link bosilganda email dasturi ochiladi.

---

## Telefon link

Telefon raqamga qo‘ng‘iroq qilish uchun ham link ishlatiladi.

```html
<a href="tel:+998901234567">Telefon qilish</a>
```

Bu asosan telefon qurilmalarida ishlaydi.

---

## To‘liq misol

```html
<!DOCTYPE html>
<html>
<head>
<title>HTML Links</title>
</head>

<body>

<h1>HTML Links misollari</h1>

<h2>Oddiy link</h2>
<a href="https://google.com">Google ga o'tish</a>

<br><br>

<h2>Yangi tabda ochish</h2>
<a href="https://youtube.com" target="_blank">YouTube ochish</a>

<br><br>

<h2>Ichki sahifa</h2>
<a href="about.html">About sahifasi</a>

<br><br>

<h2>Email link</h2>
<a href="mailto:test@gmail.com">Email yuborish</a>

<br><br>

<h2>Telefon link</h2>
<a href="tel:+998901234567">Telefon qilish</a>

</body>
</html>
```

---

## Xulosa

HTML da link yaratish uchun `<a>` tegi ishlatiladi.

Eng muhim atributlar:
- `href` — link manzili
- `target="_blank"` — yangi tab
- `mailto:` — email yuborish
- `tel:` — telefon qilish