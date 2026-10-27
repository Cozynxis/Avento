# Avento

**Your ideas. Your workspace.**

Gratis webgebaseerde Office-suite met Write, Sheets, Slides en Notes.

## Starten

1. Installeer Node.js 20.19+ of 22.12+.
2. Voer `npm install` uit.
3. Kopieer `.env.example` naar `.env` en vul de Supabase publishable key in.
4. Voer `npm run dev` uit.

De eerste versie bevat authenticatie, dashboard, app-launcher en een eenvoudige tekstbasis voor de vier apps. Dit zijn nog **geen volledige Office-editors**. Voor het opslaan moet de database-migratie in Supabase zijn uitgevoerd.

De service-role key hoort **nooit** in frontendcode of GitHub.

<!-- Redeploy after Supabase email confirmation setting update. -->
