# Welcome to awesome documentation page

Disclaimer: We are not trying to replace Bootstrap or Foundation or any of them. We are only trying to demostrate how you can build you own custom framework so your websites would easily be unique and you have more controls.

We will go over these sections

- Layout
- - container
- - grid
- - flex
- Typography
- - text
- - color
- Components
- - navbar
- - button
- Utilities
- - margin
- - padding
- - background

## Layout

These set of classes are used for managing spaces throwing things around of your web page.

### container classes

If you need a centralized container, this is the class to use. Just like bootstrap's container. But unlike with bootstrap, you have the freedom to choose whether you want to use 95% or 75% of the space.

> .container-1 gives you a 95% centralized container.
> You can choose any number from 1 to 5 for 95%, 90%, 85%, 80%, 75% respectively

```html
<section class="container-2"></section>
```

### grid classes

These classes gives the power to slice up your page into 12 sections and then choose how many you want to use at a particular time.

To do this, wrap your div in a container of class row (for horizontal) grid or column (for vertical grid). Then give each direct child a class of box-<break-point identifier>-number. You also have access to a gutter class g-1 through g-5 for 10px to 50px gutters respecively.

Example 1:
I want a horizontal grid 2 sections; 1 taking 8 slot, the other taking 4 slots and having a gutter of 30px between them.

```html
<div class="row g-3">
  <div class="box-sm-8 box-xs-12">
    I occupy 8 out of 12
  </div>
  <div class="box-sm-4 box-xs-12">
    I occupy 4 out of 12
  </div>
</div>
```

### flex classes

These classes gives you the powers of CSS flexbox. You can throw things around as you wish - hahahaha.

To use it, give the parent container a class of flex-row for horizontal direction or flex-column for vertical direction. You can append reverse (eg: flex-row-reverse) to flip the start from left to right for row or top to bottom for column.

You can use popular flex properties like;

- justify-content-
- - start (flex-start)
- - end (flex-end)
- - center (center)
- - between (space-between)
- - around (space-around)

- align-items-
- - start (flex-start)
- - end (flex-end)
- - center (center)
- - baseline (baseline)
- - stretch (stretch)

- align-self-
- - start (flex-start)
- - end (flex-end)
- - center (center)
- - baseline (baseline)
- - stretch (stretch)

## Typography

These sets of classes helps you apply colors and align texts.

### text classes

Just apply class text-align-<where> and your text gets aligns there. The options avaliable are;

- left
- right
- justify
- center

### color classes

## Components

### navbar classes

### button classes

## Utilities

These ones might look trivial but can help you avoid visiting you CSS file that often. You can choose any number from 1 to 5 where 1 respresents 10px and 5 represents 50px when dealing with margins and paddings.

### margin classes

This offers you the options to target either all round, top, bottom, right, left, x-axis or y-axis.

Options avaliable are:

- m-<num>
- m-t-<num>
- m-r-<num>
- m-b-<num>
- m-l-<num>
- m-h-<num>
- m-v-<num>

### Padding classes

This offers you the options to target either all round, top, bottom, right, left, x-axis or y-axis.

Options avaliable are:

- p-<num>
- p-t-<num>
- p-r-<num>
- p-b-<num>
- p-l-<num>
- p-h-<num>
- p-v-<num>

### background classes
