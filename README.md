# highlighter.css

CSS classes for highlighted-text effects.

## Usage

The CSS files in the `dist` folder are compiled and ready to use: `highlighter.css` or `highlighter.min.css`.

### Recommended Font Properties

These classes do not set any font properties. Here are the recommended font properties for best outcomes:

~~~
font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
line-height: 1.8;
word-spacing: 0.25em;
~~~


### Classes

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
