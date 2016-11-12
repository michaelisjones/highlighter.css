# highlighter.css

CSS classes for highlighted-text effects. CSS files in `dist` folder: `highlighter.css` or `highlighter.min.css`

## Classes

**.highlighter** – Required class on parent element.

**.word** – Word container, required on every word.

**.word.highlighted** – A highlighted word.

**.word.correct** – A correct word.

**.word.incorrect** – An incorrect word.

## Example

See `demo/demo.html` for implementation example.

~~~
<p class="highlighter">
    <span class="word">one</span>                       <!-- Word -->
    <span class="word">sunny</span>
    <span class="word highlighted">morning</span>       <!-- Highlighted Word -->
    <span class="word highlighted correct">ena</span>   <!-- Correct Word -->
    <span class="word highlighted incorrect">set</span> <!-- Incorrect Word -->
</p>
~~~

![example](https://github.com/michaelisjones/highlighter.css/blob/master/demo/example.png)

## Build

Build script requires [SassC](https://github.com/sass/sassc) executable. Alternatively, SCSS source can be built using [SassMeister](http://www.sassmeister.com/).

CSS output minified (.min.css) using [cssnano](http://cssnano.co/).
