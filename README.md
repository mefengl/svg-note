# svg-note

## colorful outline 

![colorful outline](svg/colorful_outline.svg)

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="50" height="50">
  <defs>
    <linearGradient id="grad11" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#007BFF;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#F24646;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#F0AC5B;stop-opacity:1" />
    </linearGradient>
  </defs>
  <rect x="5" y="5" width="40" height="40" fill="transparent" rx="10" ry="10" stroke-width="2" stroke="url(#grad11)" />
</svg>
```
