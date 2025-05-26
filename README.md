
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

### Align Self
```css
.align-self-auto      /* align-self: auto */
.align-self-start     /* align-self: flex-start */
.align-self-end       /* align-self: flex-end */
.align-self-center    /* align-self: center */
.align-self-baseline  /* align-self: baseline */
.align-self-stretch   /* align-self: stretch */
```

### Flex Fill
```css
.flex-fill        /* flex: 1 1 auto */
.flex-grow-0      /* flex-grow: 0 */
.flex-grow-1      /* flex-grow: 1 */
.flex-shrink-0    /* flex-shrink: 0 */
.flex-shrink-1    /* flex-shrink: 1 */
```

### Flex Wrap
```css
.flex-wrap        /* flex-wrap: wrap */
.flex-nowrap      /* flex-wrap: nowrap */
.flex-wrap-reverse /* flex-wrap: wrap-reverse */
```

## Spacing

Margin and padding utilities using the format: `{property}{sides}-{size}`

### Properties
- `m` - margin
- `p` - padding

### Sides
- `t` - top
- `b` - bottom
- `s` - start (left in LTR)
- `e` - end (right in LTR)
- `x` - left and right
- `y` - top and bottom
- blank - all sides

### Sizes
- `0` - 0
- `1` - 0.25rem (4px)
- `2` - 0.5rem (8px)
- `3` - 1rem (16px)
- `4` - 1.5rem (24px)
- `5` - 3rem (48px)
- `auto` - auto

```css
.m-0, .m-1, .m-2, .m-3, .m-4, .m-5, .m-auto
.mt-0, .mt-1, .mt-2, .mt-3, .mt-4, .mt-5, .mt-auto
.mb-0, .mb-1, .mb-2, .mb-3, .mb-4, .mb-5, .mb-auto
.ms-0, .ms-1, .ms-2, .ms-3, .ms-4, .ms-5, .ms-auto
.me-0, .me-1, .me-2, .me-3, .me-4, .me-5, .me-auto
.mx-0, .mx-1, .mx-2, .mx-3, .mx-4, .mx-5, .mx-auto
.my-0, .my-1, .my-2, .my-3, .my-4, .my-5, .my-auto

.p-0, .p-1, .p-2, .p-3, .p-4, .p-5
.pt-0, .pt-1, .pt-2, .pt-3, .pt-4, .pt-5
.pb-0, .pb-1, .pb-2, .pb-3, .pb-4, .pb-5
.ps-0, .ps-1, .ps-2, .ps-3, .ps-4, .ps-5
.pe-0, .pe-1, .pe-2, .pe-3, .pe-4, .pe-5
.px-0, .px-1, .px-2, .px-3, .px-4, .px-5
.py-0, .py-1, .py-2, .py-3, .py-4, .py-5
```

### Negative Margins
```css
.m-n1, .m-n2, .m-n3, .m-n4, .m-n5
.mt-n1, .mt-n2, .mt-n3, .mt-n4, .mt-n5
.mb-n1, .mb-n2, .mb-n3, .mb-n4, .mb-n5
.ms-n1, .ms-n2, .ms-n3, .ms-n4, .ms-n5
.me-n1, .me-n2, .me-n3, .me-n4, .me-n5
.mx-n1, .mx-n2, .mx-n3, .mx-n4, .mx-n5
.my-n1, .my-n2, .my-n3, .my-n4, .my-n5
```

## Sizing

### Width
```css
.w-25             /* width: 25% */
.w-50             /* width: 50% */
.w-75             /* width: 75% */
.w-100            /* width: 100% */
.w-auto           /* width: auto */
```

### Height
```css
.h-25             /* height: 25% */
.h-50             /* height: 50% */
.h-75             /* height: 75% */
.h-100            /* height: 100% */
.h-auto           /* height: auto */
```

### Max Width/Height
```css
.mw-100           /* max-width: 100% */
.mh-100           /* max-height: 100% */
```

### Viewport Sizing
```css
.vw-100           /* width: 100vw */
.vh-100           /* height: 100vh */
.min-vw-100       /* min-width: 100vw */
.min-vh-100       /* min-height: 100vh */
```

## Colors

### Text Colors
```css
.text-primary     /* Primary theme color */
.text-secondary   /* Secondary theme color */
.text-success     /* Success color (green) */
.text-danger      /* Danger color (red) */
.text-warning     /* Warning color (yellow) */
.text-info        /* Info color (cyan) */
.text-light       /* Light color */
.text-dark        /* Dark color */
.text-body        /* Body text color */
.text-muted       /* Muted text color */
.text-white       /* White text */
.text-black-50    /* Black with 50% opacity */
.text-white-50    /* White with 50% opacity */
```

