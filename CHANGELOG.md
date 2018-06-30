# Changelog

### 1.4.0
- Initial support for Pale Moon 28

### 1.3.0
- Default accent color on Win10 changed to black-on-white
- Remove unused urlbar progress bar styles (as of PM 27.5)
  - This causes problems with the status bar progress meter

### 1.2.9
- Drop support for PM 27.4 and lower
- Support PM 27.5's Win10 window styling implementation
- Styling for verify places database (about:support)
- Restore app menu private browsing indicator
- Restore padlock icons and add glow to padlock and favicon
  - If you want to remove the padlock, switch the **browser.padlock.show** pref to false.

### 1.2.8
- Drop support for versions lower than PM27.4
- Update devtools styling

### 1.2.7
- Restore missing icons on notification panel

### 1.2.6
- Remove aboutReader.css
- Update session restore and certificate error styling
- Minor fixes to browser.css (see commit)
- Don't invert toolbar buttons dropmarker when tabs are on top

### 1.2.5
- Proper styling for bookmark items and identity icon
- Remove border from proxy favicon (default)
- Add image document proxy favicon styling
- Add missing glow to some toolbar icons
- Proper standalone go-button styling
- Minor changes to add-ons page style
- Restore in-content ui background
- Remove unused images
	
### 1.2.0
- Fix inconsistent styling
- Restore missing opacity applied to buttons when it is disabled during full/text modes
- Restore glow on the forward button
- Use defined color instead of ThreeDDarkShadow for urlbar border color
- Made the identity box round again when a notification popup box is visible
- Add support for Home Styler (when you have this add-on, the about:home page will now look like FF4's)

### 1.1.5
- Fix for margin on text-only mode when use small icons is not enabled
- Restore missing background for unselected tabs
- Add a 1px margin near the back button
- Add style to search textbox and buttons in add-ons page

### 1.1.0
- Fix for abrupt animation end on toolbar button
- Add missing rounded right edges of urlbar go/stop/reload
- Style toolbar buttons for other modes in main browser

### 1.0.0 - 2017-02-16
- Initial release