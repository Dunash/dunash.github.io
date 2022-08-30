Brief summary

Layout types in CSS - display: property
display sets inner and outer display types. 

<style>
display: inline | inline-block | block | flex | inline-flex | grid | inline-grid; /*etc*/

.example{
display: block;
/* - line breaks before and after the element, width=parent-width  */

display:inline;
 /* - does not generate breaks, width=content-width */

display:inline-block;
 /* - allows to set height and width, top and bottom margins/paddings respected;
does not add a line-break after the element */
}
</style>
