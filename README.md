# Lager saldo (RTG-app)

Ett internt webbverktyg som jag har byggt för min arbetsplats för att hålla koll på lagersaldot av kalibrerade TV-apparater och datorer. 

**Live-demo:** [https://wisambaldawi.github.io/RTG-app/](https://wisambaldawi.github.io/RTG-app/)

## Om projektet
Tanken med appen är att säljarna snabbt ska kunna se vad som finns tillgängligt och plocka bort enheter när de säljs, medan den tekniska supporten använder systemet för att lägga till nya produkter allt eftersom de blir färdiga. Eftersom databasen synkar i realtid är lagersaldot alltid uppdaterat för alla.

Jag byggde detta både för att lösa ett praktiskt problem på jobbet, och för att få praktisk erfarenhet av att koppla en frontend mot en molndatabas och hantera publicering via Git.

## Teknik
- **Frontend:** HTML, JavaScript och Tailwind CSS (via CDN).
- **Databas:** Supabase (PostgreSQL).
- **Hosting:** GitHub Pages.

