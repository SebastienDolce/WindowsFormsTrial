Create a main form that will have a group box and a list view.

Create properties in the main form to access the user settings. Use these properties to encapsulate access to the settings.
Set the client size and desktop location to the settings when the form loads.
Dock the groupbox to the top. Add four buttons and a text box to the group box.
Add Name button:
Anchor the button to the top edge of the group box.
Validate that the name is not empty, contains a non-space character and is no longer than 15 characters. Perform thorough validation and allow focus change.
Use an error provider to display an error when the name does not validate.
If the name is valid, then clear the name in the text box, after it is added to the list view.
Save Size button: set the user setting for the size to the current client size and save the settings. Anchor the button to the lower left corner of the group box.
Save Location button: set the user setting for the location to the current desktop location and save the settings. Anchor the button to thelower right corner of the group box.
Reset Settings button: reset the user settings to the original default values. Set the client size and desktop location to the reset settings. Anchor the button to the bottom edge of the group box.
Dock the list view so it fills the remaining available space in the form.
Add a notify icon. Create a simple icon for it in the resource editor. When the notify icon is clicked, make the application visible and activate it.
Keep track of whether a name has been added to the list view. When the application closes, display a message box if the user has added a name to the list view. Allow the user to cancel the closing of the application, in this case.
When the application loses focus, hide the application.