# United Leadership Development by Korlu: going live

This folder is the complete website. It runs free on GitHub Pages.

## 1. Connect the waitlist form (Formspree), about 5 minutes

1. Go to https://formspree.io and sign up with the email that should receive signups (e.g. gaygaykorlu@gmail.com). Confirm the email.
2. Click **New Form**, name it "Meeting Waitlist", and create it.
3. Copy the form endpoint. It looks like `https://formspree.io/f/abcdwxyz`.
4. Open `index.html` in Notepad (right-click → Open with → Notepad).
5. Press Ctrl+F and search for `PASTE_FORMSPREE_ENDPOINT_HERE`. Replace that text with your endpoint, keeping the quotes. Save.

Until this is done, the form shows an error asking visitors to call or email instead, so nobody is told they joined when they didn't.

In Formspree's form settings, also turn on reCAPTCHA or spam filtering and add your website address to "Allowed domains" once you know it.

## 2. Publish with GitHub Desktop

1. Open **GitHub Desktop** → File → **Add local repository** → choose this folder.
   It will say it isn't a repository yet; click **create a repository**, keep the name `united-leadership-development`, and click **Create repository**.
2. Click **Publish repository**. **Uncheck "Keep this code private"** (free GitHub Pages needs a public repo), then Publish.
3. Click **Repository → View on GitHub**.
4. On GitHub: **Settings → Pages**. Under "Build and deployment", Source = **Deploy from a branch**, Branch = **main**, folder = **/ (root)**. Save.
5. Wait 1–2 minutes, then refresh. Your site link appears at the top, like `https://YOURNAME.github.io/united-leadership-development/`.

## 3. Test it

Open the live link on your phone, join the waitlist with your own details, and confirm the signup arrives in Formspree and by email.

## Making changes later

Edit the files, then in GitHub Desktop: write a short summary → **Commit to main** → **Push origin**. The live site updates in a minute or two.

- Swap the portrait: replace `assets/korlu.jpg` with a new photo of the same name.
- Bio and privacy policy: search `index.html` for "Bio placeholder" and "Privacy policy" and replace the placeholder text with approved copy **before sharing the site publicly**.

## Custom domain (optional)

If you buy a domain (e.g. uldbykorlu.com), add it under Settings → Pages → Custom domain and follow GitHub's DNS instructions. Then add that domain to Formspree's allowed domains.
