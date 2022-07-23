# LabelRemap

R package to 'best' remap cluster labels to ground truth by assessing accuracy of each permutation.

## Installation
```
library(devtools)
install_github("StirlingCodingClub/SCC_R_package");
```

## Usage
`labels <- labelremap(clustering_labels, true_labels)`

Returns the remapped clustering_labels. You could then pass to the caret package `confusionMatrix(labels, true_labels)` function to assess clustering performance.

## License
[MIT](https://choosealicense.com/licenses/mit/)