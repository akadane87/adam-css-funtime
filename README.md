# adam-css-funtime


Media Queries:

Do mobile/break up CSS in 2 ways:
  1.) Break it up by device: Call 4 seperate style sheets for major device widths
  2.) Break it up by feature + media quieries within style sheet

Example:
  1.) <link rel="stylesheet" media="(max-width: 800px)" href="example.css" />
  2.)<style>
@media (max-width: 600px) {
  .facet_sidebar {
    display: none;
  }
}
</style>

Mobile First....?
http://www.w3schools.com/css/css_rwd_mediaqueries.asp

Control Landscape:
@media only screen and (orientation: landscape) {
    body {
        background-color: lightblue;
    }
}

Why doesn't my site resize on my phone?
<!--<meta name="viewport" content="width=device-width, initial-scale=1"> -->



Responsive Elements + Layout:
(demo fixed widths vs percentages vs viewport heights/widths)

img {
    width: 100%;
    height: auto;
}

Same as...

div {
  width: 100%;
  padding-bottom: 100%;
}
