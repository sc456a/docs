---
title: RokSprocket: Strips Layout Mode
description: Your Guide to the Strips RokSprocket Layout Mode for Joomla
breadcrumb: /joomla:Joomla/!extensions:Extensions/!roksprocket:RokSprocket

---

### Strips
![][strips_demo]

Strips displays content in long rectangular blocks, which appear vertically on larger browsers and horizontally on smaller mobile screens.

![][strips_1]

:   1. **Title** This is the title of your module. [12%, 14%, se]
    2. **Show Title** Determines whether the title of the module will appear for visitors or remain hidden. [12%, 58%, se]
    3. **Status** Sets the publishing status for the module. [20%, 64%, nw]
    4. **Access** Sets the access level for the module. [12%, 81%, se]
    5. **Filtered Article List Options** Gives you access to item-specific settings for the articles title, description, image, and link. [50%, 50%, sw]
    6. **Layout Type** This is where you will select the Layout Mode you wish to use for your RokSprocket Module. [47%, 80%, sw]
    7. **Content Filter Rules** Sets the content filter rules for the module. [57%, 78%, sw]

1. The **Title** field gives you the ability to set a title for the module itself. Every module has to have a title, though you can opt to hide it from public view for a cleaner, more template integrated look. The **Position** field right below it gives you the ability to set the position within the template's layout the module should appear in.

2. The **Show Title** option gives you the ability to determine whether or not the title of the module will appear with the module on the frontend.

3. The **Status** option allows you to determine the current publishing status of the module. An unpublished module will still appear on the backend for administrators, but will not appear on the live site.

4. The **Access** option gives you the ability to determine which user group will be able to see the module on the frontend. Someone logged in as a registered user may be able to see a module set at that level while random visitors do not see it.

5. The **Filtered Article List** gives you access to item-specific settings including:
    * **Title** - Allows you to override the article title in the module. The article title will be used if this is left at *Default*.
    * **Description** - Allows you to set a description for the item. If this is left at *Default* the introtext from the article is used. 
    * **Image** - This allows you to circumvent the assigned image from the article and replace it with one specifically for the feature. 
    * **Link** - If set, the link will show a **Read More** button as well as link the title. On specific themes, it will link the image in the feature, as well.

6. The **Content Provider and Layout Type** section gives you the ability to set the Layout Mode you wish to use for the module. This is often the first setting you want to pay attention to when creating a new RokSprocket module. The Content Provider can vary, but in most Joomla instances, this will default to Joomla.

7. The **Content Filter Rules** section gives you the ability to determine how the module will pull content to make up the items. For example, you can have the module pull articles that are within a specific category, contain a particular name or keyword in the title, or choose specific articles. You can also modify how this content is sorted in the module.

![][strips_2]

:   1. **Display Limit** The amount of articles to show when rendering. [12%, 40%, se]
    2. **Theme** This sets the theme for displaying strips in the module. [15%, 70%, sw]
    3. **Article Titles** This toggle enables you to show or hide article titles. [21%, 40%, se]
    4. **Article Text** This toggle allows you to show or hide article text in a strips. [25%, 49%, sw]
    5. **Preview Length** This option sets the amount of words you wish to limit the preview to within the module's article display. [29%, 67%, sw]
    6. **Strip HTML Tags** This option removes HTML tags from the description of an article. [34%, 46%, sw]
    7. **Arrow Navigation** This option determines whether you wish to show or hide the arrow navigation controls on the module. [38%, 40%, se]
    8. **Pagination** This toggle gives you control over whether or not you wish to show pagination. [43%, 48%, sw]
    9. **Animation**  This dropdown gives you the ability to set the type of animation that happens during transitions from one feature to the next. [47%, 40%, se]
    10. **Autoplay** Sets whether you want the module to start rolling through strips automatically when the page loads, or to await a command from the visitor. [52%, 52%, sw]
    11. **Autoplay Delay** Sets the amount of time between cycled strips in the module. The longer this delay (in seconds), the longer a single article will be featured in the module. [56%, 65%, sw]
    12. **Image Resize** This option is best utilized on a non-responsive template. It renders a copy of the selected image with a maximum width or height determined in these fields. [63%, 42%, se]
    13. **Default Title** You can set a default title for all articles from this field. If this selection is set at `Default Article Title`, then the articles' given titles are used. [74%, 40%, se]
    14. **Default Article Text** This field allows you to set default article text for all strips in the module. If this is not changed from its default, then the article's introductory text is used. [78%, 64%, sw]
    15. **Default Article Image** Determines which image field the module will default to when locating an image for the feature. [82%, 40%, se]
    16. **Default Link** Determines which link field the module will default to when locating a link for the feature. [86%, 64%, sw]

