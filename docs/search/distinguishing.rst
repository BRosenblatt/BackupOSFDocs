
**Purpose:** Results returned include projects, components, users, registrations, and SHARE results. Each is distinguished
from one another so that the user can best find the appropriate resource.

Links from each search result bring the user to the relevant page.

Project and component results show the title with a link to the "Overview" page as well as the contributors and links to
their user profiles. If tags or descriptions are provided, these are listed below the project title. Options to jump to
the homepage wiki or the files page are provided.

If a result returned is a component, the parent project title precedes the component title using the standard breadcrumbs
format: Project / Component. Both the project and component titles are linked to the relevant "Overview" pages. Projects
that are children of projects do not display breadcrumbs.

Registration results also show the title and contributors with links to the registration’s "Overview" page and user profiles.
In addition, registrations are indicated by text to the right of their name that reads “(Registration).” Below the title
of the registration is bold text that reads::

    Date Registered: [Date and time]

User results show the user’s name and their Gravatar image.

SHARE results are not shown, but are accessible via the SHARE link (filter) on the left hand side of the page.

If no search results are returned, the right side of the page shows “No results found” and the category filters only
show the Total and SHARE categories, with a count of zero relevant results.

Filtering Search Results
----------------------
**Purpose:** Filtering allows the user to remove extraneous results.

Filtering by Category
^^^^^^^^^^^^^^^^^^^^
**Purpose:** Filtering by category allows users to focus their search on the correct content type.

When performing a search, there is a left sidebar that shows categories and their counts of how many results fell into each category. The categories are: Projects, Components, Users, Registrations, Files, Institutions, and SHARE.
A Total category is shown at the top of the sidebar. The sum of the categories amounts to the Total.

By default, the Total results are selected and displayed. The categories are displayed below the Total category in the order from most to least results. If a category has no results, it does not appear in the sidebar.

Clicking on the SHARE category does not filter results but brings the user to the separate SHARE search page with the
relevant results. SHARE results do not contribute to the Total category result count.

Users can select one of the other categories by clicking on its title. Only search results that fall into that category
are then shown on the right hand side of the page. Only one category can be selected at a time.

Filtering by Tag
^^^^^^^^^^^^^^^^^
**Purpose:** Filtering by tag narrows the search frame and raises the topic relevance of results.

When performing a search, below the left sidebar of categories are a list of tags that the search results are associated with. This section of tags is titled "Improve your search." "If no tags
are associated with any of the results, no tags appear. Clicking through each category displays the same tags.

Tags are ordered by the number of their results. They appear as buttons with a blue/grey background. The tag that has been
used the most among the search results appears first in the list.

