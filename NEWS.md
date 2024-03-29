### dashboardthemes ----------------------------------------

### v1.1.5
* buttonHeight and textBoxHeight parameters now default to "auto" instead of fixed pixels

### v1.1.4
* Switched automated checks from Travis to Github Actions

### v1.1.3
* Updated image links to new URLs 

### v1.1.2
* Fixed problem where shiny notifications were all the same colour for different statuses
* Fixed problem where DataTable font colour didn't reflect choice of application font colour

### v1.1.1
* Updated DESCRIPTION file to use preferred Title and Description formatting.
* Updated function examples to use \donttest{} instead of \dontrun{} tags.

### v1.1.0
* Breaking changes:
  - The boe_website theme has been discontinued, please use flat_red instead.
  - The following used to be logo objects with hard-coded text, they are now functions, with optional parameters boldText, mainText and badgeText:
  
    logo_blue_gradient, logo_flat_red, logo_grey_light, logo_grey_dark, logo_onenote, logo_poor_mans_flatly, logo_purple_gradient
    
* Major back-end refactor:
  - R source code separated into multiple files.
  - Resolved all R CMD CHECK errors, warnings and notes.
  - CSS and HTML code generated by functions has been formatted to remove line breaks.
  - shinyDashboardLogo function now has boldText, mainText and badgeText optional parameters, rather than hard-coding these values.
  
* Added back-end quality controls:
  - Unit tests for all functions.
  - Support for continuous integration on TravisCI and Jenkins.
  - Support for test coverage reports on CodeCov.
  - Support for linter checks.

### v1.0.6
* Fixed a UI bug where submenu items would incorrectly receive the "selected" colour by default instead of only on selection. (#19)

### v1.0.5
* Fixed small bug with multi-line selectize drop-box height cutting off - now set to auto by default.


### v1.0.4
* Added option to change Info font and box colour.
* Removed incorrect body tag in shinyDashboardLogoDIY function.


### v1.0.3
* Added option to change Primary/Success/Warning/Danger status highlight font colour.
* Enables better visibility of header titles in boxes that use a specific status.
* Updated all theme options with a status highlight font colour.


### v1.0.2
* Fixed small bug when viewing dashboards at smartphone screen resolution - first sidebar tab link was hidden.


### v1.0.1
* By request: Added support for changing textbox/dropdown/button height and padding.
  Four new optional arguments were added to shinyDashboardThemeDIY: 
  buttonHeight, buttonPadding, textboxHeight, textboxPadding.
  Height arguments default to 34. Padding arguments default to "6px 12px".
* Added support for modal background colour - inherited from box background colour.
* Added support for datatable search box - inherited from textbox style.


### v1.0.0 
* First BETA release for Github.


### v0.0.0.9003
* Added new theme.
* Added support for datatable formatting.


### v0.0.0.9002
* Fixed problem with textbox and drop-box font colour and drop-box menu background colour.


### v0.0.0.9001
* Introduced four new arguments in shinyDashboardThemeDIY:
  sidebarPadding, sidebarMenuBackColor, sidebarMenuPadding, sidebarMenuBorderRadius.
* Fixed problem with sidebar sub-tabs.


### v0.0.0.9000
* ALPHA release.
* Known issues: some application components have not been fully customised.
