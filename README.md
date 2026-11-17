# Savings Plan

A personal savings and budget dashboard that runs in the browser. Set a monthly budget, tick off bills each month, log side income, and watch your savings grow. The plan starts at 12 months, and you can add another 12 whenever you need more.

## Getting started

1. Open the link to this page in Safari, Chrome or Edge.
2. Fill in the short setup: your name (optional), currency, first month, monthly take-home pay, and how much you want to save and keep in reserve each month.
3. On the **Plan** tab, type an amount next to each bill. You can rename or remove any item, or tap **+ Add item** for anything that's missing (including bills paid in US$, £, € or CA$).
4. Each month, open the **Month** tab, flip the switch as each bill is paid, and type an amount only if it was different from the budget.

## Add to your phone's home screen

- **iPhone:** open the link in Safari, tap Share, then **Add to Home Screen**.
- **Android:** open the link in Chrome, tap the ⋮ menu, then **Add to Home screen** (or **Install app**).

## Where your data is kept

Everything you enter is saved in your own browser on your own device. It isn't sent anywhere and nobody else can see it, including whoever runs this page.

- **Export backup** (Plan tab) downloads a copy of your plan. **Import** restores it.
- To use the plan on both your phone and your computer, turn on **Sync between phone and computer** on the Plan tab. It uses a private gist (a hidden note) in your own free GitHub account. Do this once on each device:
  1. On github.com, go to **Settings → Developer settings → Personal access tokens → Fine-grained tokens → Generate new token**.
  2. Under **Account permissions**, set **Gists** to **Read and write**. Leave everything else off.
  3. Copy the token, paste it into the Sync box, and tap **Connect**.
  On a second device, tap **I already use this on another device** during setup, then connect the same token.

## When the 12 months are up

Near the end of the plan, a banner offers **+ Add 12 months**. The same button is on the Plan tab under **Your plan**. Your budget carries over, everything you've logged stays, and your savings goal goes up by another 12 months of savings.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole app |
| `manifest.json` | App name and icons for home screens |
| `icon.svg`, `favicon.ico`, `favicon-16.png`, `favicon-32.png` | Browser tab icons |
| `apple-touch-icon.png`, `icon-192.png`, `icon-512.png` | Home-screen icons |

## Hosting it on GitHub Pages

1. Create a new repository and upload all the files in this folder.
2. Go to **Settings → Pages**, set the source to the `main` branch, root folder, and save.
3. After a minute or two, the app will be at `https://<username>.github.io/<repository>/`.
