# Check, please!

Use this Quarto dashboard to check how well the content on a webpage matches the Wikipedia page that most closes matches its topic.

See an example rendered at: <https://juliasilge.github.io/check-please-llm/>

Some example URLs to try:

- <https://childrenshealthdefense.org/defender/texas-health-officials-measles-budesonide-treatment/>
- <https://childrenshealthdefense.org/defender/cdc-study-possible-link-vaccines-autism/>
- <https://www.wired.com/story/federal-auditors-doge-elon-musk/>
- <https://www.motherjones.com/politics/2025/03/meteorologist-john-morales-doge-trump-cuts-weather-climate-forecasting-disaster-lives/>
- <https://www.dailykos.com/stories/2025/3/19/2311219/-Trump-slams-Canada-as-nastiest-country-while-fawning-over-Putin>
- <https://www.newyorker.com/news/q-and-a/mahmoud-khalils-constitutional-rights-and-the-power-of-ice>
- <https://phys.org/news/2025-03-dark-oxygen-deep-sea-discovery.html>

You can generate a dashboard for any URL with:

```sh
quarto render index.qmd -P input_url:https://www.newyorker.com/news/q-and-a/mahmoud-khalils-constitutional-rights-and-the-power-of-ice
```