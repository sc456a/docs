---
title: Hexeris: Recreating the Demo - Popular Addons
description: Your Guide to Recreating Elements of the Hexeris Theme for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/hexeris:Hexeris

---

Popular Addons
----
![][demo]
This area of the front page is a **mod_custom** module. You'll find the settings used in our demo below.

### Details
![][demo2]

| Option            | Setting                                                       |  
| :---------------- | :------------------------------------------------------------ |  
| Title             | `Popular Addons [span class="rt-subtitle"]RocketTheme[/span]` |  
| Show Title        | Show                                                          |  
| Position          | footer-b                                                      |  
| Status            | Published                                                     |  
| Access            | Public                                                        |  
| Start Publishing  | 0000-00-00 00:00:0                                            |  
| Finish Publishing | 0000-00-00 00:00:0                                            |  
| Language          | All                                                           |  
| Note              | Blank                                                         |  

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p class="nomarginbottom"><a href="#">RokGallery</a> is a gallery extension based on a custom-tagging architecture.</p>
<p class="rt-tag">Advanced Galleries</p>

<p class="nomarginbottom"><a href="#">RokSprocket</a> is a powerful, switchblade content display extension.</p>
<p class="rt-tag">Multiple Layouts</p>

<p class="nomarginbottom hidden-tablet hide-ie8"><a href="#">RokNavMenu</a> is the core menu extension behind Dropdown Menu.</p>
<p class="rt-tag hidden-tablet hide-ie8">Core Navigation</p>
~~~

### Basic
![][demo3]

| Option                    | Setting |
| :------------------------ | :------ |
| Prepare Content           | Yes     |
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting        |  
| :------------------ | :------------- |  
| Module Class Suffix | `hidden-phone` |  

[demo]: assets/demo_9.jpeg
[demo2]: assets/addons_1.jpeg
[demo3]: assets/addons_2.jpeg
[demo4]: assets/addons_3.jpeg