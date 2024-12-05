# Autó Bérlő alkalmazás

## Készítők:
**Horváth Dávid Alexander**
**Gaál András Krisztián**

## Mi a szoftver célja?

Le klónozni egy professzionális autókereskedés Weboldalát és Mobil applikácíóját.

## Milyen funkciókat kell megvalósítani?

- **Felhasználó rész**
- Autók listájának böngészése
- Járművek bérlése/ vásárlása kapcsolatfelvétellel
<br>
- **Admin felület**
- Jármű paletta szerkesztése (Hozzádadás/Törlés)
- Járművek adatainak szerkesztése (Km állás, kor, stb.)
- Kategóriák szerkesztése 


## Szoftverkomponensek
### RestApi
A RestApi modul felelős az adatbázis kezeléséért, új adatok hozzáadásáért, törléséért, frissítéséért, illetve az adatok továbbításáért  az alkalmazás többi része, vagy más alkalmazások felé.

**Használt eszközök:**
- ASP NET
- MySQL

### Weboldal
Ez az asztali számítógépen és mobil egyaránt elérhető reszponzív weboldal lesz az applikáció elsőszámú felhasználói felülete. Emellett az adminisztrációs funkciók is weboldalon keresztül lesznek elérhetőek az üzemeltetők számára.

**Használt eszközök:**
- HTML
- CSS
- JAVASCRIPT
- Tailwind
- Svelte

### Mobil applikáció
Weboldal mellet mobilon applikáción keresztül is elérhető lesz a szolgáltatás. Ennek célja egy kényelmesebb felület biztosítása a mobilos felhasználók számára, illetve más webes felületen elérhetetlen funkciók *(például értesítések)* alkalmazása.

**Használt eszközök:**
- Flutter

## A szoftver futtatásához szükséges műszaki feltételek

- **Mobil Alkalmazás**
- Modern Android / IOS telefon
- Internet elérés
  <br>
- **Weboldal**
- Internet elérés
- Modern böngésző