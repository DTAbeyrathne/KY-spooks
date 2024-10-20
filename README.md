# Haunted Kentucky: Ghostly Visitations

Welcome to spooky Kentucky This eerie map was created to illustrate the locations of all documented (to-date) haunted locations in Kentucky, which include any place that has anecdotally been recorded to have strange, unexplained occurences, including shadowy figures, disembodied voices, unexplained physical feelings, visual anomalies, and apparitions (among many other reported paranormal experiences). Since it's near Halloween, I decided to create a fun, spooky map for the season showing various hauntings around Kentucky. I'm quite interested in the stories of paranormal experiences, which fueled my desire to map these locations in Kentucky. Additionally, I created a similar map a few years ago illustrating popular haunted and abandoned locations in Kentucky. That map only featured five haunted locations, and I've always wanted to expand on it. Thus, this project was born!


## Haunted Sites Data Sources

The majority of haunted sites was compiled using information from [Kentucky Haunted Houses](https://www.kentuckyhauntedhouses.com/real-haunts/).Supplementary data for the Kentucky State Penitentiary, Camp Taylor, Sleepy Hollow Road, and Asbury Cemetery were sourced from these sites: 

* [KY State Penitentiary & Camp Taylor](https://kyforky.com/blogs/journalh/haunted-places)
* [Sleepy Hollow Road](https://www.kentuckybb.com/Blog/Get-Haunted-and-Go-Ghost-Hunting-in-Kentucky.html)
* [Asbury Cemetery](https://www.fourriversexplorer.com/asbury-cemetery-unusual-sights-ghostly-tales/)

Additional sites in Lexington and Kentucky were sourced from these sites:
* [Haunted Rooms (Lexington, Kentucky)](https://www.hauntedrooms.com/kentucky/lexington/haunted-places)
* [Haunted Rooms (Kentucky)](https://www.hauntedrooms.com/kentucky/haunted-places)

In rechecking my hauntings list, I referenced these Reddit threads to read about additional potentially haunted areas that I may have missed in my initial research:

* [Does anyone know of some haunted places in Eastern Kentucky? Particularly in the Pike/Letcher/Perry area?](https://www.reddit.com/r/Kentucky/comments/qxhrms/does_anyone_know_of_some_haunted_places_in/)
* [Looking for some haunted areas in Kentucky?](https://www.reddit.com/r/Kentucky/comments/c000hk/looking_for_some_haunted_areas_in_kentucky/)

All of this data was compiled on a spreadsheet in Microsoft Excel, with colums for place name, location (city), hauntings (reported paranormal experiences, simplified), and a unique ID for each site. It was then saved as a .csv (comma separated values) file for use in QGIS.

You can download the entire haunted data compilation here: <a href="data/KY_haunted_places.csv.js" download>KY_haunted_places.csv</a>


## Other Data Sources

Data for the Kentucky state and county polygon data was sourced from the [U.S. Census Bureau](https://www.census.gov/cgi-bin/geo/shapefiles/index.php). Kentucky roads and river data was sourced from [Natural Earth Data](https://www.naturalearthdata.com") (1:10m scale). Lastly, the ghost raster image used to mark haunted locations was sourced from my previous spooky mapping project, which is the inspiration for this one. All data was clipped using the extent of Kentucky's state polygon.


## How the Map was Made

### 1. The Basics

The spooky adventure began with extensive research into Kentucky's haunted locations, with the intent of documenting every possible haunted location as I could along with their respective coordinates. I was lucky to find a compilation of 76 haunted locations in the Kentucky Hauted Houses website, which saved me quite a lot of time. Although I had to supplement that source with several others, it gave me a significant head start.

I began by creating an Excel spreadsheet to record my findings. It has six columns:
1. Place_name --> the site's name
2. Location --> the city/town it is located in
3. Haunt:
4. Lat_coord_x --> the site's x-coordinate
5. Long_coord_y --> the site's y-coordinate
6. Unique_ID --> a unique numeric identifier given to each site

This step took approximately 5-6 hours as I had to scour the documentations to codify paranormal experiences and note down coordinates (after checking their accuracy). Despite the time it took to compile this data, it was a lot of fun learning about each site's spooky personality!

### 2. Getting the Supplementary Data




# Project title (10 points)
Information about data source (10 points)
# Link to the data source, if applicable, or a copy of the full data source for download (10 points)
Markdown formatting throughout the document (10 points)
# Description about why you created the map (10 points)
Description about how the map was created, including any geoprocessing methods or other steps you took described in a way that someone else could try to recreate your map process in a new location (30 points)
Active link to the final index.html page (20 points)
Include embedded images, as needed, to document the mapping process, including key data management or geoprocessing steps and settings (20 points)
Information about the projection of the original data and the projection for the final data (10 points)