Vite PWA Project
<img src="https://vitejs.dev/logo.svg" alt="Vite Logo" width="150"/>
Asennus
Ennen kuin aloitat, asenna PWA-tuki seuraavalla komennolla terminaalissa:

bash
Kopioi koodi
npm install -D vite-plugin-pwa
Kun tämä on asennettu, voit kopioida ja käyttää seuraavaa koodia.

Projektin ominaisuudet
Tämä repository sisältää täysin toimivan Progressive Web Applicationin (PWA), joka on rakennettu käyttäen Viteä. Sovellus on suunniteltu tarjoamaan nopean ja saumattoman käyttökokemuksen, ja siinä on seuraavat ominaisuudet:

Offline-ominaisuudet: Sovellusta voidaan käyttää myös ilman internet-yhteyttä.
Tehokas suorituskyky: Vite-teknologian ansiosta latausajat ovat lyhyitä ja navigointi on sujuvaa.
Progressiivinen parantaminen: Optimoitu sekä työpöytä- että mobiilikäyttäjille.
Rakentaminen kahdella HTML-sivulla
Jos haluat rakentaa projektin ja lisätä kaksi erillistä HTML-sivua (index.html ja main.html), lisää seuraava konfiguraatio vite.config.ts -tiedostoon:

ts
Kopioi koodi
// vite.config.ts

build: {  
  rollupOptions: {
    input: {
      index: './index.html',
      main: 'main.html'        
    }
  }
}
Miten osallistua
Tutustu vapaasti lähdekoodiin ja kaikki kontribuutiot ovat tervetulleita!

Tämän avulla ohjeistuksesi ovat hieman helpommin luettavissa, ja konfiguraatioiden käytön yksityiskohdat tulevat esille selkeämmin. Voit halutessasi lisätä myös linkkejä lisäresursseihin, kuten Vite PWA Plugin -dokumentaatioon, jos haluat tarjota syvempää tietoa käyttäjille.
