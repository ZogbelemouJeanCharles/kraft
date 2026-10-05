# KRAFT

Landingspagina van KRAFT: creatieve workshops in koffiebars.
Een schoolonderneming van Marit, Fien, Soniya, Jean-Charles, Elif en Kiara.

De hele website zit in één bestand: `index.html`. Er is geen installatie of build nodig.

## Online zetten met GitHub Pages

1. Maak een nieuwe repository op GitHub, bijvoorbeeld `kraft`.
2. Klik op **Add file → Upload files** en sleep `index.html` en `README.md` erin. Klik op **Commit changes**.
3. Ga naar **Settings → Pages**.
4. Kies bij *Source* **Deploy from a branch**, kies branch `main` en map `/ (root)`, en klik op **Save**.
5. Na een minuutje staat de site op `https://<jouw-gebruikersnaam>.github.io/kraft/`.

## Eigen domeinnaam koppelen (bv. kraft.be)

1. Koop de domeinnaam bij een registrar (bv. Combell, One.com, Namecheap).
2. Op GitHub: **Settings → Pages → Custom domain**. Typ je domein (bv. `www.kraft.be`) en klik op **Save**.
3. Bij je registrar, in de DNS-instellingen:
   - Een **CNAME**-record: naam `www`, waarde `<jouw-gebruikersnaam>.github.io`
   - Vier **A**-records voor het hoofddomein (`@`):
     `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
4. Wacht tot de DNS is bijgewerkt (soms een paar uur) en vink daarna **Enforce HTTPS** aan.

## Aanpassen

- **Teksten**: zoek de tekst in `index.html` en pas hem aan.
- **Workshops en prijzen**: in de sectie `id="workshops"`.
- **Kleuren**: bovenaan in `:root` (bv. `--ink` is het blauw, `--sun` het geel).
