# SpreadsheetFormulasReadable
Beside your spreadsheet cells, have a synchronized listing of the content of the cells?

Any programmer will tell you code listings are MUCH better for getting an overview instead of having to manually click every cell (including the thousands you think have no content; or at least scrolling past them). Quickly typing some numbers in a grid also can be quite powerful however. Why not do both, synchronized? You click a cell and the listing is scrolled to the first mention of it, or creates the first mention. There's some reactive coding under the hood of spreadsheets, that 'keeps count' of what comes first for calculation anyway, so there is an order of things somewhere already.

Cells only would provide a view, in which you can select cells. Code and data can however be also defined in this code listing immediately without attaching it to a cell.

Maybe this would also a basis for something else: take the cells out of the grid, into a graph, where arrows show use of variables.

How to implement:
- Make it inside of [E2D3](https://e2d3.org) (has JavaScript references to cells in Excel-embedded web browser), or as an Excel extension like E2D3 is.
- If the above doesn't work, try this route through R: https://mobile.twitter.com/steltenpower/status/1330290665322934278

Also look at:
- [Deep Spreadsheets](https://gitlab.com/muishkin/mwnci---deep-spreadsheets/)
- https://blockpad.net/
- https://observablehq.com
- See how far you can get with Jupyter
- Microsoft must have something like this. Can you tell me? VBA? Though I strongly prefer open source.