### Background Colors
```css
.bg-primary       /* Primary background */
.bg-secondary     /* Secondary background */
.bg-success       /* Success background */
.bg-danger        /* Danger background */
.bg-warning       /* Warning background */
.bg-info          /* Info background */
.bg-light         /* Light background */
.bg-dark          /* Dark background */
.bg-body          /* Body background */
.bg-white         /* White background */
.bg-transparent   /* Transparent background */
```

### Link Colors
```css
.link-primary     /* Primary link color */
.link-secondary   /* Secondary link color */
.link-success     /* Success link color */
.link-danger      /* Danger link color */
.link-warning     /* Warning link color */
.link-info        /* Info link color */
.link-light       /* Light link color */
.link-dark        /* Dark link color */
```

## Typography

### Text Alignment
```css
.text-start       /* text-align: left */
.text-end         /* text-align: right */
.text-center      /* text-align: center */
.text-justify     /* text-align: justify */
```

### Text Transform
```css
.text-lowercase   /* text-transform: lowercase */
.text-uppercase   /* text-transform: uppercase */
.text-capitalize  /* text-transform: capitalize */
```

### Font Weight
```css
.fw-light         /* font-weight: 300 */
.fw-lighter       /* font-weight: lighter */
.fw-normal        /* font-weight: 400 */
.fw-bold          /* font-weight: 700 */
.fw-bolder        /* font-weight: bolder */
```

### Font Style
```css
.fst-italic       /* font-style: italic */
.fst-normal       /* font-style: normal */
```

### Font Size
```css
.fs-1             /* font-size: calc(1.375rem + 1.5vw) */
.fs-2             /* font-size: calc(1.325rem + 0.9vw) */
.fs-3             /* font-size: calc(1.3rem + 0.6vw) */
.fs-4             /* font-size: calc(1.275rem + 0.3vw) */
.fs-5             /* font-size: 1.25rem */
.fs-6             /* font-size: 1rem */
```

### Line Height
```css
.lh-1             /* line-height: 1 */
.lh-sm            /* line-height: 1.25 */
.lh-base          /* line-height: 1.5 */
.lh-lg            /* line-height: 2 */
```

### Text Decoration
```css
.text-decoration-none         /* text-decoration: none */
.text-decoration-underline    /* text-decoration: underline */
.text-decoration-line-through /* text-decoration: line-through */
```

### Text Wrap
```css
.text-wrap        /* white-space: normal */
.text-nowrap      /* white-space: nowrap */
.text-break       /* word-wrap: break-word */
```

## Position

```css
.position-static    /* position: static */
.position-relative  /* position: relative */
.position-absolute  /* position: absolute */
.position-fixed     /* position: fixed */
.position-sticky    /* position: sticky */
```

### Top/Bottom/Start/End
```css
.top-0, .top-50, .top-100
.bottom-0, .bottom-50, .bottom-100
.start-0, .start-50, .start-100
.end-0, .end-50, .end-100
```

### Translate
```css
.translate-middle    /* transform: translateX(-50%) translateY(-50%) */
.translate-middle-x  /* transform: translateX(-50%) */
.translate-middle-y  /* transform: translateY(-50%) */
```

## Borders

### Border
```css
.border           /* border: 1px solid #dee2e6 */
.border-0         /* border: 0 */
.border-top       /* border-top: 1px solid #dee2e6 */
.border-top-0     /* border-top: 0 */
.border-end       /* border-right: 1px solid #dee2e6 */
.border-end-0     /* border-right: 0 */
.border-bottom    /* border-bottom: 1px solid #dee2e6 */
.border-bottom-0  /* border-bottom: 0 */
.border-start     /* border-left: 1px solid #dee2e6 */
.border-start-0   /* border-left: 0 */
```

### Border Colors
```css
.border-primary   /* border-color: primary */
.border-secondary /* border-color: secondary */
.border-success   /* border-color: success */
.border-danger    /* border-color: danger */
.border-warning   /* border-color: warning */
.border-info      /* border-color: info */
.border-light     /* border-color: light */
.border-dark      /* border-color: dark */
.border-white     /* border-color: white */
```

### Border Width
```css
.border-1         /* border-width: 1px */
.border-2         /* border-width: 2px */
.border-3         /* border-width: 3px */
.border-4         /* border-width: 4px */
.border-5         /* border-width: 5px */
```

### Border Radius
```css
.rounded          /* border-radius: 0.375rem */
.rounded-0        /* border-radius: 0 */
.rounded-1        /* border-radius: 0.25rem */
.rounded-2        /* border-radius: 0.5rem */
.rounded-3        /* border-radius: 1rem */
.rounded-circle   /* border-radius: 50% */
.rounded-pill     /* border-radius: 50rem */

.rounded-top      /* border-top-left-radius, border-top-right-radius */
.rounded-end      /* border-top-right-radius, border-bottom-right-radius */
.rounded-bottom   /* border-bottom-left-radius, border-bottom-right-radius */
.rounded-start    /* border-top-left-radius, border-bottom-left-radius */
```

## Float

