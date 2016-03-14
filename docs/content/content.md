# Content Items

Content Items make up the bulk of the text on your site. Pages are the placeholders; providing an address to which a user can navigate and save a bookmark. Content items are the filler on those pages. You can place multiple content items on a page, and you can use one content item on many pages. When you change a content item, it is automatically updated in all the pages where it is used on your site.

The Content Editor tool is used to create content items, edit content properties, edit the content itself, and delete content items. You can access the Content Editor by clicking on the “Content Items” link in the left navigation bar, within the "Content" section on any administrative page. Alternatively, you can click on “Content Items" link in the body of the main administrative screen.

A representation of the main Content Editor screen is shown in Figure 5. On this screen you can see all the content items in your site. The top of the page contains a link allowing you to create new content items.

The bottom part of the screen lists your existing content items in alphabetical order. You can change the sort order by clicking on one of the other column header links. Next to each item is a check box that allows you to perform certain actions on one or more content items. The actions that can be taken are shown in the “Action” menu at the start of the content item listing.

You can also view a subset of the content items by selecting a group name from the “Display content items from group” menu, and clicking “Submit.” This will show only those content items that are part of that content group.

You can _create additional content groups_, or edit existing groups, by clicking on the “edit content groups” link next to “Display content items from group” menu. Each content group has an optional setting that allows you to specify an email address for a person responsible for that content group. When any change is made to an item in that group, an email notification is sent to that address.

## Creating Content Items

To create a new content item, click the “New Content Item” link at the top of the main Content Editor page. This will open a new pop-up window wizard, and display the fields for the first step in the two-step process of creating a content item.

### Step One

Define the Properties for the Content Item. In this step, you will assign descriptive information about the content item using these fields:

**Select a Group** – This menu is used to assign this content item to a content group.

**Name** – This is the descriptive name used to identify the content item. When the content item is used as part of a content filter, this field is used as the headline for this content item. Otherwise, site visitors will not see this name.

**Live** – This check box determines whether this content item can be seen by your site visitors. If the content item is not live (the box is not checked), then visitors to your site will not see this item. Once you make the content item live (by checking the box and saving your changes), VitaSite will make it available for your web site visitors to see. This functionality allows you to work with an item in the administrative tools until you get it finished, without making it available on the site until it is ready.

**Private** – This check box is only available in a multiple sites installation of VitaSite. If this box is checked, this item can only be used on the site in which it is created. If this box is unchecked, it will be made available for use on other sites in the installation.

Author – This is an optional field used to identify the author of the content item. If the item is used in a content filter, the information in this field is shown to users as part of the content summary. Otherwise, site users do not see this field.

Go Live Date – This is an optional field used to determine when a content item should appear in a content filter. It only applies to content filters, and does not affect the appearance of the content item when it is inserted on a page.

Expire Date – This is an optional field used to determine when a content item should disappear in a content filter. It only applies to content filters, and does not affect the appearance of the content item when it is inserted on a page.

Summary – This is an optional field used to provide a short summary of the content item. It is only used when an item is part of a content filter, and the content filter has been set to show summaries.

Once you have completed these fields, you will generally click the “Proceed to Editor” button. This will save the properties, and take you to the next screen where you can edit the content itself. Clicking the “save properties” button will not proceed to the editor after saving the properties.

### Step Two 

Edit the content of the item. In this step you will work with the text and images that make up this item. This step uses a visual what-you-see-is-what-you-get (WYSIWYG) editor, which allows you to control the appearance of your content item without having to learn HTML. An image of the WYSIWYG editor is shown in Figure 6.

The actions you can perform using the WYSIWYG Editor include:

