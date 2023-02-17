# Compatible theme

{% hint style="warning" %}
**WP Advanced Block Theme** needs a compatible theme.
{% endhint %}

## Theme specification file

Your theme has to have a **JSON specification file** which describes some behaviors used by "WP Advanced Block Theme" plugin.

{% hint style="info" %}
**Default location:** themes/active\_theme/theme\_spec.json
{% endhint %}

##

## Front-end code

Your theme has to have a specific **front-end directory**.

{% hint style="info" %}
**Default location:** themes/active\_theme/front-end/
{% endhint %}

## ****

## **Frontspec**

The front-end code inside your theme has to have its **frontpec file**, which works with the previous Theme specification file.

{% hint style="info" %}
**Default location:** themes/active\_theme/front-end/src/views/
{% endhint %}

##

## Front-end view

"WP Advanced Block Theme" plugin uses **Twig Template Engine** to render content.\
The front-end code inside your theme has to support Twig, and has to contain a sub-directory with views (.twig files).

_**Default location:** themes/active\_theme/front-end/src/views/_

__

_****_

__

__
