---
description: WP Advanced Block Theme needs a compatible theme
---

# Compatible theme

## Back-end part

### # Theme specification file

Your theme has to have a **JSON specification file** which describes some behaviours used by "WP Advanced Block Theme" plugin.

{% hint style="info" %}
**Default location:** themes/active\_theme/theme\_spec.json
{% endhint %}

[View available properties](broken-reference)



***

## Front-end part

### # Front-end code

**PHP Constant:** THEME\_FRONT\_END\_RELATIVE\_PATH

Your theme has to have a specific **front-end directory**.

{% hint style="info" %}
**Default location:** themes/active\_theme/front-end/
{% endhint %}

```php
// Add this code in your wp-config.php file to override default value:
define('THEME_FRONT_END_RELATIVE_PATH', 'front-end');
```



### **# Frontspec** (optionnal)

**PHP Constant:** THEME\_FRONTSPEC\_JSON\_FILENAME

The front-end code inside your theme has to have its **frontpec file**, which works with the previous Theme specification file.

{% hint style="info" %}
**Default location:** themes/active\_theme/front-end/frontspec.json
{% endhint %}

```php
// Add this code in your wp-config.php file to override default value:
define('THEME_FRONTSPEC_JSON_FILENAME', 'frontspec.json');
```



### # Front-end views

**PHP Constant:** THEME\_VIEW\_ROOT\_LOCATION

"WP Advanced Block Theme" plugin uses **Twig Template Engine** to render content.\
The front-end code inside your theme has to support Twig, and has to contain a sub-directory with views.\
Each view is a sub-directory with:

* .twig file
* viewspec JSON file

{% hint style="info" %}
**Default location:** themes/active\_theme/front-end/src/views/
{% endhint %}

```php
// Add this code in your wp-config.php file to override default value:
define('THEME_VIEW_ROOT_LOCATION', 'src/views/');
```



### # Front-end components use as Gutenberg Block

**PHP Constant:** COMPONENTS\_RELATIVE\_PATH

The front-end code inside your theme has to support Twig, and has to contain a sub-directory with views, and sub-directories for each components used as Gutenberg Block.

{% hint style="info" %}
**Default location:** themes/active\_theme/front-end/src/views/components/
{% endhint %}

```php
// Add this code in your wp-config.php file to override default value:
define('COMPONENTS_RELATIVE_PATH', 'components/');
```
