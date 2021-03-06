# ***Code Refactor Engagement for Horiseon Marketing by Cerebreo Creators***

# Purpose
### The Cerebero Creators were hired by the Horiseon Marketing to refactor their web design in order for it to be optimized for search engines and meet accessibility standards. The scope of this engagement includes consolidating and scouting the elements of the web page, adding attributes to ensure that the pages are readable by screen readers and improving the flow of the pages and code for future revisions.

## I. First Commit

## I.1 Refactor Head Element on HTML
- Replaced title with the name of the company.

## I.2 Refactor Header
### I.2.a Header on HTML
- Added Header semantic element.
- Added Nav semantic element.
- Made Company Logo "Horiseon" interactive by pointing back to the index.html upon click event. 
- Added comments to indicate the Navigation section.
- Added comments to indicate the Unordered List elements. 
- Added comments to indicate the List items. 
- Added comments to indicate the Anchor elements. 
- Removed "Header" class and introduced a Nav element with class "Header".

### I.2.a Header on CSS
- Added comments to indicate General CSS styles. 
- Removed "list-style-type" property under header class since it does not affect the code.  
- Updated seo class call since it is a class itself. 

## I.3 Refactor Hero
- Added comments to easily identify hero html and style from other sections.
- Grouped Hero elements in the HTML using aside element.
- Added title attribute on the image presented.
- Moved float left and right classes to general styles section. 
- Added comments to easily identify footer html and style from other sections.
- Added HTML comments to easily identify services and benefits sections.

## I.4 Refactor Services
- Consolidated identifiers (id) "search-engine-optimization", "online-reputation-management" and "social-media-marketing" into one class called "services-info".
- Consolidated descending selectors for img and h2 of class: "services" so they are under the "services-info" class.
- Added alt attributes to the img elements in the services section. 

## I.5 Refactor Benefits
- Added Section semantic element with class "benefits" to separate the benefits section and removed parent div. 
- Consolidated benefits-brand, benefits-lead and benefits-cost classes into one class called "benefits-know"
- Added alt attributes to the img elements in the benefits section. 
- Removed benefits-brand, benefits-lead and benefits-cost selectors from the stylesheet.

## I.6 Refactor Footer
- Added comments to easily identify the footer section. 
- Replaced footer section parent div with footer semantic element.

## I.7 Scouting Process - For Cleaner Code
- Added spaces in between the html codes and stylesheet to easily read code.
- Followed proper indentation on the html for cleaner identification of elements. 
- Deleted closing img tag for "Cost Management" image. 
- Added single quotes to 'Calibri' in benefits and services-info classes.

## I.8 Redeploy Horiseon Website and Updated README file

- Please visit this link to view the running website for Horiseon: https://nellirism.github.io/cerebreo-code/
- See screenshots below:

![header with Title on page](https://user-images.githubusercontent.com/71202250/112762034-a16a9700-8fb2-11eb-9a42-e7dbecdca26b.png)

![main page](https://user-images.githubusercontent.com/71202250/112762070-c959fa80-8fb2-11eb-9959-44b345797341.png)

![submain](https://user-images.githubusercontent.com/71202250/112762088-dd9df780-8fb2-11eb-8e4c-4cbbcb02e0d3.png)

![footer](https://user-images.githubusercontent.com/71202250/112762094-e1317e80-8fb2-11eb-83cb-e792f050e3db.png)