Users can click on a tag to filter the search results. When a tag is selected, the search bar appends “AND tags:("XXX")” to the end of the query. Multiple tags can be selected and appended to a query. Tags cannot be unselected, but the user can manually delete the tag filter from the search bar (i.e. the user can delete “AND tags:("XXX").”

Filtering by license
^^^^^^^^^^^^^^^^^^^^
**Purpose**: Filtering by license narrows the search results to show those items with a particular license.

The "Filter by licence" sidebar is only visible when the user clicks the "Projects," "Components," or "Registrations" categories from the left sidebar. The list of filters appears below the "Improve your search" section of licenses. Each license type has a number to its right that shows how many search results are associated with that license. Licenses are ordered from top to bottom according to the total number of search results associated with that license. Even if no search results have added a licence, the license type has the number "0" to its right. The user can select one license to filter search results. Or, the user can select multiple licenses at the same time to filter search results - each selected licence will be highlighted in blue in the left sidebar.

SHARE
^^^^^
**Purpose:** Aggregates data from several different sources to make research easily searchable and accessible.

When the user clicks **SHARE** from the left sidebar, they are taken to the SHARE search page that shows results pertaining to the query that the user entered into the OSF search bar.

The SHARE search page has a search bar in the top center, which displays the query the user entered into the OSF search bar. Below the left side of the search bar, the total number of results in SHARE appears as the following::
  
    xx,xxx,xxx events as of mm/dd/year [the current date is listed]

Below the center of the search bar, the total number of search results appear as the following::
  
    Found xxx,xxx events in 0.xxx seconds
    
Below the right side of the search bar, the total number of aggregated sources appears as the following::
  
    Aggregating xxx sources

Below the total number of search results is a drop-down button that reads: "View query body." Clicking this button causes a drop-down section of the query code to unfold. Above this section is a line of text and a link::
  
    Search API: https://share.osf.io/api/v2/search/creativeworks/_search

A list of search results are listed in the middle of the SHARE search page.

SHARE sources are required to provide the source, type, and title to display in search results. If sources choose to provide more metadata, results can include any or all of the following metadata: title, type, source, publisher, tags, and date last updated. If a source does not provide a type, then the type will read: "Not Categorized." If the source does not provide a publisher, then no publisher will be listed. If the source does not provide a date, then the date will not be listed. 

There are nine left sidebar menus from which the user can filter results: "Sort by,""Date," "Type," "Tag," "Publisher," "Funder," "Language," and "People."

In the "Sort by" menu, "Relevance" is selected by default. The user can click on the menu and a drop-down menu will unfold from which the user can sort results by the following::
  
    Relevance
    Date Updated (Newest first)
    Date Updated (Oldest first)
    Ingest Date (Newest first)
    Ingest Date (Oldest first)
    
Whichever sorting option the user clicks, the search results will be filtered accordingly, and whichever sorting option the user clicks, the "Sort by" menu will by titled "Sort by: [sorting option]."

In the "Source" section, there is a drop-down menu and a pie chart of all of the SHARE sources. The text displayed in the drop-down menu reads: "Add Source filter." The user can click on the menu and a drop-down menu will unfold from which the user can filter results by any source. The user can also click on a section of the pie chart to filter results by source.

In the "Date" section, there is a drop-down menu of calendars. The text displayed in the drop-down menu reads: [calendar icon] "All time." The user can click on the menu and a drop-down menu of calendars date ranches will unfold.

This drop-down menu has the following date range options::
  
    Past week
    Past month
    Past year
    Past decade
    Custom Range

When the user clicks on the menu, "Custom Range" is selected by default, and two calendars appear to the right, displaying the current month and the next month from which the user can choose a custom date range by which to filter results. There are back and forward arrows on the calendars that the user can click to choose dates from the past and dates from the future. The user will need to click **Apply** to filter results by the custom dates.

From the "Type" sidebar, the user can click a type to automatically filter results. The types include: data set, patent, poster, presentation, publication (article, book, conference paper, dissertation, preprint, project, registration, report, thesis, working paper), repository, retraction, software, not categorized.

From the "Tag" sidebar, the user can click the menu "Add Tag filter" that brings up a drop-down menu with text that reads: "Type to search." The user can type letters or words into the menu to show results in the drop-down menu. Pressing **enter** after typing is not necessary. Search results will be filtered accordingly. The user can continue selecting tag filters which will appear in the drop-down box. The user can click the **x** to next to a tag to remove it as a filter.

From the "Publisher" sidebar, the user can click the "Add Publisher filter" menu that brings up a drop-down menu with text that reads: "Type to search." Pressing **enter** after typing in a letter or word is not necessary. After selecting a publisher from the menu, the publisher will appear in the drop-down box and the search results will be filtered accordingly. The user can continue selecting publisher filters which will appear in the drop-down box. The user can click the **x** next to a publisher to remove it as a filter.

From the "Funder" sidebar, the user can click the "Add Funder filter" menu that brings up a drop-down menu with text that reads "Type to search." The user can type a letter or words into the menu to show results in the drop-down menu. After selecting a funder from the menu, that funder will appear in the drop-down box and the search results will be filtered accordingly. The user can continue selecting funder filters which will appear in the drop-down box. The user can click the **x** next to a funder to remove it as a filter.

From the "Language" sidebar, the user can click the "Add Language filter" menu that brings up a drop-down menu with languages. After selecting a language, the language will appear in the drop-down box. Only one language can be used as a filter at a time. The user can click the **x** next to the language to remove it as a filter.

From the "People" sidebar, the user can click the "Add People filter" menu that brings up a drop-down menu with text that reads "Type to search." The user can type a letter or words into the menu to show results in the drop-down menu. After selecting a perosn from the menu, that person will appear in the drop-down box and the search results will be filtered accordingly. The user can continue selecting people filters which will appear in the drop-down box. The user can click the **x** next to a person to remove them as a filter.

The user can click the **Clear filters** button above the sidebars in the top left of the search page and all filters will be removed and the original search results will appear.

The user can click a search result to view it and its metadata on its "Details" page. The page will display all of the metadata that is applied to that item::
  
  Title
  Type
  Description
  Related Works
  Contributors
  Published By
  Funders
  Hosts
  Tags
  External Links
  Collected From
  Additional Information
  
If the item does not have a description, the "Description" section will read::
    
    No description provided
    
If no metadata is provided in the other sections, these sections will not appear.

The names of contributors listed under the "Contributors" section will be linked to their individual SHARE profiles.

Publishers listed in the "Published by" section will be linked to their organization's SHARE profile page.

External links listed in the "External Links" section will be linked to the item's online publication.

Works listed in the "Related Works" section will be linked to the related work's "Detail" page in SHARE.

