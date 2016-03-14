# Pages & Content

With VitaSite™, you organize your web site using Pages and Content. Pages are placeholders for information. [Content](content.md) is the information you put on those pages.

Think of Pages as an outline of your site. The top-level is your home page. Under that you might have six or seven sub-pages that organize information about your company in a logical way. In turn, each of those sub-pages may have sub-pages under them, which further describe the information in that section.

For example, if we wanted to take this Users Guide and make it into a web site, then we might outline it into Pages and Sub-Pages as follows:

1. Home Page
    1. Introduction & Overview
        1. Pages & Content
        1. Page Editor
        1. Content Items
        1. Media Items
            1. Etc.
            1. Etc.

You might notice that the outline looks a lot like a Table of Contents. That is the point. Organizing your site into Pages and Sub-pages provides an organizational structure that makes it easy for your site visitors to find what they’re looking for.

Think of [content](content.md) as the “stuff” that goes on your pages. Content is usually text and images, but it can also be a streaming audio/video file, a PDF document, or something similar. Content is the message you’re trying to communicate through the pages of your site.

The tools described in the rest of this section allow you to manipulate pages and various types of content.

## Page Editor

The admin uses the Page Editor tool to create pages, edit page properties, edit the content on a page, preview pages and delete pages. You can get access to the Page Editor by clicking on the “Pages” link in the left navigation bar with the "Content" section on any administrative page. Alternatively, you can click on the “Pages" link in the body of the main administrative screen.

![Figure 1.](img/pages_figure_1.png)

_Figure 1_

You can see a representation of the main Page Editor screen in Figure 1. On this screen you can see all the pages in your site. The pages are arranged in a tree structure, with related pages grouped together, and with sub-pages indented under their respective parent pages. This arrangement makes it easy for you to find the page you need, and it helps you keep the content of your site organized.

Next to each page is a group of up to five buttons. Each button performs a specific function, as follows:

