# This is a `laravelcollective/html` drop-in replacement

To use this package instead of `laravelcollective/html` as a perfect drop-in replacement, do this in your project:

1. `composer require rdx/laravelcollective-html`
2. if your project explicitly required `html`: `composer remove laravelcollective/html`

This will install `rdx/laravelcollective-html` and pretend it IS `laravelcollective/html`, and all other packages will believe `laravelcollective/html` is installed, because Composer is awesome.
