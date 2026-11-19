# Example papers and their licences

Pier's example review ("Does sunlight make people happier?") uses four open-access papers. All four are published under a Creative Commons Attribution (CC BY) licence, which allows them to be shared and adapted with credit. The licence statement was checked inside each PDF.

| Id | Paper | Licence |
|---|---|---|
| P1 | Boubekri, M., Lee, J., MacNaughton, P., Woo, M., Schuyler, L., Tinianov, B., & Satish, U. (2020). The impact of optimized daylight and views on the sleep duration and cognitive performance of office workers. *International Journal of Environmental Research and Public Health, 17*(9), 3219. https://doi.org/10.3390/ijerph17093219 | © 2020 by the authors. Licensee MDPI. [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| P2 | Crouse, J. J., Park, S. H., Mitchell, B. L., Byrne, E. M., Medland, S. E., Lin, T., Scott, J., de Haan, Z., Tonini, E., Iorfino, F., Wray, N. R., Martin, N. G., & Hickie, I. B. (2025). Mental health and sleep correlates of self-reported outdoor daylight exposure in over 13,000 adults with depression. *European Psychiatry, 68*(1), e41. https://doi.org/10.1192/j.eurpsy.2025.20 | © The Author(s), 2025. Published by Cambridge University Press on behalf of European Psychiatric Association. [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| P3 | Zhang, W., & Li, W. (2025). How weather conditions affect well-being: An explanation from the perspective of environmental psychology. *Frontiers in Public Health, 13*, 1553315. https://doi.org/10.3389/fpubh.2025.1553315 | © 2025 Zhang and Li. Creative Commons Attribution License (CC BY), as stated in the article |
| P4 | Peng, Y.-F., Tang, J.-H., Fu, Y.-c., Fan, I.-c., Hor, M.-K., & Chan, T.-C. (2016). Analyzing personal happiness from global survey and weather data: A geospatial approach. *PLOS ONE, 11*(4), e0153638. https://doi.org/10.1371/journal.pone.0153638 | © 2016 Peng et al. [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |

## What was changed

- **`example-pdfs.js`** holds the four published PDFs, unchanged, encoded as base64 so the reader can show the original pages.
- **`example-text.js`** holds each paper's text, extracted with pdf.js and tidied for reading in the app: front matter, tables, figure captions, references and back matter were left out; section headings were added; spacing from the PDF text layer (ligatures, brackets, apostrophes) was cleaned up. No sentence was reworded.
- Inside the app, short passages are quoted with their page number, and the sample notes and hat lines respond to them. Those notes and lines are part of the prototype's fictional example, not the authors' views.

The papers are included only as example material for the prototype. Please cite the original articles, not this repository.
