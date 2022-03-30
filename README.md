# Spreadsheet-SourceCode
![stopPeepholing](https://repository-images.githubusercontent.com/206755968/aeb9f700-bfde-11eb-87af-516894842592)
Spreadsheets can show the output of many cells, but the formula of only 1. That's like looking through a peephole, instead of proper coding.
I propose to no longer show formulas exclusively 1-on-1 per cell, but in some sort of code view besides the sheet.
And why stick to only 1 source view; pick whatever you like: cells, linear text, graph


How to implement:
Seems done: https://towardsdatascience.com/interactive-spreadsheets-in-jupyter-32ab6ec0f4ff and https://github.com/mito-ds/monorepo#-mito-monorepo


otherwise:
- Make it inside of [E2D3](https://e2d3.org) (has JavaScript references to cells in Excel-embedded web browser), or as an Excel extension like E2D3 is.
- If the above doesn't work, try this route through R: https://mobile.twitter.com/steltenpower/status/1330290665322934278


Also look at:
- Excel doing Lambda, or User Defined Functions nowadays.
- [Deep Spreadsheets](https://gitlab.com/muishkin/mwnci---deep-spreadsheets/)
- https://blockpad.net/
- https://observablehq.com
- See how far you can get with Jupyter
- Microsoft must have something like this. Can you tell me? VBA? Though I strongly prefer open source.
