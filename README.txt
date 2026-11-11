EWEW 1.1 — kostnadsfri iPhone-webbapp

INNEHÅLL
Chattgränssnitt, lokalt sparade konversationer, export/import av JSON, radering av en chatt, offline-gränssnitt och PWA-stöd.

PUBLICERING UTAN BETALNING
Packa upp ZIP-filen och publicera mappen ewew på en gratis statisk webbhosting med HTTPS, till exempel GitHub Pages eller Cloudflare Pages (kontrollera aktuella villkor). Öppna sedan adressen i Safari på iPhone, välj Dela > Lägg till på hemskärmen. Att ladda ned ZIP-filen installerar inte appen automatiskt.

AI-ANSLUTNING
Öppna Inställningar och välj en leverantör, eller ange en egen OpenAI-kompatibel HTTPS-endpoint, modell och eventuell API-nyckel. Leverantören måste acceptera anrop direkt från webbläsaren (CORS). Groq och OpenRouter finns som exempel/presets, men gratis tillgång och modellnamn kan ändras och fungerar inte garanterat. Ingen nyckel sparas permanent. En API-nyckel i en webbläsare är synlig för den som har tillgång till enheten och kan exponeras via tillägg/komprometterad miljö; använd bara nycklar med begränsad behörighet och inga betalda krediter.

BEGRÄNSNINGAR
Appen har ingen server, ingen synkning mellan enheter och ingen användarinloggning. Historik sparas okrypterad lokalt i webbläsaren; den som har åtkomst till webbläsarprofilen kan läsa den. Offline fungerar appens gränssnitt och historik, men AI-svar kräver internet och en fungerande leverantör. Inga löpande AI-anrop sker utan att du själv konfigurerar leverantör.
