# Symfony & Tailwind CSS Example

This is a supporting example repository for using TailwindCSS within a Symfony project.  The full blog post can be found at https://chrisshennan.com/blog/using-tailwindcss-with-symfony-encore.

## Usage

### Check out the application and install the dependencies
```
# Checkout the repository
git clone https://github.com/chrisshennan/symfony-and-tailwindcss-example.git

# Move to the project directory
cd symfony-and-tailwindcss-example

# Install PHP packages
composer install

# Install node modules
yarn install
```

### Watch for CSS class changes in templates
Run this in a terminal window
```
yarn encore dev --watch
```

### Start a webserver to view the project

```
cd public
php -S localhost:8080
```
Now open your favourite browser and go to http://locahost:8080 and you will see a Symfony application using TailwindCSS.

You can modify the templates (change Tailwind CSS classes) or try other components from https://tailwindui.com/components/preview and the `watch` step above will pick up the changes and update the CSS needed.  You can then refresh your browser and see the changes.