# Project 2: Regression
###### Metis — Fall 2019 NYC Cohort — Weeks 2 and 3
---
## Assignment Description
### Backstory:

Using information we scrape from the web, build linear regression models from which we can learn about movies, sports, or other categories.

#### Data:

 * **acquisition**: web scraping
 * **storage**: flat files
 * **sources**: (as listed below or any other publicly available information)   
  - movie: boxofficemojo.com, imdb.com   
  - sports: sports-reference.com
  

#### Skills:

 * basics of the web (requests, HTML, CSS, JavaScript)
 * web scraping
 * `numpy` and `pandas`
 * `statsmodels`, `scikit-learn`


#### Analysis:

 * linear regression is required, other regression methods are optional


### Deliverable/communication:

 * organized project repository
 * slide presentation
 * visual and oral communication in presentations
 * write-up of process and results


#### Design:

 * iterative design process
 * "MVP"s and building outward
 * [stand-ups/scrums](https://en.wikipedia.org/wiki/Scrum_(software_development)) (1 minute progress updates to the class)

---

## My Design draft

#### Question/need: 
As a tabletop game developer, what can I do to raise the maximum amount of money for my next tabletop game project with a crowdfunding campaign on Kickstarter?

#### Description of my sample data:
I scraped data about projects in the Tabletop Games category from Kickstarter search results, as well as corresponding project, rewards, and creator pages.

I also pulled descriptive data about the games from BoardGameGeek's API.

#### Characteristics of each entity:
TODO
    
    
---

_Keeping in mind the common sense:_
> ### Being a data scientist, the real sh*t:
> * Data scientists in real life have multiple goals that fit under the
  general category of "making sense of data" or "turning data into
  insights".   
>   * Often we are focused on building a predictive model, and on
    maximizing the predictive model's accuracy. Sometimes this focus
    is overemphasized. This is a thing that we do, but this is not the
    only thing.
 >     * Things that fail are often still interesting insights.
 >     * Anecdotes are often interesting insights.
 >     * The utility of an analysis is independent of the sophistication
      of the algorithm. Sometimes the most mind-blowing insights come
      from lists, tables, histograms, or scatter plots. Don't throw
      out cool stuff that isn't technically advanced unless absolutely
      necessary.
 >       * Don't over-design and under-deliver. For every data science
        project that you see or hear about, the version in the data
        scientist's head was probably fancier, bigger, more
        comprehensive, more elegant, presented in a cooler format, or
        with better copy, et cetera, ad nauseum. The reason you heard
        about it at all, however, is because it was *finished*, and
        published or released in all its heart-wrenching
        imperfection.
 >       * Start with something small, and build from there, as
        necessary, as time allows.
 >       * Jot down the elaborations, next steps, uh-ohs, or grand
          ideas that strike you as you are working. Leave them alone
          for a while and then come back and look at them later.
 >         * Many things that feel like huge "uhoh"s in the heat of the
            moment are actually small deals or even false alarms. The
            fewer of these you spend time on, the better.
