# UX Meetup
Dear UX geniuses, Sophicware wants to turn OpenData into Information ingestable by everyone. 

## Sophicware's Problem Scope
One of Sophciware's goals is to make OpenData more accessible to everyone. The effort requires leaning one the established field of Journalism acting as the conduit. I desire an experience where it is easy for anyone to search for datasets, filter search results and emded the any one of the returned data visualizations into online articles, blog posts, etc.

Any experiences devised should assume the use of a mobile device.

## Personas

1. General Population Persona
2. Journalist Persona

The only difference between the experences of the two personas is that the Journalist persona will further interact with a data visualization and be presented with an embed code.

### Usage

1. User visits web page containing a search box
2. User types a query
3. User is presented with a page of data visualizations
4. User interacts with the visualization to reveal additional details about the dataset
5. (Journalist Persona Only) Given some gesture, the User is presented with an embed code

## Search Queries
Samples:

- Parks in New York
- Elections results in Nashville during 2016
- Wifi locations

We've released an open source library

## Search Results
Search results from Sophicware's server will contain data visualizations.

- all data visualizations will have supporting text (chart headings, and axises)
- there will be a diverse set of chart types: eg. trend, map, scatter plot, etc
- Data visualizations returned in search results may vary in height
- Data visualizations returned in search results will be filterable by geography, chart type, year of creation/update.


## Advice: Go Wild. Push the limits.

1. Given this is a mobile-first experience, feel free to experiment with additional mobile gestures such as, long press, swipe left, swipe right, etc.
2. Consider data visualizations being full or half width of a mobile screen.
3. Animations are ok, if they are sensible non-animated fall backs.
4. When typing a search query, does a search _box_ need to exist?
5. Can "additional information" for each data visualization be hidden?
