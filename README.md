# Responsive Spaces

This is a set of responsive spacing classes.  Unfortunately, most spacing classes out there aren't responsive, 
so I threw this together modelled after bootstrap's media queries (mobile-first).

## Basics:

**padding/margin + direction + amount + -screensize**

## Syntax:

pan-xs = "padding all none (at extra small screensize)"

pax-xs = "padding all extra small (at extra small screensize)"

pas-xs = "padding all small (at extra small screensize)"

pam-xs = "padding all medium (at extra small screensize)"

pal-xs = "padding all large (at extra small screensize)"


**Possible directions:** all/top/right/bottom/left

**Possible breakpoints:** xs, sm, md, lg


## Examples:

Padding top large at the extra small screensize, and padding top none at the medium screensize.

```
<div class="ptl-xs ptn-md">
</div>
```

Padding left none at the extra small screensize, and padding left medium at the small screensize.

```
<div class="pln-xs plm-sm">
</div>
```

Padding all large at the extra small screensize, and padding all extra large at the small screensize.

```
<div class="pal-xs paxl-sm">
</div>
```