```css
.float-start      /* float: left */
.float-end        /* float: right */
.float-none       /* float: none */
```

### Responsive Float
```css
.float-sm-start   /* float: left on small screens and up */
.float-md-end     /* float: right on medium screens and up */
.float-lg-none    /* float: none on large screens and up */
```

## Overflow

```css
.overflow-auto     /* overflow: auto */
.overflow-hidden   /* overflow: hidden */
.overflow-visible  /* overflow: visible */
.overflow-scroll   /* overflow: scroll */
```

### Overflow X/Y
```css
.overflow-x-auto     /* overflow-x: auto */
.overflow-x-hidden   /* overflow-x: hidden */
.overflow-x-scroll   /* overflow-x: scroll */
.overflow-y-auto     /* overflow-y: auto */
.overflow-y-hidden   /* overflow-y: hidden */
.overflow-y-scroll   /* overflow-y: scroll */
```

## Shadow

```css
.shadow-none      /* box-shadow: none */
.shadow-sm        /* box-shadow: 0 .125rem .25rem rgba(0, 0, 0, .075) */
.shadow           /* box-shadow: 0 .5rem 1rem rgba(0, 0, 0, .15) */
.shadow-lg        /* box-shadow: 0 1rem 3rem rgba(0, 0, 0, .175) */
```

## Visibility

```css
.visible          /* visibility: visible */
.invisible        /* visibility: hidden */
```

## Background

### Background Image
```css
.bg-gradient      /* background-image: linear-gradient() */
```

### Background Position
```css
.bg-center        /* background-position: center */
.bg-top           /* background-position: top */
.bg-bottom        /* background-position: bottom */
.bg-start         /* background-position: left */
.bg-end           /* background-position: right */
```

### Background Size
```css
.bg-cover         /* background-size: cover */
.bg-contain       /* background-size: contain */
```

### Background Repeat
```css
.bg-repeat        /* background-repeat: repeat */
.bg-no-repeat     /* background-repeat: no-repeat */
```

## Opacity

```css
.opacity-0        /* opacity: 0 */
.opacity-25       /* opacity: 0.25 */
.opacity-50       /* opacity: 0.5 */
.opacity-75       /* opacity: 0.75 */
.opacity-100      /* opacity: 1 */
```

## Z-Index

```css
.z-n1             /* z-index: -1 */
.z-0              /* z-index: 0 */
.z-1              /* z-index: 1 */
.z-2              /* z-index: 2 */
.z-3              /* z-index: 3 */
```

## Gap (Grid/Flexbox)

```css
.gap-0            /* gap: 0 */
.gap-1            /* gap: 0.25rem */
.gap-2            /* gap: 0.5rem */
.gap-3            /* gap: 1rem */
.gap-4            /* gap: 1.5rem */
.gap-5            /* gap: 3rem */

.row-gap-0        /* row-gap: 0 */
.row-gap-1        /* row-gap: 0.25rem */
.row-gap-2        /* row-gap: 0.5rem */
.row-gap-3        /* row-gap: 1rem */
.row-gap-4        /* row-gap: 1.5rem */
.row-gap-5        /* row-gap: 3rem */

.column-gap-0     /* column-gap: 0 */
.column-gap-1     /* column-gap: 0.25rem */
.column-gap-2     /* column-gap: 0.5rem */
.column-gap-3     /* column-gap: 1rem */
.column-gap-4     /* column-gap: 1.5rem */
.column-gap-5     /* column-gap: 3rem */
```

## Responsive Breakpoints

All utilities can be made responsive by adding breakpoint suffixes:

- `sm` - Small devices (≥576px)
- `md` - Medium devices (≥768px)
- `lg` - Large devices (≥992px)
- `xl` - Extra large devices (≥1200px)
- `xxl` - Extra extra large devices (≥1400px)

### Example Usage
```css
.d-none.d-md-block    /* Hidden on small screens, visible on medium and up */
.text-center.text-md-start /* Centered on small screens, left-aligned on medium and up */
.mb-3.mb-lg-5         /* Margin bottom 3 on small screens, 5 on large and up */
```

## Important Notes

1. **!important**: All utility classes use `!important` to ensure they override component styles.

2. **RTL Support**: Bootstrap 5 includes built-in RTL support. Use `start`/`end` instead of `left`/`right` for better RTL compatibility.

3. **Custom Properties**: Many utilities now use CSS custom properties (CSS variables) for easier theming.

4. **Utilities API**: Bootstrap 5 includes a utilities API for generating custom utility classes.

## Resources

- [Official Bootstrap Documentation](https://getbootstrap.com/docs/5.3/utilities/api/)
- [Bootstrap Utilities on GitHub](https://github.com/twbs/bootstrap/tree/main/scss/utilities)

---

*This cheat sheet is based on Bootstrap 5.3 documentation. For the most up-to-date information, always refer to the official Bootstrap documentation.*
