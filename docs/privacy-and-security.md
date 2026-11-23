# Privacy and security

The rule for this site: collect nothing that isn't needed, and let the browser enforce it.

## What the site collects

**Nothing in the background.** There are no cookies, analytics, trackers, ads, embeds or third-party scripts. Fonts, images and music all load from the site itself.

| Data | Where it lives | Leaves the visitor's device? |
|---|---|---|
| Display, sound and motion settings | The visitor's own browser (local storage) | No |
| Whether the intro has played this visit | The visitor's own browser (session storage) | No |
| A contact message | Sent only when the visitor presses Send | Yes, just the name, email and message they typed, delivered to my inbox through Web3Forms |

The contact form says this right where you type, and there's a plain-language privacy note in Settings.

## What the browser enforces

The site is served with strict security headers, so these rules hold even if something unexpected were ever added to a page:

- **Content Security Policy.** The page may only load its own scripts, styles, fonts, images and audio, and may only send data to the contact-form service. Anything else is refused by the browser.
- **No framing.** Other sites can't embed this one in a frame (protects against clickjacking).
- **HTTPS only.** Plain `http://` redirects to `https://`, and browsers are told to always use HTTPS.
- **No device access.** Camera, microphone, location and motion sensors are switched off at the policy level, so the site can never even ask for them.
- **Safe outbound links.** Links that open a new tab can't control or track back to this page.
- **Strict referrer and cross-origin isolation** settings limit what other sites learn from a visit.

## How it's checked

- The security policy was tested against the production build on every screen: nothing legitimate is blocked, and requests to other sites are.
- Dependencies are audited for known vulnerabilities.
- Contact-form fields have length limits and spam protection.
