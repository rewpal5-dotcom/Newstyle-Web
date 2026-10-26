# Newstyle

Ek chhoti si wrapper site — upar **Newstyle** naam, aur neeche aapki website seedha embed hoti hai.

Live: **https://rewpal5-dotcom.github.io/Newstyle-Web/**

## Kaise kaam karta hai

- Header mein sirf project ka naam "Newstyle" dikhta hai.
- Neeche `<iframe>` mein website khulti hai: `https://neon-name8700.base44.app/`
- "Naye tab mein" button se wahi website alag tab mein khul jaati hai.
- "Reload" button iframe ko dobara load karta hai.

## Note

Kuch websites security header (`X-Frame-Options` / CSP `frame-ancestors`) ki wajah se doosri site ke andar khulna block kar deti hain. Aisa ho to page par "Website kholen" button se naye tab mein kholein.

## Doosri website lagani ho to

`index.html` mein do jagah URL badal dein — iframe ka `src` aur header/footer ke links.

## Tech

Single file, vanilla HTML + CSS + JS. Koi dependency nahi.

## License

MIT
