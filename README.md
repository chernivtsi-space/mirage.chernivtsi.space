# Mirage

Live site: https://mirage.chernivtsi.space

## About
Mirage — готель у Чернівцях. Односторінковий лендинг. Фото закладу немає (`photos_source: null`), тому hero типографічний (CSS/SVG), а єдині фото — міста Чернівців з Pexels (див. Photos).

## Hero concept
Відображення-міраж: назва «Mirage» над лінією горизонту і її розмите перевернуте відображення, що ледь «тремтить». Теплий градієнт сутінок.

## Amenities (verified, list.json)
- Безкоштовний Wi‑Fi
- Цілодобова рецепція
- Приватна парковка
- Сімейні номери
- Власна ванна кімната
- Холодильник
- Робочий стіл
- Номери для некурців

## Check-in / check-out
не встановлено

## Reviews
Booking.com 8.2/10 (447), Google 4.2/5 (177). Знімок на 30.09.2026, платформи окремо, без aggregateRating.

## Contact
- Phone: +380 99 014 8006
- Booking.com: https://www.booking.com/hotel/ua/mirage-chernivtsi.en-gb.html
- Google Maps: https://maps.google.com/?cid=1438619668549480458
- Address: вул. Руська, 207-В, Чернівці

## Not published
Час заїзду/виїзду, кількість номерів, зірковість, email, сайт, Instagram. Парковка — лише «приватна», не «безкоштовна».

## Forms
HotelOS (`ch-mirage`): `stay-request` (проживання). Документ `hotels/ch-mirage` у Firestore треба створити вручну, інакше правила відхилять заявки.

## Photos
Лише фото міста (не готелю), з Pexels, підключені за прямими посиланнями images.pexels.com (без копій у репо), з підписами та авторами на сторінці:

- Сади Резиденції митрополитів: pexels.com/photo/38163645 (Natalia Sevruk)
- Храм у Резиденції митрополитів: pexels.com/photo/20074400 (Anastasiia Kalushka)
- Вулиця в Чернівцях: pexels.com/photo/17268858 (Андрій Копічевський)

## SEO
Title і description з маніфесту, canonical, Open Graph, `geo.*`, JSON-LD `Hotel` лише з підтвердженими полями (без numberOfRooms, starRating, aggregateRating), `robots.txt`, `sitemap.xml`, `404.html`.
