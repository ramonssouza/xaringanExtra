# xaringanExtra 0.0.19 (2020-07-22)

* Increased specificity of CSS rules for the panelset.

* Added `--panel-tab-background-color` with additional `-active` and `-hover`
  custom properties to style the background color of tabs. Similarly, two
  CSS variables for border color were added: `--panel-tab-border-color-active`
  and `--panel-tab-border-color-hover`.

* Updated Tachyons to 4.12.0 (#27)

* Added **clipboard** extra with `use_clipboard()`. Adds a "Copy Code" button
  to code chunks (`<pre><code>...</code></pre>`) and works in both xaringan
  slides and R Markdown documents (thanks @mattwrkentin #20, #36).

# xaringanExtra 0.0.18 (2020-07-16)

* Improved accessibility of panelset so that it now works with touch devices.
  The currently selected tab is written into the URL query to ensure that URLs
  resolve to currently open tab. The tab ID isn't written into the URL hash
  because this is used by remarkjs to jump to the current slide. (#34, #33, #18)

* Added a `NEWS.md` file to track changes to the package.

# xaringanExtra 0.0.17 (2020-07-09)

* [_Your slides are so extra!_ (useR!2020)](https://youtu.be/vZMuu77ocMY)

* `text_poster()` has been deprecated and will be removed eventually.
