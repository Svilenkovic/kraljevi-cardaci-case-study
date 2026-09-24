<a href="https://kraljevicardaci.svilenkovic.rs/"><img src="media/cover.jpg" alt="Kraljevi Čardaci 11/61, naslovna strana na laptopu i telefonu" width="100%"></a>

# Kraljevi Čardaci 11/61

Jedna strana na srpskom i engleskom za apartman koji se istovremeno prodaje i izdaje, u kompleksu Kraljevi Čardaci Spa na Kopaoniku.

**[kraljevicardaci.svilenkovic.rs](https://kraljevicardaci.svilenkovic.rs/)** · [Studija slučaja](https://svilenkovic.rs/radovi/kraljevi-cardaci) · [English](README.md)

> [!NOTE]
> Klijentski projekat. Izvorni kod pripada klijentu i čuva se u privatnom repozitorijumu. Ova stranica opisuje šta sam uradio i kako.

<table>
  <tr><td><b>Klijent</b></td><td>Apartman 11/61, Kraljevi Čardaci</td></tr>
  <tr><td><b>Delatnost</b></td><td>Prodaja i izdavanje apartmana</td></tr>
  <tr><td><b>Lokacija</b></td><td>Kopaonik</td></tr>
  <tr><td><b>Vrsta</b></td><td>Dvojezični sajt na jednoj strani</td></tr>
  <tr><td><b>Moj deo posla</b></td><td>Dizajn, izrada, SEO, hosting i održavanje</td></tr>
  <tr><td><b>Tehnologije</b></td><td>Next.js 16, React 19, next-intl, Tailwind</td></tr>
</table>

## O projektu

Apartman 11/61 je u kompleksu Kraljevi Čardaci Spa na Kopaoniku, a vlasnik ga istovremeno prodaje i izdaje, bez agencije. Ista strana mora da radi za dva sasvim različita posetioca: onog koji traži nekoliko noći na planini i onog koji razmišlja o kupovini nekretnine. Obojica stižu do istog broja telefona, pa strana pokušava da unapred odgovori na pitanja koja bi svaki od njih postavio pre poziva.

Cena, raspoloživost i pravni status se menjaju, pa ih strana ne objavljuje i to otvoreno kaže, a za sve što se menja upućuje na vlasnika. Galerija prikazuje samo kompleks i zajednički spa centar, uz napomenu da to nisu fotografije enterijera apartmana, a u podnožju piše da ovo nije zvanični sajt kompleksa. Spa sadržaji su opisani uz link ka zvaničnom izvoru, jer se ponuda kompleksa može promeniti bez najave.

## Šta sam uradio

- Srpski u korenu sajta, engleski na `/en`, sa hreflang parovima u zaglavlju strane i u mapi sajta
- Bez automatskog prebacivanja po jeziku pregledača: svako prvo dobija srpski i jednim klikom prelazi na engleski
- Tekstovi, opisi i česta pitanja u dva prevodna fajla, a u engleskom HTML-u se traže naša slova, da ništa ne ostane neprevedeno
- Česta pitanja koja ljudi postavljaju pre poziva, označena i kao `FAQPage`
- Samo telefon i Viber, bez forme i bez sandučeta koje neko mora da prati
- Uzajamni linkovi sa drugim apartmanom istog vlasnika u centru Kopaonika

## Merenja

| | Performanse | Pristupačnost | Dobre prakse | SEO |
| :-- | :-: | :-: | :-: | :-: |
| Telefon | 99 | 100 | 100 | 100 |
| Desktop | 96 | 100 | 100 | 100 |

PageSpeed Insights, laboratorijsko merenje živog sajta, septembar 2026. Sigurnosna zaglavlja: 6 od 6. HTML validator: bez grešaka. axe provera pristupačnosti: bez prekršaja. Strukturisani podaci: `Apartment`, `FAQPage`, `Person`, `Resort`.

## Snimci ekrana

<table>
  <tr>
    <td width="68%" valign="top"><img src="media/desktop.webp" alt="Kraljevi Čardaci 11/61, naslovna strana na ekranu širine 1440 px"></td>
    <td width="32%" valign="top"><img src="media/mobile.webp" alt="Kraljevi Čardaci 11/61, naslovna strana na telefonu"></td>
  </tr>
</table>

<img src="media/inner-1.webp" alt="O apartmanu: šest kartica za dnevnu sa kuhinjom, spavaću, kupatilo, grejanje, TV i pogled">
<sub>O apartmanu: šest kartica za dnevnu sa kuhinjom, spavaću, kupatilo, grejanje, TV i pogled</sub>

<img src="media/inner-2.webp" alt="Prodaja: cena na upit, uz poziv i Viber umesto agencije">
<sub>Prodaja: cena na upit, uz poziv i Viber umesto agencije</sub>

---

<sub>Izrada: [D. Svilenković](https://svilenkovic.rs).</sub>
