# Day One Parental Leave Australia – website

Static site (plain HTML) for GitHub Pages. Sign-ups go to Web3Forms and arrive in your email.

## Put it online
1. Create a free account at github.com, then **New repository** (name e.g. `dayone`, set to **Public**).
2. **Add file > Upload files**: drag in everything from this folder (index.html, privacy.html, the images and the `docs` folder). Commit.
3. **Settings > Pages**: Source = *Deploy from a branch*, Branch = `main`, folder `/ (root)`. Save. After a minute the site is at `https://YOURNAME.github.io/dayone/`.
4. Optional: add your own domain under Settings > Pages > Custom domain.

## Connect the sign-up form
1. Go to web3forms.com, enter the email where you want sign-ups sent, and get your **access key** (free: 250 submissions a month).
2. In `index.html`, search for `PASTE_YOUR_WEB3FORMS_ACCESS_KEY_HERE` and replace it with your key (it is meant to be public).
3. Do a test sign-up. You should get an email.

## Before launch
- Edit `privacy.html` (replace the contact email, read the draft).
- The text message updates checkbox was removed. Add it back only with a plan to collect clear consent.
- Signatures only arrive by email. For a spreadsheet or email list, add each sign-up to a free Google Sheet or Mailchimp/Brevo list.
- There is no live signature counter or public name list on this version.
