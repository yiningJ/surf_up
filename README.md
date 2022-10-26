# surf_up

## Overview of Project
### Purpose
After providing analysis on weather information about active stations, W. Avy would like to see more relationship between date and temperature to help him prepare for the surf shop opening. We will be showing information in June and December to help him better understand if the surf and icecream shop is a good business to run all year round in Oahu.

## Results
### Three key differences
- On average June has a slightly higher temperature than December in Oahu (about 6F difference).
- Minimum temperature in December is much lower than June (about 8F difference). 
- Maximun temperature in December is not much different with June (about 2F difference).

## Summary
On average both months are not hot enough for people to comfortably consume icecream and go surfing. And the lowest temperature in both months are way too low for summer activities.
additional queries:/
df = pd.DataFrame(results, columns=['date','Temps'])
df.set_index(df['date'], inplace=True)
df = df.sort_index()
df.plot()
