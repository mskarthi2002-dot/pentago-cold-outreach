# PentaGo Cold Outreach CRM

Independent mobile-friendly PentaGo Holidays Cold Outreach CRM hosted on GitHub Pages, with data and authentication on the existing PentaGo Supabase project.

**Repository website:** https://mskarthi2002-dot.github.io/pentago-cold-outreach/

This public repository must not contain any customer contact spreadsheets, personal customer details, passwords, Supabase service-role keys, or backups. The browser uses the public Supabase publishable key and authenticated RPC calls.

Setup: GitHub repository **Settings → Pages → Build and deployment → Source: GitHub Actions**. After deployment, add the GitHub Pages URL with trailing slash to Supabase Authentication → URL Configuration (Site URL and Redirect URLs).

Daily use: admin schedules up to 20 fresh contacts per salesperson per India day; staff record outreach notes/outcomes, and follow-ups remain with each owner. All records stay in the original Supabase database.

The 'Unassign' action clears the current follow-up date and owner, retaining historic records. Unowned leads do NOT enter the four-person scheduler until reassigned, so use carefully.

Do not contact opted-out records.