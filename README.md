# sass-mq-json

Inspired by [SassyJSON](https://github.com/HugoGiraudel/SassyJSON) aud use with [sass-mq](https://github.com/sass-mq/sass-mq).

Useful to provide the list of the breakpoint to the JavaScript.

Use ``_base-html.scss`` to provide the current breakpoint and expose the list to the JavaScript.

``@mixin mq-json`` generate a json list of the breakpoint in the ``content``.

This will be expose by ``_base-html.scss`` in the pseudo-element ``html::before``.

``body::before`` expose the current breakpoint depending of the breakpoint. 

``@mixin mq-json`` is coded for the compiler sass Ruby, ``@mixin mq-json-libsass`` is coded for the compiler libsass.
