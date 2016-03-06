# GIS
This is a collection of various GIS maps created using QGIS, GeoDa, and R.

## *Race & Self-Reported Health*
I created these maps for a project about health disparities in black and white populations in the US.  The "about" sections below are excerpts from my paper.

### About the project:

Racial discrimination, defined as being treated unfairly because of one’s racial characteristics (Dovidio & Gaertner, 1986), is arguably one of the largest problems facing the United States today (Johnson, 2006).  Racial discrimination has many negative effects, one of which is that it is associated with an exceedingly high number of disparities in health outcomes for people of different races (e.g., Galea, Tracy, Hoggatt, DiMaggio, & Karpati, 2011; Krieger & Sidney, 1996; Landrine & Klonoff, 2000; Massey, 2004; Mays, Cochran, & Barnes, 2007; Nelson, 2006; Williams & Jackson, 2005).

Many studies have investigated the effects of racism on observable, physiological health measures (e.g., Krieger & Sidney, 1996; Landrine & Klonoff, 2000; Massey, 2004) as well as self-reported feelings about health (Brondolo et al, 2011).  In fact, self-reported general health measures are highly correlated to physical measures of health, such as chronic disorders and acute life-threatening conditions (e.g., Brondolo et al., 2011).  I would like to further investigate how race and geography may impact self-reported general health scores.

This paper first gives an overview of how racial inequality can cause poorer health outcomes in black populations.  The two main categories addressed are larger systemic inequalities, such as segregation, and more micro-level racial discrimination experiences.  The present analyses focus on the relationship between self-reported healthiness, race, and geographical location within the US, by state.  I conduct a number of exploratory analyses, including a spatial regression to see if the percentage of black residents in each state predicts the state’s average self-reported health score.  Results show that there are significant spatial differences in black populations, health scores, and the relationship between the two, varying by state in the US, but my main hypothesis is not fully supported.

### About the data:

I used publically available data from the November 2012 Gender and Generations Survey, which was sponsored by the Pew Social & Demographic Trends Project (Princeton Survey Research Associates, 2012).  The survey was conducted between November 28 and December 5, 2012, and 2,511 adults living in the U.S. were interviewed via landline (nLL=1,506) and cell phone (nC=1,005; including 509 without a landline phone).  The sample is representative of the U.S. and known demographic discrepancies in that data have been corrected for with statistical weights (the margin of sampling error for weighted data is ±2.2 percentage points).  With the weighted data, I believe it is suitable to compare the data from this dataset to U.S. Census data, since both are representative of the U.S. population.  I used this data set to operationalize my dependent variable, general health.

I also used publically available data from the U.S. Census Bureau’s American Community Survey (ACS) (U.S. Census Bureau, 2011).  I chose to use five-year population estimates (2007-2011) of race distributions by state to operationalize my independent variable, race.

I used publically available cartographic boundary files from the U.S. Census Bureau, as well (U.S. Census Bureau, 2013).  Specifically, I used the 2013 U.S. state-level TIGER/Line shape files for all of the spatial analyses in this paper.  I did not include Hawaii, Alaska, Puerto Rico, Guam, and the U.S. Virgin Islands in my analyses because they are, geographically, very far away from the U.S. mainland, which would affect the spatial analyses unfittingly.

## *US Home Values*

I created these maps for a class project that posed a hypothetical research question in which we were asked to explain variations in home values across the US (at the county level).  We were given the following variables with which to work: percent of population with a Bachelor's degree, percent of population in poverty, percent of population living in a rural area, and the percent of the population that is white.  We were asked to examine the relationships between these four variables and home values as well as explore the data for global spatial dependence and local non-stationarity.





