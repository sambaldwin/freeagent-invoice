Simple monospaced FreeAgent template. Set in Courier.

Make sure [Sass](http://sass-lang.com) is installed on your system, then:

```
sass --watch --sourcemap=none custom.scss:custom.css
```

Notes:

- `::first-letter` selector not supported by FreeAgent’s PDF generator
- General sibling selectors (`~`) not supported by FreeAgent’s PDF generator
- FreeAgent won't render a PDF with `font-size: 0;`
- Use selector `#invoice[data-url*="estimates"]` to target estimates specifically. `#invoice[data-url*="invoices"]` also works.
