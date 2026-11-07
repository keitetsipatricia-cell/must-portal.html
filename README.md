# MUST Online Application Portal: Login Screen

A front-end recreation of the Mbarara University of Science and Technology (MUST) online application portal login screen, built with plain HTML, CSS and JavaScript in three separate files.

## What is inside
- **Sign In** screen: email and password fields with icons, show/hide password eye, Sign In button, "Forgot your password?" link
- **Create Account** screen: name, email, phone, password and confirm password, with validation
- **How to Apply** screen: short list of application steps
- No install or build step; just keep the three files in the same folder

## Files
| File | Purpose |
|------|---------|
| `index.html` | The page structure (HTML) |
| `style.css` | All the styling (CSS) |
| `script.js` | Validation, screen switching, show/hide password (JavaScript) |
| `README.md` | This guide |
| `logo.png` | Optional. The university crest. See below |

## Run it on your computer
1. Open the folder in **Sublime Text** to read or edit the code.
2. Double-click `index.html` to open it in your browser (best viewed on a phone-sized window).

## Add the real crest
The crest drawn in the code is a placeholder. To use the real one, save the logo image in the same folder and name it `logo.png`. The page picks it up automatically.

## Publish on GitHub Pages
1. On GitHub, open your repo and click **Add file** > **Upload files** (or open `index.html` and use the pencil icon to paste new code).
2. Drop in `index.html`, `style.css`, `script.js` and `README.md` (and `logo.png` if you have it), then click **Commit changes**.
3. Go to **Settings** > **Pages**, set **Branch** to `main` and `/ (root)`, then click **Save**.
4. After 1 to 2 minutes your site is live. Use **Visit site** on the Pages screen.

## Notes
- This is a **class project demo**. The forms are validated in the browser only; nothing is sent anywhere.
- **Never type a real password** into this demo, and do not present it as the official MUST portal.
- Validation rules: valid email format, Ugandan phone numbers (+256 7XX XXX XXX or 07XX XXX XXX), passwords of 8+ characters with letters and numbers.
