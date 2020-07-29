## Using this starter

Before building for production: You'll need to ensure any file which uses classes from TailwindCSS that you want included in your compiled CSS file are added to the postcss.config.js file under 'content' for PurgeCSS. The current configuration will catch classes used in any .html file within the 'src' folder. PurgeCSS is currently setup to only run when the NODE_ENV is 'production'.

## Extending TailwindCSS

Adding custom classes to Tailwind is easy. Edit the tailwind.config.js file and add any custom classes to the 'theme' -> 'extend' object.  You can see the available classes that can be overwritten in the tailwind-full.config.js within the repo. 