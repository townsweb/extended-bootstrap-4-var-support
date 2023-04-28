The file `_functions-override.scss` contains the custom functions to handle color conversions within sass and bootstrap.

Bootstrap does not like its sass variables set to css custom properties, e.g. `var(--primary)`. If you use the code snippets below, you can do so, under some conditions.

In the most basic case, you should provide your color variables using the hsl format.

If you insert this using javascript, you can use the script `apply-colors.jsx` to let js handle the conversion from hex or rgb to hsl.

Reference the `main.scss` file to import the files in the correct order.


Original gist can be found here.
https://gist.github.com/518a511b2b2f6b96c4f429b3af2f169a