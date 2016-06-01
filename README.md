Notes:

- `::first-letter` selector not supported by PDF generator
- General sibling selectors (`~`) not supported in PDF generation
- FreeAgent won't render a PDF with `font-size: 0;`
- Use selector `#invoice[data-url*="estimates"]` to target estimates specifically. `#invoice[data-url*="invoices"]` also works.
