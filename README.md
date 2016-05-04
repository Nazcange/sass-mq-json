# sass-mq-json

Inspired by [SassyJSON](https://github.com/HugoGiraudel/SassyJSON) and [o-grid](https://github.com/Financial-Times/o-grid/blob/master/main.scss#L25).
Working in harmony with  [sass-mq](https://github.com/sass-mq/sass-mq). 

Useful to provide the breakpoints list to the JavaScript.

``$mq-breakpoints`` should be a map of breakpoint like in sass-mq.

Use ``@include mq-expose();`` to provide the current breakpoint through ``body::before`` and expose the list through ``html::before`` to the JavaScript.

``@function mq-json`` generate a json with the breakpoints list.
