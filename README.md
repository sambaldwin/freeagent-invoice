Notes:

- Use selector `#invoice[data-url*="estimates"]` to target estimates specifically. `#invoice[data-url*="invoices"]` also works.
- `::first-letter` selector not supported by PDF generator
- FreeAgent won't render a PDF with `font-size: 0;`
- `~` adjacent sibling selectors not supported in PDF generation
