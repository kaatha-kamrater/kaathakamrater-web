# KK-Web
Detta är den nya hemsidekoden för KK. Den är skriven I HTML/MARKDOWN/JS/CSS med hjälp av Hugo och Tailwind CSS. Den hostas på Vercel.

## Utveckling
För att starta utvecklingsmiljön kör du `npm run start`. Detta startar en lokal server på `localhost:1313` som uppdateras automatiskt när du gör ändringar i koden.

Projektet kräver Hugo Extended `0.165.0` eller senare. Versionen finns även angiven i `.hugo-version`.

## Vercel
Importera repot i Vercel och lägg till miljövariabeln `HUGO_VERSION` med värdet `0.165.0` för alla miljöer. Vercel använder sedan `vercel.json` för att bygga sidan med Hugo och publicera katalogen `public`.
