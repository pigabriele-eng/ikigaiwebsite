# ikigaisolutions.ae

The live IKIGAI Solutions site: one static page (`index.html`), its photos in `img/`, icons, and `.htaccess` for Apache/cPanel hosting.

## Put it online (aeserver cPanel)
1. Log in to cPanel and open **File Manager**, then `public_html`.
2. Upload everything in this repo (download it as ZIP from GitHub: Code > Download ZIP, upload the zip, then Extract). Make sure `index.html` sits directly in `public_html`, not in a subfolder.
3. In cPanel, open **SSL/TLS Status** and run AutoSSL for ikigaisolutions.ae and www.
4. Once https works, uncomment the four Rewrite lines in `.htaccess` so every visit goes to https://ikigaisolutions.ae.

## Contact form
Sent through FormSubmit to hello@ikigaisolutions.ae. The very first submission sends an activation email to that inbox; click the link in it once and every later message arrives normally.
