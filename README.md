# FreeAgent invoice template

Minimal invoice template for [FreeAgent](https://freeagent.com), as used by [SB-PH](https://sb-ph.com). Typeset in Courier: one weight, one size.

## Getting started

Make sure [Sass](http://sass-lang.com) is installed on your system, then:

```
sass --watch --sourcemap=none custom.scss:custom.css
```
Then, copy the output into FreeAgent’s custom invoice theme CSS area.

## Notes

- `::first-letter` selector not supported by FreeAgent’s PDF generator
- General sibling selectors (`~`) not supported by FreeAgent’s PDF generator
- FreeAgent won't render a PDF with `font-size: 0;`
- Use selector `#invoice[data-url*="estimates"]` to target estimates specifically. `#invoice[data-url*="invoices"]` for invoices, etc.
