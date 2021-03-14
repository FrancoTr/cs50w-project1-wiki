# CS50W - Wiki

**Objective**: Design a Wikipedia-like online encyclopedia.

## Specifications

Complete the implementation of your Wiki encyclopedia. You must fulfill the following *requirements*:

### **Entry Page**: 

Visiting /wiki/TITLE, where TITLE is the title of an encyclopedia entry, should render a page that displays the contents of that encyclopedia entry.

* The view should get the content of the encyclopedia entry by calling the appropriate util function.
* If an entry is requested that does not exist, the user should be presented with an error page indicating that their requested page was not found.
* If the entry does exist, the user should be presented with a page that displays the content of the entry. The title of the page should include the name of the entry.

### **Index Page**: 

Update index.html such that, instead of merely listing the names of all pages in the encyclopedia, user can click on any entry name to be taken directly to that entry page.

### **Search**:

Allow the user to type a query into the search box in the sidebar to search for an encyclopedia entry.
