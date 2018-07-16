### Link Historical Names
A custom module for the Artechne project that adds the functionality to (semi-)automatically link Historical Names to records.

Modules, in Drupal (7), reside at `sites/all/modules`.
More on how to create custom modules [here](https://www.drupal.org/docs/7/creating-custom-modules/getting-started).

The module adds a tab under 'Content', 'Link Historical Names'. 
It also adds a custom permissions (under 'People', the tab 'Permissions'), that can be used to enable the module only for certain users.

More detail on how the code does its work exactly can be found in the `.module` file, which is just plain php (but without the closing tag!!).
