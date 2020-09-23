# UFOs Analysis
Analysis of UFOs
Overview:
Dana wants to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, need to add table filters for city, state, country and shape. I will be creating a dynamic table with filters that will react to user input, and then place the table into a HTML file to view and read easily by her viewers.
Hypertext Markup Language (HTML) is the standard markup language for documents designed to be displayed in a web browser. It can be assisted by technologies such as Cascading Style Sheets (CSS) and scripting languages such as JavaScript.

Results:
search by date: 
Search by date will show all the results by date which shows all dates, cities, states, countries, shapes and durations.

Search by dates and city: 
The search with cities and dates will show results only that are related to both categories.

Search with date and state: 
The date and state search will only show the results which indicates the date and state.

Search by date and country: 
This search categories only shows by date and country.

Summary:
Hypertext Markup Language (HTML) and JavaScript can be used together to build a dynamic website for users. Sightings is a website with dynamic search filters which has multiple search criteria to refine the viewers search results for information.

The drawback of this new design was to setup the filters to run a search for multiple criteria and provide results instant to the viewer. To overcome the issue and get results, used a for loop of Object.Entries to search the user input request, filter through data and print them as table on the website.

The next two development for search criteria can be "Search by keyword" and by month. They both represent uniqueness to search method, where users do not need to input the whole date to get the results. They can extract the information through just by entering the month alone. It is same rule for searching by “key word”, users can skip all the fields to fill by just inputting the specific word to extract all the information through the website.
