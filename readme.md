Workflow for this project:
1. When `main.css.scss` is edited, `sass` notices and recompiles `main.css`
3. When any files in `.` or `./css` are edited, `guard-livereload` notices and tells the [LiveReload Chrome Extension](https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei?hl=en) to refresh the browser tab for me.

In different terminal tabs, I run:
```
sass --watch css/main.css.scss:css/main.css
guard
open index.html
```

This workflow could go nicely in a single gruntfile and the single command `grunt`, but this is just what I had handy :)