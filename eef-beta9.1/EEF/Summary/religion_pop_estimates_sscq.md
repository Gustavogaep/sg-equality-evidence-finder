* In `r graphData$Year[1]`, Christian (Church of Scotland, Roman Catholic and Other Christian) represented `r filter(graphData,Breakdown%in%c("Church of Scotland","Roman Catholic","Other Christian"))$Figure %>% sum %>% round`% of the adult population.
* Over the past decade there has been an increase in the proportion of adults reporting not belonging to a religion, from 40% in 2009 to just under a half of adults (`r filter(graphData,Breakdown=="None")$Figure %>% round`%) in `r graphData$Year[1]`.
* There has also been a corresponding decrease in the proportion reporting belonging to 'Church of Scotland', from 32% to `r filter(graphData,Breakdown=="Church of Scotland")$Figure %>% round`%.

