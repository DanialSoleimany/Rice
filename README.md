For simple and even complex Styling for Readme.md file. You can also use SVG in this simplest way, among other ways.

This is my Readme.md with an example to style. Readme.md:

# Using CSS in Readme.md file

Readme.md files do not allow direct CSS classes injection.

Though, there are several ways you can inject a CSS file or link into your README.md file, I prefer using the SVG files for simple styling or even complex charts and tables. [see my simple `Readme.md` example with SVG styling][1]

## ![plot](./title.svg)

This is a title that can be manipulated.

## ![plot](./subTitle.svg)

This is a sub-title with cyan color but can be manipulated
title.svg:

<svg xmlns="http://www.w3.org/2000/svg" height="80">
    <style src="./style.css" >
        .title {
          transition: fill .3s ease;
          <!-- cursor: works in github not in preview mode -->
          cursor: pointer;
          font-family: Helvetica, sans-serif;
          border-radius: 5px 5px 5px 5px;
          fill:#2c1300;
          text-anchor: middle;
          dominant-baseline: middle;
          font-size: 24px;
        }

    </style>

    <g class="title">
        <rect rx="5" width="100%" height="80"></rect>
        <text x="50%" y="50%" width="" font-weight="bold" fill="yellow" >TypeScript Course</text>
    </g>
</svg>
