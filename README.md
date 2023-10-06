# Drupal-CustomTheme-Menu-Dropdown
Displaying menu icons, menu name, and menu description 

1. Install Menu Item Extras(https://www.drupal.org/project/menu_item_extras)
To add a new icon field to upload icon images for each menu 


2. Create a Custom Drupal Theme:
If you haven't already, create a custom theme for your Drupal site. You can do this by creating a new directory in the themes directory of your Drupal installation and adding the necessary theme files. Make sure your custom theme has its own mytheme.info.yml file.


3. Identify the Menu and menu item extra You Want to Override:
Determine which menu you want to override. You can do this by finding the menu's machine name. You can usually find this in the Drupal admin interface under "Structure" > "Menus."

4. Create a menu and menu extra item extras Override Template:
Inside your custom theme directory, create a template file for the menu you want to override. The template file should follow Drupal's naming conventions. The naming convention for menu templates is usually menu--[menu-name].html.twig. Replace [menu-name] with the machine name of your menu.

For example, if you're overriding a menu named "main-menu," create a file named menu--main-menu.html.twig in your custom theme's template directory.


5. Write Your Custom Menu Markup:
you can write the custom markup for your menu. You'll have access to the menu items and their attributes in this template, allowing you to customize the HTML structure and styling.