1. The **Theme** option sets the theme for displaying strips in the module. These themes determine how the strips look within the module. You can choose the one that best fits your template and/or personal taste.

2. The **Display Limit** field sets the amount of articles shown when the page is rendered.  Setting this limit to zero or infinity will allow it to cycle through all applicable items.

3. The **Preview Length** option sets the amount of words you wish to limit the preview to within the module's article display. This can help reduce occurrences of controls overlaying the description and make your strips more uniform.

4.  The **Strip HTML Tags** option removes HTML tags from the description of an article.

5.  The **Previews per Page** option gives you control over how many article previews show on each page.

6. **Items Per Row** sets the amount of article items to show in each row.

7.  The **Arrow Navigation** option determines whether you wish to show or hide the arrow navigation controls on the module.

8. The **Pagination** toggle gives you control over whether or not you wish to show pagination.

9.  The **Animation** dropdown gives you the ability to set the type of animation that happens during transitions from one feature to the next.

10.  **Autoplay** sets whether you want the module to start rolling through strips automatically when the page loads, or to await a command from the visitor.

11.  **Autoplay Delay** sets the amount of time between cycled strips in the module. The longer this delay (in seconds), the longer a single article will be featured in the module.

12.  The **Image Resize** option is best utilized on a non-responsive template. It renders a copy of the selected image with a maximum width or height determined in these fields. This option is disabled by default, but can be used to fit a variety of templates which would benefit from this uniformity. In a responsive template, images will continue to expand or shrink based on the grid and browser window size.

13.  You can set a default title for all articles from the **Default Title** field. If this selection is set at **Default Article Title**, then the articles' given titles are used. 

14. The **Default Article Text** field allows you to set default article text for all strips in the module. If this is not changed from its default, then the article's introductory text is used. You can choose full text or to pull from the meta description for each article in this field.

15. The **Default Article Image** option gives you the ability to set a standard default image for articles. This includes: a custom image, article intro image, and article full image. Alternatively, you can leave this set to default and it will grab the global default article image.

16. The **Default Article Link** gives you the ability to set a default link field from articles in this module. For example, if you wish to link to the link provided in the article's **Link A** or **Link B** settings, you can do so here.

[features]: assets/features.jpeg
[headlines]: assets/headlines.jpeg
[lists]: assets/lists.jpeg
[mosaic]: assets/mosaic.jpeg
[tabs]: assets/tabs.jpeg
[features_link]: features_mode.md
[lists_link]: lists_mode.md
[tabs_link]: tabs_mode.md
[mosaic_link]: mosaic_mode.md
[headlines_link]: headlines_mode.md
[strips_link]: strips_mode.md
[features_1]: assets/features_1.jpeg
[features_2]: assets/features_2.jpeg
[lists_1]: assets/lists_1.jpeg
[lists_2]: assets/lists_2.jpeg
[mosaic_1]: assets/mosaic_1.jpeg
[mosaic_2]: assets/mosaic_2.jpeg
[strips_1]: assets/strips_1.jpeg
[strips_2]: assets/strips_2.jpeg
[headlines_1]: assets/headlines_1.jpeg
[headlines_2]: assets/headlines_2.jpeg
[tabs_1]: assets/tabs_1.jpeg
[tabs_2]: assets/tabs_2.jpeg
[roksprocket_module_1]: assets/roksprocket_module_1.jpeg
[strips_demo]: assets/strips_demo.jpeg
