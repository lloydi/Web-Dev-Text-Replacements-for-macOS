# Web Dev Text Replacements for macOS

These .plist files can simply be drag/dropped into the System Settings for keyboard text replacements.

Unfortunately, I am not sure how you would add it in a way that does not require a mouse (the add buttons in this panel are for adding individual entries).

<img width="710" alt="Choose Text Replacements button in the System Settings Keyboard section" src="https://user-images.githubusercontent.com/2778763/210348789-ac6c550c-5d20-44cf-9ea6-e2409db158bf.png">
<img width="643" alt="Drag the .plist file into the window that shows the text replacement entries" src="https://user-images.githubusercontent.com/2778763/210348786-7035d309-f007-442f-8bb0-008775c6ef9c.png">
<img width="705" alt="All Text replacements are now added" src="https://user-images.githubusercontent.com/2778763/210348776-92803d63-c2b9-46ab-9b42-77db92339fa1.png">

## Trigger format

How to trigger these text replacements:

### HTML Reference

(Where `kbd` is the HTML element you are getting a link for; change according to the element that you need)

* HTML reference - link. Trigger format = <mark>!kbd-l </mark>
* HTML reference - Markdown link. Trigger format = <mark>!kbd-md</mark>

### WCAG SC Links

(Where `1.1.1` is the SC you are getting a link for; change according to the SC that you need)

* WCAG 2.1 - Link. Trigger format = <mark>1.1.1-l</mark>
* WCAG 2.1 - Markdown link. Trigger format = <mark>1.1.1-md</mark>
* WCAG 2.1 - Understanding - Link. Trigger format = <mark>1.1.1-u-l</mark>
* WCAG 2.1 - Understanding - Markdown link. Trigger format = <mark>1.1.1-u-md</mark>
