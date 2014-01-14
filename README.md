# README

The purpose of this project is to provide Notre Dame branded styles for Zurb Foundation.

## Brand Bar

### Department

By default, the department is set to "Office of Information Technologies". To change this you must edit several items in the "brandbar" in the header of the document. First, find the correct department code and replace "dept-ooit" with your new selection. These values can be found in the "Themes" section of "foundation_and_overrides.scss". You will also need to update the text inside of the "li" as well as the url. These styles call a preformatted graphic that replaces the text, but it's good to have the actual text there for accessibility purposes. The department is hidden by default at sizes less than 50em (~800px). Change as necessary depending on the graphic length of the department name.

### Colors

There are several options available for the brand-bar. The default is the blue version and is designated by the class "theme-bb-blue". To use one of the other options, change the class to one of the following:

- Blue (default): theme-bb-blue
- Gold: theme-bb-gold
- Light Gray: theme-bb-lightgray
- Medium Gray: theme-bb-mediumgray
- Dark Gray: theme-bb-darkgray

## Title Bar

The title bar comes in several options. The default is Gold as designated by the class "theme-tb-gold". To use one of the other options, change the class to one of the following:

- Gold (default): theme-tb-gold
- Gold 2: theme-tb-gold2
- Blue: theme-tb-blue

## Top Bar

Foundation include a navigation/utility bar called the "Top Bar"(http://foundation.zurb.com/docs/components/topbar.html). It's stored as a partial in this project and is located in the <header> in "application.html.erb". Remove if not needed.