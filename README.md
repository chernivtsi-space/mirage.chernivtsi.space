# Mirage

Live site: https://mirage.chernivtsi.space

## About
Mirage — готель у Чернівцях. Односторінковий лендинг без фото (`photos_source: null`): типографіка та CSS/SVG-графіка.

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
HotelOS (`kp-mirage`): `stay-request` (проживання). Документ `hotels/kp-mirage` у Firestore треба створити вручну, інакше правила відхилять заявки.

## SEO
Title і description з маніфесту, canonical, Open Graph, `geo.*`, JSON-LD `Hotel` лише з підтвердженими полями (без numberOfRooms, starRating, aggregateRating), `robots.txt`, `sitemap.xml`, `404.html`.
