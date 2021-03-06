# compjour-2018-project proposal

<h1>Less Schools, More Shootings?</h1>
<p>(working title)</p>

<h2>Elevator Pitch</h2>
<p>The link between education and proclivity to commit crimes has been well-established by researchers and sociologists. Many in law enforcement, government and social groups point to the importance of schooling as a factor in reducing crime.</p>

<p>What about in Chicago, Illinois often ranked as one of the most crime-ridden cities in the United States? The City closed nearly 50 schools in 2013, to the detriment of many community members and educators alike. My app will pair incidents of violent crime in Chicago with a map of schools that have been closed since 2013 to see if there is any link between increased crime and reduction of schools.</p>

<h2>Far vs. Near View</h2>

<p>Far view: a map that displays shooting incidents on or near schools in Chicago - specifically, near schools that have closed since 2013. Allows the user to filter shooting incidents by time of day, neighborhood, age of victim/shooter, school type and whether it is a fatal or nonfatal incident.</p>

<p>Near view: tables listing each shooting incident for each school that has closed since 2013. The table will contain similar information as the interactive map (location, time of day, age of victim/shooter, fatal or nonfatal incident, school type) but will be separated by each school rather together in one map. Separately, the user could also select to view all shooting incidents in a table-view for a certain filter: location, time, age of victim/shooter, fatal/nonfatal incident, and school type (elementary, middle or high).</p>


<h2>Inspirations and prior work </h2>
<a href="https://graphics.stltoday.com/apps/crime/index.html">St. Louis Crime Tracker</a> 
<p>This web app shows year-over-year change for crime incidents in the city of St. Louis, organized by neighborhood. The app allows the user to choose to view crimes by type (violent or property) and choose year-over-year change or per-capita incidents. It is fairly straightforward and provides a sense of which neighborhoods experience the most crime and which have the highest changes.</p>

<a href="http://graphics.chicagotribune.com/school_utilization/">School Board votes to close 49 schools</a> 
<p>This map of the Chicago area displays the locations of every school that was voted to close in 2013. It allows the user to pair the location of closing schools with poverty rates, population of school-aged children, and elementary school attendance boundaries. It also provides detailed information about the utilization rates, performance levels and ISAT scores (standardized testing) of the schools in question.</p>

<a href="http://www.chicagotribune.com/news/data/ct-shooting-victims-map-charts-htmlstory.html">Chicago Tribune's Shooting Victims Map</a> 
<p>Chicago, notorious for its gun violence, provides robust crime data that reimagines the way we can perceive the city. One visualization that I like on this page, which provides several charts and tables with shooting data, is the heatmap of where shootings occur. I think that being able to see the map provides a good understanding of the prevalence of violence in certain neighborhoods. </p>

<a href="https://everytownresearch.org/gunfire-in-school/">Gunfire in school</a>
<p>This interactive map displays every shooting incident that has occurred on school grounds in the United States since 2013. It allows the user to select to view the shootings by year or cumulatively. Upon choosing a shooting incident, the app displays the date, location, region, description and outcome of the shooting. I like that this is very simple in that it only shows the individual incidents and descriptions over a time filter.  </p>

<a href="https://projects.fivethirtyeight.com/simplified-gun-deaths/">Gun deaths in America</a>
<p>This data viz by 538 focuses on all gun deaths in the United States, regardless of location or motive. I appreciate that the app guides you through anecdotal information about the data, such as women who have been gun homicide victims, the number of black men shot, and data about suicides. But it also allows the user to explore the data by filtering for causes, gender, age and race. It is a straightforward app that uses pixels to represent the number of victims for a specific field.</p>

<ul>
<li>The main thing that will differentiate my app from the others is that none of these pair location of the closed schools with crime incidents. Each app focuses on one metric: shooting/crime incidents or demographic/geographic location of the schools that closed. Mine will attempt to pair the two in order to provide more context.
<li>While I appreciate STLTODAY's graphic on year-over-year change, I wish it provided a tooltip that gave more information about that neighborhood: population and median income, to start. My app would provide the following data points: attendance rates, number of crime incidents, population and median income. I think even knowing this simple information could give more insight into differences between neighborhoods.</li>
<li>Whereas the Chicago Tribune provides several data charts to display their information, I think it is easy to get lost on that page because of the sheer amount of information they provide. I would like to make my app more streamlined, in that it consists mainly of a map and tooltips, along with a written section under the map for explanation.</li>
<li>Finally, I want to take advantage of the up-to-date data available for both attendance rates and crime incidents. Data for crime incidents in Chicago are regularly published and available, as is information about the CPS that closed since 2013. To my knowledge, a web-app based on these data does not exist currently.</li>
</ul>

