# Product tour

An interactive tour which helps onboard new users to Mautic

## Installation

Reload plugins on the plugin page, and the tours will be available. 

After installing or updating the plugin, regenerate Mautic's assets so `tour.js` and `tour.css` are included in `media/js/app.js` and `media/css/app.css`:

```bash
php bin/console mautic:assets:generate
```

## Development info

This plugin leverages the [shepherdjs](https://www.shepherdjs.dev/) library to add tours to Mautic. 
Tours are created inside the `Assets/js/tour.js` file.
