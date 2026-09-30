# Rovarirtófiúk — egészségügyi kártevőirtás

*(Weboldal / domain: rovarirtofiuk.hu)*

Prémium, magyar nyelvű bemutatóoldal: rovar- és rágcsálóirtás otthonoknak és vállalkozásoknak Miskolc térségében és Borsod-Abaúj-Zemplén vármegyében.

**Éles oldal:** https://rovarirtofiuk.hu

## Kapcsolat (testvérpáros)

- **Cservenyák Tamás** — egészségügyi gázmester · kártevőirtó szakember — [+36 20 370 6439](tel:+36203706439)
- **Cservenyák Ádám** — e.ü. kártevőirtó szakember — [+36 20 985 2717](tel:+36209852717)
- **E-mail:** [cservenyakt@freemail.hu](mailto:cservenyakt@freemail.hu)
- **Bázis:** Felsőzsolca · **Szolgáltatási terület:** Miskolc térsége, Borsod-Abaúj-Zemplén vármegye

## Megtekintés

Az oldal statikus HTML/CSS/JS alapú, nincs buildfolyamat:

- Éles: https://rovarirtofiuk.hu
- Előnézet (GitHub Pages): https://daekon-ship.github.io/cservenyak-tamas-latvanyterv/
- Helyben: nyissa meg az `index.html` fájlt böngészőben — minden erőforrás (CSS, JS, favicon) a fájlba van építve.

## Technológia

- Egyoldalas, reszponzív HTML (`index.html`) — a teljes CSS és JS inline van benne, így egyetlen fájlból működik (build nélkül)
- Egyedi SVG-jelvény: stilizált, áthúzott rovar (kártevőirtás-motívum) — faviconként (data-URI, beágyazva) és arculati jelként
- Google Fonts: Archivo (display) + Inter (szöveg)
- Alap SEO: magyar oldalnyelv, title, meta description, canonical (https://rovarirtofiuk.hu/), Open Graph, JSON-LD (ProfessionalService + ContactPoint)

## Vizuális rendszer — „világos + zöld”

- **Alap:** halványzöldes törtfehér (`#f4f7f1`) és tiszta fehér felületek — világos, friss megjelenés
- **Fő zöld:** mély erdőzöld (`#1e6f45`) — egészség, higiénia, természetesség
- **CTA-zöld:** élénk mohazöld (`#35c47e`) sötét zöld felületeken, mély zöld (`#1e6f45`) világos felületeken
- **Sötét kontraszt:** majdnem-fekete zöld (`#0d2b1d` / `#0a2015`) — záró CTA és lábléc
- **Visszafogott kiegészítő:** terrakotta (`#bf6a4a`) csak a kártevő-motívumon, hogy a „cél” jól elkülönüljön a „védelem”-től
- Motívumok: célkereszt + ház-kontúr + áthúzott rovar; lebegő jelvények, pulzáló gyűrűk

## Oldalszekciók

Fejléc · Hero (chipek + lebegő jelvények) · Mozgó szolgáltatás-marquee · Bizalmi sáv · Szolgáltatások (kiemelt géltechnológia kártya) · „Mit vállalunk el?” ellenőrzőlista · Kinek segítek? · Munkafolyamat · Rólunk · GYIK (accordion) · Záró CTA (kapcsolattartóval) · Lábléc · Mobilon sticky hívósáv

## Tartalmi szabályok, amelyeket az oldal betart

- Csak ellenőrzött tényadat szerepel: tevékenység (egészségügyi kártevőirtás), szolgáltatások, kapcsolattartók (Cservenyák Tamás és Cservenyák Ádám), elérhetőségek, bázis és szolgáltatási terület.
- Nincs kitalált ár, vélemény, referencia, engedélyszám, éves tapasztalat vagy „24/7” állítás. Az árra vonatkozó GYIK-válasz kifejezetten a felmérés utáni egyeztetést mondja.
- A kezelés körülményeit és az óvintézkedéseket a szakemberrel egyeztetik — nincs általános „veszélytelen” állítás.
- Nincs látszólagos ajánlatkérő űrlap: a kapcsolatfelvétel a telefon és az e-mail.

## Deployment

- **GitHub Pages (előnézet):** main branch pushra automatikusan élesedik.
- **FTP (éles, rovarirtofiuk.hu):** a projektgyökér `index.html` feltöltése a tárhely gyökerébe (single-file oldal, egyéb asset nincs).
