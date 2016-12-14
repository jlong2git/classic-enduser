<div id="wrap">

[Skip Navigation](item_fullsize.html#content)
<div id="header">

<div class="padding">

<span
id="logo">[![Omeka](http://omeka.org/ui/i/logo-horizontal-288px.gif)](../../index.html)</span>
<div id="search-form">

</div>

-   <div id="nav-showcase">

    </div>

    [Showcase](../../showcase.1.html)
-   <div id="nav-involved">

    </div>

    [Get Involved](../../index.html%3Fp=124.html)
-   <div id="nav-addons">

    </div>

    [Add-Ons](../../add-ons.1.html)
-   <div id="nav-forums">

    </div>

    [Forums](../../forums/topic/mysqli-stmt.bind-result.html)
-   <div id="nav-documentation">

    </div>

    [Documentation](http://omeka.org/codex/)
-   <div id="nav-download">

    </div>

    [Download](../../download.1.html)

</div>

</div>

<div id="content">

<div class="padding">

<div id="user-meta">

-   <div id="pt-login">

    </div>

    [Log
    In](http://omeka.org/c/index.php?title=Special:UserLogin&returnto=Functions/item%20fullsize)

</div>

Functions/item fullsize
=======================

<div id="contentSub">

<span class="subpages">&lt;
[Functions](../Functions.html "Functions")</span>

</div>

<div id="primary">

`item_fullsize()` returns HTML for a fullsize image associated with an
item. By default, the first image will be used, but other images can be
displayed by passing `$index`.

<span id="Usage" class="mw-headline"> Usage </span>
---------------------------------------------------

<div class="mw-geshi mw-content-ltr" dir="ltr">

<div class="php source-php">

``` {.de1}
<?php echo item_fullsize($props = array(),$index = 0, $item = null); ?>
```

</div>

</div>

<span id="Arguments" class="mw-headline"> Arguments </span>
-----------------------------------------------------------

 *array* `$props` {{\#if
:   array() | (optional)}}
:   Attributes to be set on the `<img>` tag.
:   {{\#if: array() | Default: `array()`}}

 *integer* `$index` {{\#if
:   0 | (optional)}}
:   Index of the file to use (where 0 is the first file).
:   {{\#if: 0 | Default: `0`}}

 *Item* `$item` {{\#if
:   null | (optional)}}
:   The item that the image belongs to. By default, the current item
    is used.
:   {{\#if: null | Default: `null`}}

<span id="Examples" class="mw-headline"> Examples </span>
---------------------------------------------------------

The following example works on the items/show.php page. Not all items
have an image associated with them, so it is best to check.

<div class="mw-geshi mw-content-ltr" dir="ltr">

<div class="php source-php">

``` {.de1}
<?php 
if(($fullsizeHtml = item_fullsize())) {
    echo $fullsizeHtml; 
}
?>
```

</div>

</div>

<span id="Source_File.2FVersion" class="mw-headline"> Source File/Version </span>
---------------------------------------------------------------------------------

-   application/helpers/ItemFunctions.php since Omeka 1.0.

<div class="printfooter">

Retrieved from
"[http://omeka.org/codex/Functions/item\_fullsize](item_fullsize.html)"

</div>

<div id="catlinks" class="catlinks">

<div id="mw-normal-catlinks">

[Category](http://omeka.org/codex/Special:Categories "Special:Categories"):
<span
dir="ltr">[Functions](../Category:Functions.html "Category:Functions")</span>

</div>

</div>

</div>

<div id="secondary">

<div class="portlet">

Documentation
-------------

-   [Home](http://omeka.org/codex/)
-   [Screencasts](http://omeka.org/codex/Screencasts)
-   [Themes](http://omeka.org/codex/Managing_Themes_2.0)
-   [Appearance](http://omeka.org/codex/Managing_Appearance_2.0)
-   [Plugins](http://omeka.org/codex/Plugins2.0)

</div>

<div class="portlet">

Page View
---------

-   <div id="nav-page">

    </div>

    [Page](item_fullsize.html)
-   <div id="nav-discussion">

    </div>

    [Discussion](http://omeka.org/c/index.php?title=Talk:Functions/item_fullsize&action=edit&redlink=1)
-   <div id="nav-view_source">

    </div>

    [View
    source](http://omeka.org/c/index.php?title=Functions/item_fullsize&action=edit)
-   <div id="nav-history">

    </div>

    [History](http://omeka.org/c/index.php?title=Functions/item_fullsize&action=history)

</div>

<div id="wiki-toolbox" class="portlet">

Toolbox
-------

-   <div id="t-whatlinkshere">

    </div>

    [What links
    here](../Special:WhatLinksHere/Functions/item_fullsize.html)
-   <div id="t-recentchangeslinked">

    </div>

    [Related
    changes](../Special:RecentChangesLinked/Functions/item_fullsize.html)
-   <div id="t-specialpages">

    </div>

    [Special pages](http://omeka.org/codex/Special:SpecialPages)

</div>

[![Creative Commons
License](https://i.creativecommons.org/l/by/3.0/us/88x31.png)](http://creativecommons.org/licenses/by/3.0/us/)\
Omeka Documentation is licensed under a [Creative Commons Attribution
3.0 United States
License](http://creativecommons.org/licenses/by/3.0/us/).

</div>

</div>

</div>

<div id="footer">

<div class="padding">

<div id="sitemap">

<div class="section">

### About

-   [Project](../../index.html%3Fp=2.html)
-   [Staff](../../index.html%3Fp=3.html)
-   [News](../../blog.1.html)
-   [License](http://www.gnu.org/copyleft/gpl.html)

</div>

<div class="section">

### Help

-   [User Forums](../../forums/topic/mysqli-stmt.bind-result.html)
-   [Documentation](http://omeka.org/codex/)
-   [Dev Listserv](http://groups.google.com/group/omeka-dev)
-   [Contact](http://omeka.org/contact/)

</div>

<div class="section">

### Downloads

-   [Download Omeka](../../download.1.html)
-   [Plugins](../../plugins.html)
-   [Themes](../../download/themes/index.html)
-   [Packages](../../index.html%3Fp=222.html)

</div>

</div>

<div id="chnm-meta">

<span id="chnm-logo">[![Roy Rosenzweig Center for History and New
Media](http://omeka.org/ui/i/rrchnm-logo-regular.gif)](http://chnm.gmu.edu)</span>
Omeka is a project of the [Roy Rosenzweig Center for History and New
Media](http://chnm.gmu.edu), [George Mason
University](http://www.gmu.edu). Copyright © 2007–2016 CHNM.

</div>

</div>

</div>

</div>