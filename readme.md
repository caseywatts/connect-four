Workflow so far, sass watches for changes to main.css.scss, guard watches for any files in `.` or `./css` and reloads chrome when I make a change.

```
sass --watch css/main.css.scss:css/main.css
guard
```

This could go nicely in a single gruntfile, this is just what I had handy :)