# Ducknest site - deploy notes

Upload everything in this folder to the ROOT of your GitHub Pages repo
(site URL: https://ducknest-company.github.io/.com/).

index.html      main site (Poultry Farming button -> poultry/)
dashboard.html  customer sign-up / login / dashboard (Product button -> product.html)
product.html    product page (white text, Back returns to dashboard)
admin.html      admin console
app.js          shared data layer - JSONBin (bin id + access key already set)
images/         all pictures (separated from the HTML so pages load fast)
poultry/        poultry pages + poultry/assets (css, js, img)

Auto-logout: customers 3 minutes idle (app.js -> idleCustomerSeconds: 180).
Admin idle logout is app.js -> idleAdminSeconds (48 as you had it).

Contacts: Telegram support t.me/ducknestcustomerservice
          WhatsApp 09029200486 (wa.me/2349029200486)
          Channel t.me/ducknestfinance

Poultry images: ducks-farm, duck-ponds, egg-sorting-line, ducklings-brooder and
world-map-network are your 5 photos. The other 6 (global-hq, solar-farm-aerial,
hatchery-incubation, daily-care, export-logistics, co-owners-meeting) are crops of
those photos - replace any of them in poultry/assets/img/ with a real photo using
the same file name.
