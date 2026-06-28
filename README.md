# Infranova AS – nettside

Statisk nettside for Infranova AS. Kan publiseres gratis med **GitHub Pages** – ingen server eller bygg-steg.

## Innhold

```
index.html        – selve nettsiden (forside, om oss, tjenester, referanser, kontakt, innlogging)
support.js        – kjøretid for siden (lastes automatisk)
media/            – logo, symbol og bilder (komprimert)
verktoy/          – interne verktøy bak innlogging
  utm32-til-mapsmadeeasy.html
  python-kalkulator-demo.html
  maler/          – Excel-/CSV-filer til nedlasting
```

## Publisere med GitHub Pages

1. Opprett et nytt repository på GitHub (f.eks. `infranova-nettside`).
2. Last opp **alle** filene i denne mappa til repoet (behold mappestrukturen).
3. Gå til **Settings → Pages**.
4. Under *Build and deployment* velg **Deploy from a branch**, branch **main** og mappe **/(root)**. Lagre.
5. Etter et par minutter er siden tilgjengelig på `https://<brukernavn>.github.io/<repo-navn>/`.

Vil du bruke eget domene (f.eks. `infranova.no`), legg det inn under **Settings → Pages → Custom domain**.

## Innlogging for ansatte

- Førstegangsbruker (administrator): **magne@infranova.no** / **InfraNova-2025!**
- Administrator kan invitere flere ansatte og styre tilgangsnivå under fanen *Ansatte*.

> Merk: Innlogging og brukere lagres lokalt i nettleseren (enkel sperre, ikke ekte sikkerhet).
> Skal det bli ekte flerbruker-innlogging på tvers av maskiner, kreves en backend-tjeneste.

## Krever internett

Siden henter noen ressurser fra nett (skrifter og kjøretidsbibliotek), så den må vises i en nettleser med internettilgang. Det er ingen problem på GitHub Pages.
