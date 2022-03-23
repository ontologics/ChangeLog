<a name="2022.03.23"></a>
# 2022.03.23
## Features
* ### Watchlist Improvements
   * Watchlist creation form replace with a wizard for better usability. ![image](wwizard.png)
   * Added company relatedness.  ![image](watchlistrelatedness.png)

* ### New Plans
  * Added Free Watchlist Plan and Watchlist Plan ![image](plans.png)

* ### Submit Bug
   * If an error on a page id detected, a bug report will automatically be filed.
   * Users can submit bug reports by clicking "Submit Bug" in the user menu. 
   ![image](buglink.png)
   ![image](bugreport.png)

<a name="2022.03.01"></a>
# 2022.03.01
## Features
* ### Industry Report Improvements
   * Custom Industry by company updated to only use Technology Areas that make up 80% of the company's portfolio
   * Added Relatedness range slider to Custom Industry by Company, CPC Code, and Patent to allow user to specify how closely related the technologies in the custom industry are to the original selection. ![image](industryrelatedness.png)
   * Removed vague Technology Area from search results
* ### Technology Hierarchy Added
  * Ability to click on a technology to see the hierarchy, which allows for a better explanation of what the technology is, and how it relates to a Technology Area ![image](cpchierarchy.png)

## Bug Fixes
* Unsubscribe link in watchlist email does not work.


<a name="2022.02.17"></a>
# 2022.02.17 (Hotfix)
## Bug Fixes
- Spelling issues on <a href="https://portal.ontologicsdata.com/home/company">Home - Company</a> page.


<a name="2022.02.16.1"></a>
# 2022.02.16.1 (Hotfix)
## Bug Fixes
- Patent charts ignore date range and kind filters. Introduced in <a href="#2022.02.16">2022.02.16</a>

<a name="2022.02.16"></a>
# 2022.02.16
## Features

* ### Added <a href="https://portal.ontologicsdata.com/company/age">Company Age Report</a> ![image](https://user-images.githubusercontent.com/768768/154108677-20f9eb26-dab6-45ac-8759-dc8ff0edccd8.png)

   * Review the expected expiration of a portfolio
   * Find out how their expiration funnel stacks up
   * See which technical areas are set to expire sooner or later
   
## Bug Fixes
- Technology comparison charts not grouping companies in company reports. So only first selected company's average score was shown.

<a name="2022.02.08"></a>
# 2022.02.09 (Hotfix)
## Bug Fixes
- Lazy load `Description` and `Claims` fields in <a href="https://portal.ontologicsdata.com/patent/search">Patent Search</a> to alleviate timeout issue

<a name="2022.02.08"></a>
# 2022.02.08 (Hotfix)
## Bug Fixes
- Fixed bug in Filterbar that prevents users from adding a competitor to the <a href="https://portal.ontologicsdata.com/competitor/overview">Competitor Reports</a>


<a name="2022.02.08"></a>
# 2022.01.24 
## Features

* ### Added <a href="https://portal.ontologicsdata.com/watchlist">Watchlists</a> ![image](watchlistexample.png)

    * Get weekly/monthly/quarterly updates when new patent documents are published
    * Filter by company, keywords, countries, CPC codes, assertability, innovation, and value ![image](createwatchlist.png)

