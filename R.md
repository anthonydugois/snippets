## ggplot2

### Remove x axis details

```R
theme(axis.title.x = element_blank(),
      axis.ticks.x = element_blank(),
      axis.text.x  = element_blank())
```

### Remove legend

```R
scale_colour_discrete(guide = "none")
```
