# Backyard Kitchen Website — Part 3

## Part 3 functionality and SEO
- Mobile navigation opens/closes accessibly and closes after a link is selected.
- Menu page includes a live search/filter across menu categories.
- Food/menu images open in an accessible dialog lightbox and can be opened by keyboard.
- Contact form uses browser validation and clearly explains that no message is sent until a backend/form service is connected.
- Each page has a specific meta description, page title, Open Graph title/description, and theme colour.
- Added `robots.txt`; a sitemap with absolute URLs should be added after the final hosting URL is known.
- CSS reset now applies box-sizing to all elements; responsive layouts, focus states, and reduced-motion support remain.
- the orange Colouring was fully extended to other pages.

## Known setup needed before public launch
1. Connect the contact form to a real form service or server. Do not tell visitors a message was sent until this is configured.
2. Add confirmed delivery-platform URLs and verified opening hours/address details if required.
3. Once hosted, add the final site URL to a sitemap and update `robots.txt` with that sitemap URL.
4. Test at desktop, tablet and mobile sizes; capture screenshots for the assignment evidence.

## Testing checklist
- `index.html`, `menu.html`, `about.html`, and `contact.html`.
- Test navigation on desktop and mobile widths.
- Search for “chicken”, “kota”, and a term with no matches on the menu page.
- Open an image using both mouse and keyboard; close the lightbox.
- Submit the contact form empty, then with valid values; verify the notice accurately says it was not  sent.
- Check browser DevTools Console and Network for errors or missing files.
- Commit the changes and push to the GitHub remote.

## References 
1. W3Schools.(n.d).HTML Tutorial.https://www.w3school.com/html/
2. W3Schools.(n.d).CSS Tutorial.https://www.w3schools.com/css/
3. W3Schools.(n.d).JavaScript Tutorial.https://www.w3schools.com/js/
4. W3Schools.(n.d).Responsive Web Design.https://www.w3schools.com/css/css_rwd_intro.asp