<h2>Articles</h2>
<a href="http://articles.chicagotribune.com/2013-02-19/news/ct-met-prison-truancy-20130219_1_much-school-public-schools-grades">Court files show link between school truancy and crime</a> <p>This story highlights prison data that links school absence in early childhood with higher rates of incarceration. According to the article, absenteeism is a growing problem in Chicago public schools, which may have a relationship with the city's high violent crime rate. Anecdotally, many prisoners attribute lack of education and schooling with their behaviors that landed them in prison.</p>

<a href="http://www.bbc.com/news/stories-42254527">School attendance and absence: the facts </a> <p>This article, while based in the U.K., looks at the reasons that students miss school, ranging from sickness to depression to boredom. It also compares the levels of absenteeism with income, crime and health levels, and found the link between truancy and other factors not as strong as previously considered.</p>

<a href="http://www.nbcnews.com/id/33200246/ns/us_news-education/t/school-closings-root-chicago-teen-violence/#.Wwg1AC-ZP-Y">School closings root of Chicago teen violence?</a> <p>While this is a dated article, it explores the link between closing schools that lead to students being put into schools outside of their neighborhoods. In Chicago, where gang violence is rampant, this often causes teens in rival gangs to be put into the same school environment which sometimes exacerbates the violence. The story also provides information that shows how fatal shootings increased as the number of school closures increased between 2006-2007.</p>

<a href="https://www.theatlantic.com/education/archive/2015/12/reimagining-abandoned-schools/418311/">Reimagining abandoned schools</a>
<p>While this article focuses on what happens to the educational spaces after they are closed, it touches on the important role that schools have. They aren't just places for youth to learn; in rural, urban and suburban areas alike, schools tend to serve as community centers. So when a school does close, it often causes "grief and upheaval" in the community it existed. I extrapolate from this article that the widespread school closures in Chicago have had similar effects: a sense of loss. The article also picks up on the fact that because of the school closures in Chicago, children have been forced to cross through gang territory to get to their new schools.</p>

<h2>Data sources</h2>

<a href="http://graphics.chicagotribune.com/school_utilization/">School board votes to close 49 schools</a>

<a href="http://www.dnainfo.com/chicago/20130321/chicago/cps-school-closings-list/">CPS School Closings map; 54 to be shuttered</a>

<a href="https://www.crimereports.com/agency/chicago-police-department-il#!/dashboard?incident_types=Assault%252CAssault%2520with%2520Deadly%2520Weapon%252CBreaking%2520%2526%2520Entering%252CDisorder%252CDrugs%252CHomicide%252CKidnapping%252CLiquor%252COther%2520Sexual%2520Offense%252CProperty%2520Crime%252CProperty%2520Crime%2520Commercial%252CProperty%2520Crime%2520Residential%252CQuality%2520of%2520Life%252CRobbery%252CSexual%2520Assault%252CSexual%2520Offense%252CTheft%252CTheft%2520from%2520Vehicle%252CTheft%2520of%2520Vehicle&start_date=2018-05-11&end_date=2018-05-25&days=sunday%252Cmonday%252Ctuesday%252Cwednesday%252Cthursday%252Cfriday%252Csaturday&start_time=0&end_time=23&include_sex_offenders=false&lat=41.85345216355517&lng=-87.68815040588379&zoom=13&current_tab=list&shapeIds=">CrimeReports for Chicago</a>

<a href="https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2">Crimes 2001 to present</a>

<a href="https://data.cityofchicago.org/Education/Schools-deprecated-2012-/kqmn-byj8">Schools (deprecated 2012)</a>

<a href="https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Boundaries-Neighborhoods/9wp7-iasj">Chicago boundaries: neighborhoods</a>

<a href="https://data.cityofchicago.org/Public-Safety/Crimes-Map/dfnk-7re6">Crimes in Chicago: map</a>

<a href="https://www.census.gov/quickfacts/fact/table/chicagocityillinois/PST045216">Census facts Chicago</a>