# MiniProject2
Expected Runs (baseball) and Expected Goals (Soccer)

The first part of this project was to calculate expected runs in baseball based on the 2021 season. The runs are calculated for each base runner / out situation, and summarized in the table in the pdf document. After this, I investiaged the top players based on runs created, comparing my metric to fangraphs WAR metric.

For the soccer analysis, the goal was to create an xG model and compare it to the statsbomb xG. The data contains information on 12,000 shots from La Liga games, and many different xG models were fit. The best models were xG boost and random forest models, having an MSE of just 0.012. Details for these models can be found in the markdown or pdf. Results are then summarized pointing out the top players based on the number of goals scored above expected goals (Lionel Messi) overall and then broken down by long shots, free kicks, short shots, headers, etc. 

A couple working markdown documents are also uploaded, but full details can be found in the FinalMiniProject2.rmd file. Data can be found in the compressed zip data folder.
