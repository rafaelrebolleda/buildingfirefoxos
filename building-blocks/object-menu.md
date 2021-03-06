---
layout: bffos
title: Object Menu
section: building-blocks
h2: <strong>Building Blocks:</strong> markup & examples
---

## Object menu

An Object menu (contextual menu) presents a list of actions, related to the app's content, from which the user may make a selection.

> ### Characteristics
> * Object menus contain one or more items.
> * These menus expand in height to accomodate their items, to a maximum of the screen's height. Once that maximum height is reached, the content becomes scrollable vertically. Generally, the best practice is to try to include no more than five items plus a menu title.
> * The title string is required.
> * The menu is closed by one of:
>   * Selecting one of the actions.
>   * Tapping the "Cancel" button.
>   * Opposite to Action menu, Object menu can have several main actions.

<h3>Default</h3>
<div> 
  <h4>Example</h4>
  <section class="example">
    <img src="../images/BB/object_menu_1.jpg" alt="Object menu (Image replacing code)"/>
    <article class="frame full">{% include building-blocks/object_menu_1.html %}</article>
  </section>

  <h4>Css link</h4>
  {% highlight html linenos=table %}<link href="(your styles folder)/style/object_menu.css" rel="stylesheet" type="text/css">{% endhighlight %}

  <h4>HTML code</h4>
  {% highlight html linenos=table %}{% include building-blocks/object_menu_1.html %}{% endhighlight %}
</div>

<hr>

<h3>Switches</h3>
<div>
  <h4>Example</h4>
  <section class="example">
    <img src="../images/BB/object_menu_2.jpg" alt="Object menu (Image replacing code)"/>
    <article class="frame full">{% include building-blocks/object_menu_2.html %}</article>
  </section>

  <h4>Css link</h4>
  {% highlight html linenos=table %}<link href="(your styles folder)/style/switches.css" rel="stylesheet" type="text/css">
  <link href="(your styles folder)/style/object_menu.css" rel="stylesheet" type="text/css">{% endhighlight %}

  <h4>HTML code</h4>
  {% highlight html linenos=table %}{% include building-blocks/object_menu_2.html %}{% endhighlight %}

</div>

<hr>

<h3>Inputs</h3>
<div>
  <h4>Example</h4>
  <section class="example">
    <img src="../images/BB/object_menu_3.jpg" alt="Object menu (Image replacing code)"/>
    <article class="frame full">{% include building-blocks/object_menu_3.html %}</article>
  </section>

  <h4>Css link</h4>
  {% highlight html linenos=table %}<link href="(your styles folder)/style/input_areas.css" rel="stylesheet" type="text/css">
  <link href="(your styles folder)/style/object_menu.css" rel="stylesheet" type="text/css">{% endhighlight %}

  <h4>HTML code</h4>
  {% highlight html linenos=table %}{% include building-blocks/object_menu_3.html %}{% endhighlight %}
</div>