* **[Edit](#edit):** This button allows you edit the content that appears on the page.
* **[Preview](#preview):** This allows you to preview a page and includes controls to allow for testing of a responsive website.
* **[Properties](#properties):** This button allows you to edit the properties of the page.
* **[Add Sub-Page](#add-sub-page):** This button adds a sub-page under the current page.
* **[Delete](#delete):** This button deletes the current page from the site.

## Edit

Click on the edit button to add, arrange or delete the content that appears on a specific page. When you click the button, a new browser window will open showing a representation of what the page will look like to your site visitors.

![Figure 2](img/pages_figure_2.png)

_Figure 2_

There are two buttons at the top of this page (see Figure 2) labeled “Save” and “Cancel.” Each button performs the following function:

* **Save** – Saves any changes you have made to the page, and closes the edit window
* **Cancel** – Discards any changes, and closes the edit window

On any given page there will be one or more areas, called content areas, which you can edit. These areas are surrounded by box with a rounded gray header, as shown in Figure 3. Inside the content area there is a toolbar associated with each content item. If no items are on the page, the tool bar only displays a plus sign( ), meaning that the only action you can take is to add an item to the page.

Once an item has been added, the full toolbar for that item will appear. There can be multiple items on a page, and each item will have its own toolbar. The full toolbar contains the following buttons:

* Insert a new item: This button starts the page insertion wizard, which allows you to insert content onto the page. The page insertion wizard is described more fully below.
* Move this item up: This button moves this item up in relation to any other items on the page around it.
* Move this item down: This button moves this item down in relation to any other items on the page around it.
* Item information: This button identifies the item by Group, Item Name, and Item Key.
* Edit this item: This button (which may not be available for every item type) opens the editor for that specific item type.
* Remove this item from the page: This button removes this item from the page. However, it does NOT delete the item from the system. The item can still be used on other pages.

It is important to remember that changes you make using these buttons are NOT saved until you click “Save” or at the top of the window. This allows you to experiment with various items, without committing to those experiments until you are satisfied with the appearance of the page.

### The Page Insertion Wizard
The page insertion wizard allows you to quickly locate an item that you want to insert on the page. At each step of the wizard you make a choice which narrows the options you see in the next step, leading to the last step of inserting a specific item onto the page. In this Users Guide, we will cover the page insertion wizard options that are common among all VitaSite installations. If your installation includes a plug-in, you may see additional options in the page insertion wizard.

In this example, we’ll follow the specific options for inserting a content item on this page. These are the same steps you will follow to insert other item types on the page, with the exception of the “content filter” type. Content Filters work differently than the other item types, and will be dealt with separately.

From the edit window for a page, you can click on an insertion button( ) to launch the page insertion wizard. This will open a new browser window, with the first set of options.

**Step 1:** The first choice you make is whether you want to insert an existing item, or create a new item. Most of the time you will be inserting an existing item, so choose that option and click “Next.”

**Step 2:** Choose the item type. There are several different types of items you can choose to insert. Each type is explained in the section of this guide devoted to the tools for that item. In most cases, you will be inserting a content item. Choose “Content Item” from the list and click “Next.”

**Step 3:** Choose the site. If you are working in a single-site environment, you will not see this option. In multiple site environments, this option allows you to choose content from a different site. The selection defaults to the site you are working on, the option you will choose most often. Choose your current site, and click next.

**Step 4:** Choose the content group. Content items are associated with groups, to help with organization (this is explained fully in the section dealing with Content Items). Choose an existing content group and click “Next.”

**Step 5:** Choose the content item. Each item in the group you selected is listed in the menu, with the most recent item at the top. Choose a content item, and click “Next.”

**Step 6:** The page insertion window closes, and the item you selected is added to the edit window. This item will NOT appear on the site until you click either the “Save” or the “Save and Close” button at the top of the edit window.

Inserting items of other types works in the same way. You narrow your selection options by making choices in each step, until the item you want is inserted on the page.

### Content Filters

In step two of the page insertion wizard, you are given the option of choosing a content filter. Content filters are unique, in that they are not a separate type of item that can be edited using one of the VitaSite tools. Rather, content filters are a powerful way of manipulating content items, so that a page is updated automatically every time a new content item is created.

When you add a content filter to a page, you specify the content group(s) to insert, but not specific content items. Instead, you define the number of content items that will display in the content filter from that content group, and the filter always displays the latest content items from that group, up to the number you defined.

Also, the content filter does not show the full item. Rather, it displays the name of that item as a hyperlink, with an optional content summary if one is available. When a user clicks on the hyperlink, they are show the full content item.

The following steps show how to insert a content filter onto a page:

From the edit window for a page, click on an insertion button( ) to launch the page insertion wizard. This will open a new browser window, with the first set of options.

**Step 1:** Choose to insert an existing item and click “Next.”

**Step 2:** Choose “Content Filter” from the list and click “Next.”

**Step 3:** This step shows two panes. In the left pane, select the group or groups you want to pull items from by placing a check mark next to the group name. In the right pane, enter the number of content items that you want to display, choose whether or not to show summaries, and then type in the headline you want to display over this content on the page. Once you have done this, click “Next.”

**Step 4:** The page insertion window closes, and the content filter you created is added to the edit window. This content filter will NOT appear on the site until you click either the “Save” or the “Save and Close” button at the top of the edit window.

Now, all you have to do to update the content displayed in the filter is add a new content item to one of the groups you selected to pull from for this filter. As soon as you save the content item, it shows up at the top of the filter and the oldest item disappears from the bottom of the filter.'

## Preview

_Documentation to come_

## Properties

Click on the properties button to edit the properties of a page. The properties of a page are simply pieces of information about the page, like its name and its position within the site. The properties page is shown in Figure 4. Changes made to page properties do not take effect until the “Save” button is clicked at the bottom of the page. Each of the fields is described below.

**Page Link Name** – The page link name is used to identify the page in the administrative tools, and for any navigational links VitaSite creates to help your users find this page (such as the left navigation bar or in the breadcrumbs trail). This name should be descriptive, but short.

**Page URL** – This shows the relative URL of the current page, in case you need to reference it for some external application.

**Page Title** – The page title defines what shows up at the top of the user’s browser window when they visit this page. This title should be consistent with the Page Link Name, but can be longer.

**Live on Site** – This check box determines whether this page can be seen by your site visitors. If the page is not live (the box is not checked), then visitors to your site will not see this page and VitaSite will not create links to it. Once you make the page live (by checking the box and saving your changes), VitaSite will create appropriate links to the page and make it available to your web site visitors to see. This functionality allows you to work with a page in the administrative tools until you get it finished, without making it available on the site until it is ready.

**Page Order** – This determines the order the pages are displayed in on the site and within the admin tools. If these are left blank, then the pages are displayed in the order in which they were created. Note that pages where the Page Order is left blank will appear before any pages where you have defined an order. Therefore, if you want to control the order of a section of pages, you must set the Page Order for all the pages involved.

**Page Template** – This option allows you to choose a different look and feel for this page, if any have been defined. Typically, this option should be set to “default.”

**Page Group** – This option allows you to assign this page to a page group. Page groups are used to control administrative access. The “edit page groups” hyperlink next to this option allows these groups to be defined.

**Parent Page** – This option allows you to move the current page, and any sub-pages under it, to a different part of the site. Choose the page from the list under which you want the current page to move. Site navigation will be updated automatically once you save this change.

**Restrict Access to User Group** – Use this option to restrict access to this page. The default setting is “No Restriction,” which allows any site visitor to see this page. The second setting, “Any Registered User,” limits access to this page to registered users of the site only. If you have defined any user groups, those groups will also appear in this list. Choosing a user group will limit access to only members of that group. When a visitor navigates to a restricted page, they will be asked to provide their username and password before they can see the contents of the page.

**Add Link in Utilities Section** – If your template includes a Utilities Link section, then checking this box will make a link to this page appear in that section.

**Loose Page** – If this box is checked, then this page is removed from the normal site hierarchy and redefined as a loose page. Loose pages are not included in standard site navigational tools.

**Show Calendar Events from Group** – If the template for this page includes the calendar tool, then this option controls what events show up on that calendar. The “All Groups” option shows all events. The “Inherit from Parent” option (the default), shows the same events as are shown on the parent page.

**META Description** – This option is seldom used, but is still available. Advanced users can use this field to define the text that appears in the META description tag for the page. At one time, search engines used this tag to determine what search phrases were relevant for a given page. Many search engines still use this tag to show information about this page in search results. If no description is defined, then the page uses the META description tag defined in the template for this page, if any.

**META Keywords** - This option is seldom used, but is still available. Advanced users can use this field to define the text that appears in the META keywords tag for the page. At one time, search engines used this tag to determine what search phrases were relevant for a given page. However, few search engines use this tag now. If no keywords are defined, then the page uses the META keywords tag defined in the template for this page, if any.

## Add Sub-Page

Clicking the “Add Sub-Page” button immediately adds a new sub-page under the current page and opens the properties screen for the new sub-page. The options for a sub-page are the same as described in the Properties section above.

If you do not define the properties of the new sub-page, it will be listed as “New Page” in the page editor until you either define the properties or delete the sub-page.

## Delete

Clicking the delete option displays a confirmation screen that asks if you want to delete or cancel. Choosing “delete” removes this page from the site permanently. However, any content contained on the page is not deleted, and can be used on other pages.