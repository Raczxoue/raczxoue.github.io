# raczxoue.github.io

This repository hosts NearByt’s public callback pages:

- **/auth-callback/** → the canonical confirmation landing used by Supabase emails  
- **/nearbyt-confirm/** and **/ecobyt-confirm/** → simple redirects to **/auth-callback/**

Opening \/auth-callback/\ directly shows “One more step” (no token).  
When opened from the confirmation email, a token is present and you’ll see “Email confirmed!”.
