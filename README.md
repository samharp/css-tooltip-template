# css-tooltip-template
A simple CSS tooltip created using a custom HTML attribute

Concept: Tooltip is created with an `:after` psuedo-element with content equal to the value of an attribute `data-tooltip`.

__Note:__ This tooltip will only populate with text. Because of the single psuedo element of `:after`, specific words will not be able to be styled by themselves (such as bold, underlined, or italicized). Leveraging the `:before` tag in conjunction can create more possibilities, but this can become quickly difficult to manage.
