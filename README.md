*FreeAgent invoice template*

Simple invoice template for [FreeAgent](https://freeagent.com) typeset in Courier, one weight, one size. Written in Sass, for convenience.

Notes:

- `::first-letter` selector not supported by PDF generator
- General sibling selectors (`~`) possibly not supported in PDF generation
- FreeAgent won't render a PDF with `font-size: 0;`
- Use selector `#invoice[data-url*="estimates"]` to target estimates specifically. `#invoice[data-url*="invoices"]` for invoices, etc.
