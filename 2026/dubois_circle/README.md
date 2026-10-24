# Species of Frogs and Toads

A [TidyTuesday](https://github.com/rfordatascience/tidytuesday) project (week of 2026-10-13), drawn in the manner of W.E.B. Du Bois.

![Spiral chart of the six largest frog and toad families](frogs_spirale.png)

## About

The chart shows the six largest families of frogs and toads by number of species as a spiral. Each ring is one family, and the length of the ring is proportional to its number of species. The hatching is generated in R to imitate coloured pencil on paper, and the page is styled as a diary sheet with a burnt top edge.

| Family | Species |
|---|---|
| Hylidae | 1086 |
| Strabomantidae | 840 |
| Microhylidae | 768 |
| Bufonidae | 666 |
| Ranidae | 470 |
| Rhacophoridae | 467 |

## Data

The data come from AmphibiaWeb via TidyTuesday (2026-10-13). The Quarto document loads them directly from the TidyTuesday repository, so no data file is needed here.

## Files

- `frogs_amphibiaweb.qmd`: Quarto document with the data preparation, the chart and the page layout
- `logo1.png`: background image used by the page
- `frogs_spirale.png`: the finished chart

## How to reproduce

1. Open `tidytuesday.Rproj` in RStudio.
2. Install the required packages: `tidyverse`, `showtext`, `sysfonts`.
3. Open `frogs_amphibiaweb.qmd` and click **Render**. An internet connection is needed to load the data and the Google fonts.

## Credits

Data: AmphibiaWeb, via TidyTuesday. Design inspired by the data portraits of W.E.B. Du Bois. Design and coding in R and Quarto.
