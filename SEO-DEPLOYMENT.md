# Reson8 site deployment notes

The local site is a static bilingual build. Greek is the default at `/`; English is under `/en/`. The site groups the original service content into Video, Audio, and Events, with a separate studio/soundstage capability page.

## Deploy

Upload the complete folder structure without flattening the nested `en/`, `ypiresies/`, `en/services/`, `assets/`, and `Reson8_files/` directories. Preserve existing HTTPS and www/non-www canonical handling at the host. If the current WordPress site remains active, map or redirect the legacy WordPress service URLs to the matching static service routes after reviewing the route plan.

Submit `/sitemap.xml` in Google Search Console after deployment. Check the production URLs and local business profile with an account owner. The site uses the existing Athens contact details and official social accounts.
