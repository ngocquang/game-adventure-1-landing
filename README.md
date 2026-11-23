# 4DAD — landing page

The public website for the game 4DAD: The 4D House. It has the game page, the Privacy Policy, the Terms of Use and the Support page.

Live site: https://ngocquang.github.io/game-adventure-1-landing/

| Page | URL |
|---|---|
| Home | [/](https://ngocquang.github.io/game-adventure-1-landing/) |
| Privacy Policy | [/privacy.html](https://ngocquang.github.io/game-adventure-1-landing/privacy.html) |
| Terms of Use | [/terms.html](https://ngocquang.github.io/game-adventure-1-landing/terms.html) |
| Support | [/support.html](https://ngocquang.github.io/game-adventure-1-landing/support.html) |

## Stack

Plain HTML and CSS. No JavaScript and no build step. GitHub Pages serves the `main` branch.

## Preview locally

```
python3 -m http.server 8080
```

Then open http://localhost:8080.

## Store buttons

The game is not in the stores yet, so the two store buttons are not links. After the release, change each `<span class="store is-soon">` in `index.html` to `<a class="store" href="..." rel="noopener">` and change the small label to "Download on the" or "Get it on".

- App Store: `https://apps.apple.com/app/id<APP_ID>`. Add `<meta name="apple-itunes-app" content="app-id=<APP_ID>">` to the head.
- Google Play: `https://play.google.com/store/apps/details?id=com.nuna.fordad`.

## Screenshots

The images in `assets/img` come from the game repository. `tools/store-shots.sh` captures them into `docs/publish_android/screenshots/US/phoneScreenshots`.

## Fonts

Be Vietnam Pro and Patrick Hand, under the SIL Open Font License 1.1. The website serves the files from `assets/fonts`.
