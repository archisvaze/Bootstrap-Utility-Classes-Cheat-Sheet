
# Bootstrap Utility Classes Cheat Sheet

A comprehensive reference for Bootstrap 5 utility classes based on the official documentation.

## Table of Contents
- [Display](#display)
- [Flexbox](#flexbox)
- [Spacing](#spacing)
- [Sizing](#sizing)
- [Colors](#colors)
- [Typography](#typography)
- [Position](#position)
- [Borders](#borders)
- [Float](#float)
- [Overflow](#overflow)
- [Shadow](#shadow)
- [Visibility](#visibility)
- [Background](#background)
- [Opacity](#opacity)
- [Z-Index](#z-index)

## Display

Control the display property of elements.

```css
.d-none           /* display: none */
.d-inline         /* display: inline */
.d-inline-block   /* display: inline-block */
.d-block          /* display: block */
.d-table          /* display: table */
.d-table-cell     /* display: table-cell */
.d-table-row      /* display: table-row */
.d-flex           /* display: flex */
.d-inline-flex    /* display: inline-flex */
.d-grid           /* display: grid */
.d-inline-grid    /* display: inline-grid */
```

### Responsive Display
Add breakpoint suffixes: `-sm`, `-md`, `-lg`, `-xl`, `-xxl`
```css
.d-sm-none        /* Hidden on small screens and up */
.d-md-block       /* Block display on medium screens and up */
.d-lg-flex        /* Flex display on large screens and up */
```

## Flexbox

### Flex Direction
```css
.flex-row         /* flex-direction: row */
.flex-row-reverse /* flex-direction: row-reverse */
.flex-column      /* flex-direction: column */
.flex-column-reverse /* flex-direction: column-reverse */
```

### Justify Content
```css
.justify-content-start    /* justify-content: flex-start */
.justify-content-end      /* justify-content: flex-end */
.justify-content-center   /* justify-content: center */
.justify-content-between  /* justify-content: space-between */
.justify-content-around   /* justify-content: space-around */
.justify-content-evenly   /* justify-content: space-evenly */
```

### Align Items
```css
.align-items-start    /* align-items: flex-start */
.align-items-end      /* align-items: flex-end */
.align-items-center   /* align-items: center */
.align-items-baseline /* align-items: baseline */
.align-items-stretch  /* align-items: stretch */
```
