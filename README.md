# Sheets Barcode Scanner

**Inboeken** en **Uitboeken** scanners met retro Windows 95-look.

## Installatie

1. Upload alle bestanden naar je repo.
2. Zet GitHub Pages aan (Settings → Pages → root).
3. Roll web‑app in Google Sheets:
   - Plak `Code.gs`
   - Deploy als Web App (‘Iedereen met link’)
   - Kopieer URL en vervang `JE_WEB_APP_URL_HIER` in HTML.
4. Voeg knoppen in de Sheet die `openInboekenScanner()` en `openUitboekenScanner()` aanroepen.

### Web App functies

```javascript
function openInboekenScanner() { … }
function openUitboekenScanner() { … }
