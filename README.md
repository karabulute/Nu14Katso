# KATSO
a Modern Theme for **Shopware 6**

## Installation
- refresh plugins list
```bash
bin/console plugin:refresh
```

- install and then activate the Theme Plugin
```bash
bin/console plugin:install --activate Nu14Katso
```

- assign the NPS theme to sales channels (--all flag will assign theme to all sales channels).
```bash
bin/console theme:change Nu14Katso --all
```

It might be necessary to rebuilt theme if storefront view is broken by:
```bash
bin/console theme:compile 
```

To assign theme to channels you can also use interactive mode:
```bash
bin/console theme:change Nu14Katso
```

**via Admin Panel** go to `Settings > System > Plugins`.
In **My plugins** box install and activate **Katso** then assign to chosen sales channels.
