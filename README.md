# css-tooltip-template
A simple CSS tooltip created using a custom HTML attribute

Concept: Tooltip is created with an `:after` psuedo-element with content equal to the value of an attribute `data-tooltip`.

__Note:__ This tooltip will only populate with text. Because of the single psuedo element of `:after`, specific words will not be able to be styled by themselves (such as bold, underlined, or italicized). Leveraging the `:before` tag in conjunction can create more possibilities, but this can become quickly difficult to manage.

Other Notes:
- The position of the tooltip relative to the respective parent can be changed by swapping `bottom` with another position property.
- A small triangle similar to ones seen on traditional tooltips can be added by using a `:before` psuedo element and a combination of border styles. For more information on how to accomplish this, Google "CSS Shapes" (I may also add these types of styles to this repo in the future).
- Because of its absolute positioning, it is possible that on smaller screens, the tooltip may 'fall off' the edge of the browser window. To alleviate this, you can either add responsive styles on different screen sizes, or change the position of the tooltip relative to its parent (i.e. on righthand-side elements, the tooltip shows on the left, etc.)
