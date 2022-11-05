# firefox-custom-bookmarks

### How to open Bookmarks sidebar in Firefox (Chosen solution)
- Press the keyboard shortcut: Ctrl+B
- Add the optional Sidebars button to the toolbar: Customize Firefox controls, buttons and toolbars
- Display the optional menu bar: View > Sidebar > Bookmarks


### Steps to reproduce:

1. open profile folder in firefox 

	* url (firefox)

			about:support

	* Windows example (profile folder)

			C:\Users\wookingwoo\AppData\Roaming\Mozilla\Firefox\Profiles\km3tzs5e.default-release 

2. create a file in profile folder

	[chrome/userChrome.css](https://github.com/wookingwoo/firefox-custom-bookmarks/blob/main/userChrome.css)
			
	* Windows example

			C:\Users\wookingwoo\AppData\Roaming\Mozilla\Firefox\Profiles\km3tzs5e.default-release\chrome\userChrome.css

3. set toolkit

	* url

			about:config

	* set true

			toolkit.legacyUserProfileCustomizations.stylesheets=true

4. restart firefox
