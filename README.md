##Description
This widget replaces the browser context menu with the actions from the toolbar when the user right clicks on a datagrid content row.
It's possible to excule certain buttons (e.g. the search switch) from the menu.

##Typical usage scenario
Use this to give the user an extra interaction-option on a datagrid.

##Features and limitations
* Has to be configured for each datagrid on which you want to use it.
* Has to be put above the datagrid on which you want to apply it, for correct positioning of the menu
* You can style the menu by adding CSS for your application by using ".DatagridContextMenu > .contextMenuList", each action in the toolbar is added as a "li"

##Dependencies
* Mendix 6.7.0+
