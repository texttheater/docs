---
layout: base
title:  'Universal Dependencies'
---

# Universal Dependencies

[Introduction to Universal Dependencies](introduction.html)


<!-- 
     The following <div> is the top-level element for the index page
     tabs. To add a new tab (e.g. for Swedish), first add a link to
     the <ul> (e.g. <li><a href="#language-sv">Swedish</a></li>), and
     then add a <div> with the tab content below, with the same ID as
     the link (e.g. <div id="language-sv" markdown="1">[...]</div>").
 -->
<div class="jquery-ui-tabs ui-tabs ui-widget ui-widget-content ui-corner-all">

<!-- links to per-language sections, shown as tab labels -->
<ul class="ui-tabs-nav ui-helper-reset ui-helper-clearfix ui-widget-header ui-corner-all">
  <li class="ui-state-default"><a href="#language-u">Universal</a></li>
  <li class="ui-state-default"><a href="#language-en">English</a></li>
  <li class="ui-state-default"><a href="#language-fi">Finnish</a></li>
  <li class="ui-state-default"><a href="#language-other">...</a></li>
</ul>

<!-- "Universal" tab -->
<div id="language-u" markdown="1" class="ui-tabs-panel">
* [Tokenization](u/overview/tokenization.html)
* Morphology
  * [General principles](u/overview/morphology.html)
  * [Universal POS tags](u/pos/index.html) ([single document](u/pos/all.html))
  * [Universal features](u/feat/index.html) ([single document](u/feat/all.html))
  * [Language-specific features](ext-feat-index.html)
* Syntax
  * [General principles](u/overview/syntax.html)
  * [Universal relations](u/dep/index.html) ([single document](u/dep/all.html))
  * [Language-specific relations](ext-dep-index.html)
* [CoNLL-U format](format.html)

<small>This is the online documentation and example bank for Universal Dependencies, version 1 (2014-10-01).
 We intend to treat version 1 as stable for at least the next year, 
 but we may subsequently make further revisions based on experiences using it to treebank 
 a range of languages. If you plan to use the scheme yourself, please get in touch so
 that we can avoid problems with conflicting versions.</small>

</div>

<!-- "English" tab -->
<div id="language-en" markdown="1" class="ui-tabs-hide">
* [Tokenization](en/overview/tokenization.html)
* Morphology
  * [General principles](en/overview/morphology.html)
  * English POS tags: TODO
  * English features: TODO
* Syntax
  * [General principles](en/overview/syntax.html)
  * [English relations](en/dep/index.html) ([single document](en/dep/all.html))
* [CoNLL-U format](format.html)

<small>
This is part of the language-specific documentation for Universal
Dependencies. <strong>Language-specific guidlines are currently under
revision and should not be considered final.</strong> Our goal is to
have a stable version of this part of the documentation by 2015-01-01.
</small>

</div>

<!-- "Finnish" tab -->
<div id="language-fi" markdown="1" class="ui-tabs-hide">
* [Tokenization](fi/overview/tokenization.html)
* Morphology
  * [General principles](fi/overview/morphology.html)
  * Finnish POS tags: TODO
  * Finnish features: TODO
* Syntax
  * [General principles](fi/overview/syntax.html)
  * [Finnish relations](fi/dep/index.html) ([single document](fi/dep/all.html))
* [CoNLL-U format](format.html)

<small> 
This is part of the language-specific documentation for Universal
Dependencies. <strong>Language-specific guidlines are currently under
revision and should not be considered final.</strong> Our goal is to
have a stable version of this part of the documentation by 2015-01-01.
</small>

</div>

<div id="language-other" markdown="1" class="ui-tabs-hide">
More languages to come.
</div>

</div>

----------------------------------------

[How to contribute](contributing.html)