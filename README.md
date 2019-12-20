# my-sass-issue

Clone and run `npm install` to get sass and Foundation Sites.

Run the sass script via npm:
```
npm run sass
```

The `css/app.css` output file should contain css from the Foundation Sites scss file `/node_modules/foundation-sites/scss/foundation.scss`, which simply imports all of the Foundation Sites items. It includes the comment banner from that file, but nothing else. :-(

**Update:**
Fixed by changing the `--load-path` from `/node_modules/foundation-sites/scss` to `/node_modules/foundation-sites/assets` as suggested by a user here: https://stackoverflow.com/questions/59417133/dart-sass-ignores-imports-in-foundation-sass-files
