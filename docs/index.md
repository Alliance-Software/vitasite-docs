# Welcome to VitaSite™

VitaSite is a set of tools that enable you to take control of your website. Now you can manage this critical communication channel without having to learn the technical intricacies of how the web works. After all, you don’t have to know how a modern telephone system works to use a phone to communicate in your business; and you shouldn’t have to know HTML, FTP, or any other Internet technology to use the web for communication, either. VitaSite makes managing your web site easy.

So relax. If you know how to use a word processor then you already know most of what you need to work with VitaSite.

VitaSite is also extremely robust and powerful. VitaSite technology is in use on sites that handle millions of page views per day. As your web needs grow, rest assured that VitaSite can handle your new requirements.

<div class="embed-container"><iframe width="560" height="315" src="https://www.youtube.com/embed/FTQbiNvZqaY?rel=0" frameborder="0" allowfullscreen></iframe></div>

## Simple Tools You Can Use from Anywhere

We built the VitaSite Content Management System (CMS) around simple, browser-based tools that you can use from any computer that has an Internet connection. In this way, you can update your website from your office, your kitchen table, or from a hotel room half way around the world. It requires no special desktop software. If you have Internet Explorer, Netscape Navigator, Apple Safari, or just about any other modern web browser, then you have all the software you need.

## Consistent Look & Feel

VitaSite maintains a consistent and professional graphical look and feel throughout your entire site. When you create or edit content, you don’t have to worry about making sure it looks like the rest of your site. VitaSite automatically wraps the look and feel of your site around any new content you create, and displays that content in the standard typeface and font size chosen for your site.

## Automatic Site Navigational Structure

VitaSite automatically updates your site navigational options as you add and change content. If you add a page to a particular section, VitaSite updates the navigation on all the related pages so that visitors to your site can find the new page.

VitaSite also maintains navigational aids, such as the breadcrumbs trail feature, to help your site visitors understand where they are in your site structure. This makes it easy for them to find their way back to a particular page, or to understand the structure of your site content.

## Central data storage

VitaSite uses a high performance SQL database (it’s not necessary to know what a SQL database is). This database keeps all your content in one place, and accesses it as visitors request information from your site. If your VitaSite CMS installation is hosted on Alliance Software’s servers, then we backup your content every two hours. If you host site on your organization’s servers, then your IT department's site administrators control the backup schedule.

VitaSite does not store anything on your local hard drive unless you explicitly choose to put it there. So again, you don’t have to worry about keeping track of the content you create. VitaSite takes care of that task, too.

We designed VitaSite to allow you to focus your energy on communicating your message, without worrying about all the other details that normally go into creating a website.

## “So, Why Do I Need this User’s Guide?”

You won’t for long. However, a Users Guide helps with two things:

1. It helps you get familiar with the organization of the tools, and become comfortable with how terminology is used.

1. It provides a reference to tools that you seldom use. You will find that you spend most of your time in the system using two or three tools. Occasionally, you will need to use one of the other tools. At those times, having a User’s Guide close by is helpful.

## Accessing the Administrative Tools

Throughout this Users Guide it will be assumed that you have access to computer with an Internet connection, and that you are logged into your VitaSite as an administrative user.

The first time you visit the administrative page each day, you will be asked to log in using your username and password. For the next visit that day from the same computer, you will not need to log in.

If you need to explicitly log out (e.g., when you are working from a computer that others can get access to), you can click the “logout” link that appears in the top right corner of each administrative page. This logs you out of the system, and returns the browser to the home page of your site.

!!! note
    To get started, first you need to know whether your VitaSite installation supports a single website or multiple websites. There are instructions for both types of installations below. If you do not know this information, contact your support team for help.

### Administrative Access on Single Site Installations

Logging in to your VitaSite is simple: just add “/admin” to the end of your site URL. As an example, if your site URL were: `http://www.mysite.com`

Then you would log in to your administrative tools by going to: `http://www.mysite.com/admin`

### Administrative Access on Multi-site Installations

Logging in to your VitaSite mulit-site installation takes and extra step. First, a 'shortname' is given to each sub-site underneath the main or home site. As an example, if your site 'stortname' was the word 'site' then your URL would be: `http://www.mysite.com/site`

Then you would log in to your administrative tools by going to: `http://www.mysite.com/site/admin`

For access to the main site, use `www` for the site's 'shortname.'

## Common Concepts in VitaSite

There are several concepts in which you might want to familiarize your self with as you learn to use the VitaSite content management system. These concepts are described below. However, don't worry, we'll link back to this page whenever there is a core concept you might need to know.

### Groups

**Groups** are a way to organize your content. You can think about groups as you would a file folder on either your desktop or in your physical desk. For instance in [Media Uploads](media.md) you may choose to organize your files into groups such as "Images", "PDFs", "Headshots" or any number of groups. 

!!!note 
    Most tools only allow for a single group to be applied to items within that tool.

Groups can also used in connection with [Filters](#filters). Following our example above, if a admin would like to create a list of PDFs that users could access, a Filter could be used to display uploaded files from the "PDFs" group on a page on your site. More information can be found in the [Filters section](#filters) and within the specific filter documentation on each tool that support filters throughout this guide.

### Filters

**Filters** are unique, in that they are not a separate type of item that can be edited using one of the VitaSite tools. Rather, filters are a powerful way of manipulating items with a tool, so that a page is updated automatically every time a new item is created with that tool.

When you add a filter to a page, you specify the group(s) to insert, but not specific items. Instead, you define the number of  items that will display in the filter from that group, and the filter always displays the latest content items from that group, up to the number you defined. Also, the content filter does not show the full item. Rather, it displays the name of that item as a hyperlink. When a user clicks on the hyperlink, they are show the full item. Filters have different options depending on what tool they filter, such as options to Show/Hide dates, summary information, pagination, etc. Additional information specifically pertaining to filters are included within each tool's section of this manual.

Filters can also be used to share items across multiple sites with **Tags**, if applicable. Tags are a method to filter specific items out of a group, only displaying the ones that relate to the topics you would like to filter. You would choose to filter groups from multiple sites and instead of showing all the items, the tags would only show those within those groups that contain the tag(s) chosen.

### Private

**Private** is a designation that applies only on multi-site installations, where an admin of Site A can access items from Site B, and so on. Private locks this item so it cannot be accessed outside this site. For instance, user permissions can be set up to allow an admin of a parent site access to site content from a child site and vice versa. Contact your site support team for more information on setting up user permissions to allow cross-site item access.

In the instance of [filters](#filters), private can prevent another site from pulling in items from your site. This could be useful if, say, you want a calendar event only to show on your site and not on another site's event filter, which incorporates your event groups.

## About This Users Guide

We organized this Users Guide in the same organizational structure as the VitaSite administrative tools. Each VitaSite tool has its own section, where we explain the use of that tool. We discuss the most often used tools first. Most readers of this Users Guide will learn the bulk of what they need in the sections discussing the first three tools: [Pages](pages.md), [Content Items](content.md), and [Media Uploads](media.md).