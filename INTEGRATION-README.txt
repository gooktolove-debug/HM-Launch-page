TSUNAMI TEST INTEGRATION

Copy these items into the root of the existing Launch Page repository:
- index.html
- app.js
- tsunami/
  - index.html

The main Tsunami Modelling card now uses ./tsunami/ and opens tsunami/index.html in a new tab.
The Tsunami page includes a Dashboard button that returns to ../ (the main page).

Important: The Tsunami page still uses its existing Supabase project, tide-data bucket, poa-tsunami-pdfs bucket, Leaflet, PDF.js, and external CDN dependencies. Those were intentionally retained for this first integration test.
