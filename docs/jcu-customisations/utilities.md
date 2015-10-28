---
layout: docs
title: Utility classes
group: jcu-customisations
---

This framework includes various utilities—classes with a single purpose. They're
designed to reduce the frequency of highly repetitive declarations in your CSS
down while allowing for quick and easy development.

## Contents

* Will be replaced with the ToC, excluding the "Contents" header
{:toc}

## Backgrounds

You can use any of the following colours and opacities and mix them into any
other block elements to provide a coloured semi-transparent background.

{% callout warning %}
#### Conveying meaning to assistive technologies

Ensure that any meaning conveyed through color is also conveyed in a format that is not purely presentational.
{% endcallout %}

For details on dealing with selector specificity, refer the [Contextual Colors
and Backgrounds](
{{ site.baseurl }}/components/utilities/#contextual-colors-and-backgrounds)
documentation from Bootstrap.

### Complete palette

<div class="row jcu-bg-examples jcu-bg--inverse">
  <div class="col-xs-3">
    <div class="jcu-bg--pink-25pc">.jcu-bg--pink-25pc</div>
    <div class="jcu-bg--pink-50pc">.jcu-bg--pink-50pc</div>
    <div class="jcu-bg--pink-75pc">.jcu-bg--pink-75pc</div>
    <div class="jcu-bg--pink-90pc">.jcu-bg--pink-90pc</div>
    <div class="jcu-bg--pink-100pc">.jcu-bg--pink-100pc</div>
  </div>
  <div class="col-xs-3">
    <div class="jcu-bg--red-25pc">.jcu-bg--red-25pc</div>
    <div class="jcu-bg--red-50pc">.jcu-bg--red-50pc</div>
    <div class="jcu-bg--red-75pc">.jcu-bg--red-75pc</div>
    <div class="jcu-bg--red-90pc">.jcu-bg--red-90pc</div>
    <div class="jcu-bg--red-100pc">.jcu-bg--red-100pc</div>
  </div>
  <div class="col-xs-3">
    <div class="jcu-bg--darkred-25pc">.jcu-bg--darkred-25pc</div>
    <div class="jcu-bg--darkred-50pc">.jcu-bg--darkred-50pc</div>
    <div class="jcu-bg--darkred-75pc">.jcu-bg--darkred-75pc</div>
    <div class="jcu-bg--darkred-90pc">.jcu-bg--darkred-90pc</div>
    <div class="jcu-bg--darkred-100pc">.jcu-bg--darkred-100pc</div>
  </div>
  <div class="col-xs-3">
    <div class="jcu-bg--orange-25pc">.jcu-bg---orange-25pc</div>
    <div class="jcu-bg--orange-50pc">.jcu-bg---orange-50pc</div>
    <div class="jcu-bg--orange-75pc">.jcu-bg---orange-75pc</div>
    <div class="jcu-bg--orange-90pc">.jcu-bg---orange-90pc</div>
    <div class="jcu-bg--orange-100pc">.jcu-bg---orange-100pc</div>
  </div>
  <div class="col-xs-3">
    <div class="jcu-bg--yellow-25pc">.jcu-bg---yellow-25pc</div>
    <div class="jcu-bg--yellow-50pc">.jcu-bg--yellow-50pc</div>
    <div class="jcu-bg--yellow-75pc">.jcu-bg--yellow-75pc</div>
    <div class="jcu-bg--yellow-90pc">.jcu-bg--yellow-90pc</div>
    <div class="jcu-bg--yellow-100pc">.jcu-bg--yellow-100pc</div>
  </div>
  <div class="col-xs-3">
    <div class="jcu-bg--lightgreen-25pc">.jcu-bg--lightgreen-25pc</div>
    <div class="jcu-bg--lightgreen-50pc">.jcu-bg--lightgreen-50pc</div>
    <div class="jcu-bg--lightgreen-75pc">.jcu-bg--lightgreen-75pc</div>
    <div class="jcu-bg--lightgreen-90pc">.jcu-bg--lightgreen-90pc</div>
    <div class="jcu-bg--lightgreen-100pc">.jcu-bg--lightgreen-100pc</div>
  </div>
  <div class="col-xs-3">
    <div class="jcu-bg--green-25pc">.jcu-bg--green-25pc</div>
    <div class="jcu-bg--green-50pc">.jcu-bg--green-50pc</div>
    <div class="jcu-bg--green-75pc">.jcu-bg--green-75pc</div>
    <div class="jcu-bg--green-90pc">.jcu-bg--green-90pc</div>
    <div class="jcu-bg--green-100pc">.jcu-bg--green-100pc</div>
  </div>
  <div class="col-xs-3">
    <div class="jcu-bg--lightblue-25pc">.jcu-bg--lightblue-25pc</div>
    <div class="jcu-bg--lightblue-50pc">.jcu-bg--lightblue-50pc</div>
    <div class="jcu-bg--lightblue-75pc">.jcu-bg--lightblue-75pc</div>
    <div class="jcu-bg--lightblue-90pc">.jcu-bg--lightblue-90pc</div>
    <div class="jcu-bg--lightblue-100pc">.jcu-bg--lightblue-100pc</div>
  </div>
  <div class="col-xs-3">
    <div class="jcu-bg--blue-25pc">.jcu-bg--blue-25pc</div>
    <div class="jcu-bg--blue-50pc">.jcu-bg--blue-50pc</div>
    <div class="jcu-bg--blue-75pc">.jcu-bg--blue-75pc</div>
    <div class="jcu-bg--blue-90pc">.jcu-bg--blue-90pc</div>
    <div class="jcu-bg--blue-100pc">.jcu-bg--blue-100pc</div>
  </div>
  <div class="col-xs-3">
    <div class="jcu-bg--darkblue-25pc">.jcu-bg--darkblue-25pc</div>
    <div class="jcu-bg--darkblue-50pc">.jcu-bg--darkblue-50pc</div>
    <div class="jcu-bg--darkblue-75pc">.jcu-bg--darkblue-75pc</div>
    <div class="jcu-bg--darkblue-90pc">.jcu-bg--darkblue-90pc</div>
    <div class="jcu-bg--darkblue-100pc">.jcu-bg--darkblue-100pc</div>
  </div>
  <div class="col-xs-3">
    <div class="jcu-bg--black-25pc">.jcu-bg--black-25pc</div>
    <div class="jcu-bg--black-50pc">.jcu-bg--black-50pc</div>
    <div class="jcu-bg--black-75pc">.jcu-bg--black-75pc</div>
    <div class="jcu-bg--black-90pc">.jcu-bg--black-90pc</div>
    <div class="jcu-bg--black-100pc">.jcu-bg--black-100pc</div>
  </div>
  <div class="col-xs-3">
    <div class="jcu-bg--white-25pc">.jcu-bg--white-25pc</div>
    <div class="jcu-bg--white-50pc">.jcu-bg--white-50pc</div>
    <div class="jcu-bg--white-75pc jcu-bg--inverse">.jcu-bg--white-75pc</div>
    <div class="jcu-bg--white-90pc jcu-bg--inverse">.jcu-bg--white-90pc</div>
    <div class="jcu-bg--white-100pc jcu-bg--inverse">.jcu-bg--white-100pc</div>
  </div>
</div>

### Gradients

{% callout warning %}
At this stage, the gradient backgrounds do not feature transparencies for
accessibility reasons.
{% endcallout %}

{% example html %}
<div class="jcu-bg--gradient-blue">.jcu-bg--gradient-blue</div>
<div class="jcu-bg--gradient-blue-reverse">.jcu-bg--gradient-blue-reverse</div>
<div class="jcu-bg--gradient-orange">.jcu-bg--gradient-orange</div>
<div class="jcu-bg--gradient-orange-reverse">.jcu-bg--gradient-orange-reverse</div>
<div class="jcu-bg--gradient-green">.jcu-bg--gradient-green</div>
<div class="jcu-bg--gradient-green-reverse">.jcu-bg--gradient-green-reverse</div>
<div class="jcu-bg--gradient-red">.jcu-bg--gradient-red</div>
<div class="jcu-bg--gradient-red-reverse">.jcu-bg--gradient-red-reverse</div>
{% endexample %}

### Inverting text

Use the `.jcu-bg--inverse` class to invert the text colour within
difficult-to-read overlays.

<div class="jcu-bg-examples">
  <div class="jcu-bg--white-50pc jcu-bg--inverse">
    <h2>White, 50% opacity</h2>
    <p>This uses the inverted text colour for readability.</p>
  </div>
</div>

{% highlight html %}
<div class="jcu-bg--white-50pc jcu-bg--inverse">
  <h2>White, 50% opacity</h2>
  <p>This uses the inverted text colour for readability.</p>
</div>
{% endhighlight %}