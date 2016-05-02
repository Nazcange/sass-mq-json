# sass-mq-json

Inspired by [SassyJSON](https://github.com/HugoGiraudel/SassyJSON) and working in harmony with  [sass-mq](https://github.com/sass-mq/sass-mq). 

Useful to provide the breakpoints list to the JavaScript.

Use ``_base-html.scss`` to provide the current breakpoint through ``body::before`` and  expose the list through ``html::before`` to the JavaScript.

``@mixin mq-json`` generate a json with the breakpoints list. This list will be in the ``content``.

This will be expose by ``_base-html.scss`` in the pseudo-element ``html::before``.

``body::before`` expose the current breakpoint.

``@mixin mq-json`` is coded for the compiler sass Ruby, ``@mixin mq-json-libsass`` is coded for the compiler libsass.
