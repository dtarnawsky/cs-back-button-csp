# Ion Back Button CSP issue

The `ion-back-button` component fetches its icon using data:// which if you have a Content Security Policy with `connect-src 'self';` the icon will not load.