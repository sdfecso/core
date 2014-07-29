# Core module

Core module keeps dependencies and customizations for each Drupal solution.

xTuple provides 3 types of the projects and for each of them we have different number of modules that needed.
Core module is used for handling specific settings, customizations and dependencies on project-level.

## Usage

1. __Download__ default Core module depending on type of the project:
 + `master` branch for Drupal-only solution;
 + `erp` branch for ERP-connected solution (no-commerce);
 + `commerce` branch for xTuple Commerce solution;
2. Copy code of the module to the `sites/project/modules/xtuple` directory, so Core module will be under project-level git repository control.
3. Work with module as with any other Drupal modules, adding functions to customize exact project.
