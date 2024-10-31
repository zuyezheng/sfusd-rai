## SFUSD School Metrics

SFUSD was not really forthcoming with their data behind the closures and [Resource Alignment Initiative](https://www.sfusd.edu/resource-alignment-initiative), only releasing the final "composite" scores and the relative ranks of the components. They even turned of copy and paste in the doc with the scores. The detailed data around enrollment, test scores, and demographics is often hard to find across CA data portals and random PDFs. 

Combined several sources and [modeled](/notebooks/processing/ComponentScores.ipynb) the component scores to see what an equally weighted composite score might have looked like compared to the current (.5 * equity + .25 * excellence + .25 * efficiency). 

Final data is in [component_scores_augmented.csv](/data/processed/component_scores_augmented.csv).

You can also play around with it in [Interactive Dashboard](https://app.hyperarc.com/?isEmbed=true&embedId=68a7fcc6-9fcc-4b13-84ec-594a75368745#/hyperarc/sfusd/dashboard/sfusd-overview) (you can build custom analysis by [logging in](https://app.hyperarc.com/) and searching for the `SFUSD Schools` dataset).

![Dashboard](/dashboard.png)