Typeface Menu: This menu allows you to select the typeface for you text. This option may be disabled if your site uses a cascading style sheet.
Type Size Menu: This menu allows you to select the type size for you text. This option may be disabled if your site uses a cascading style sheet.
Style Menu: This menu allows you to apply a style to your text using the styles defined in your site’s cascading style sheet.
- Undo: This button undoes the last edit you made. It remembers multiple edits, and undoes each previous edit each time you click the button.
- Redo: This button redoes the last “undo” you made using the “Undo” button. It remembers multiple edits, and redoes each previous edit each time you click the button.
- Font Color: This button allows you to define the color of your text.
- Font Background Color: This button allows you to define the background
color, or highlight color, of your text.
- Cut: This button removes the selected text, and places it on the clipboard.
- Copy: This button copies the selected text to the clipboard.
- Paste: This button inserts the contents of the clipboard at the current text insertion point.
- Align Left: This button aligns the current selection to the left.
- Center: This button aligns the current selection to the center point.
- Align Right: This button aligns the current selection to the right.
- Align Justify: This button aligns the current selection using full justification.
- Ordered List: This button allows you to create an ordered list. Place the insertion point where you want the list to start, then click this button once for each list item you want to create. Once you have created the list items, you can type the text that should appear next to each.
- Unordered List: This button allows you to create an ordered list. Place the insertion point where you want the list to start, then click this button once for each list item you want to create. Once you have created the list items, you can type the text that should appear next to each.
- Subscript: This button allows you to create subscript text.
- Superscript: This button allows you to create superscript text.
- Strike through This button allows you to create strike through text.
- Insert Image: This button opens the image dialog box, which allows you to insert an image into your content item. Once an image has been inserted, its parameters cannot be edited using this tool.
- Insert Hyperlink: This button opens the hyperlink dialog box, which allows you to create links.
- Insert Line: This button inserts a horizontal rule.
- Bold: This button allows you to create bold text.
- Italic: This button allows you to create italic text.
- Underline: This button allows you to create underlined text.
There are two tabs at the bottom of the WYSIWYG window, which switch between
the normal WYSIWYG view and the HTML Source view.
Two of the WYSIWYG tools ask for additional parameters when you click their respective buttons. These are the Insert Image tool and the Insert Hyperlink tool.
When you click the Insert Image button the dialog shown in Figure 8 is opened. This dialog allows you to choose the image you want to insert, and to define the parameters for the image.

The “Image Location” box allows you to specify which image you want to insert. If you have previously uploaded an image using the Media Uploads tool, select the “Uploaded Images” option. Then you can navigate to your image in the listing on the right.
If you are using an image from the Web, select the “URL” option and type the full address to the image you want to use.
The “Image Attributes” box allows you to specify optional parameters for your image. Once you have selected your image and assigned any optional parameters, click the “OK” button to insert your image into the text window.

When you click the Insert Hyperlink button the dialog shown in Figure 9 is opened. This dialog allows you to choose the hyperlink you want to insert, and to define any optional parameters.
If you are linking to a page from your VitaSite, choose the “Link” option. Then you will be able to navigate to the page you want using the window on the right.
If you are linking to an external resource, choose the “URL” option and type in the fill address. Once you click the “OK” button your link will be inserted into the text.

Once you have completed your text edits, click the “save” button at the bottom of the WYSIWYG screen. If you do not want to save your text edits, click the “cancel” button.
There are two additional text editors available for advanced users. The first is a WYSIWYG editor based on the Microsoft DHTML control. This editor only works on PCs running Internet Explorer in a Windows environment, and is not a supported editor. It is provided as a convenience to advanced users.
The second additional editor is the text-only editor, which allows raw HTML to be inserted in a content item. This editor does not display content in a WYSIWYG window, and requires the user to be familiar with HTML.

You can edit existing content items by clicking the “edit” link next to the name of the content item you wish to change. The edit process then works in the same way as the creation process described above.

VitaSite maintains a history of all revisions of your content items. Each time you save changes to a content item, the previous version is stored in the history file. You can access this version history by clicking the “history” link next to the content item name. Each saved version is listed by the time and date that it was first saved. You can click the “view” link to see how that version of the item appeared. Clicking the “restore” link restores the content item to the version you choose.