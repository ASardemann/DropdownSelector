# DropdownSelector Plugin

A Shopware 6 plugin that adds a customizable dropdown selector to the buy widget in the storefront.

## Features

- Adds a customizable dropdown selector to the product buy widget
- Seamlessly integrates with the Shopware 6 storefront
- Customizable styling through SCSS
- Easy to configure through the Shopware admin panel

## Requirements

- Shopware 6.4.0.0 or higher
- PHP 7.4 or higher

## Installation

### Via Composer (recommended)

1. Change to your Shopware installation directory
```bash
cd /path/to/shopware
```

2. Install the plugin via Composer
```bash
composer require vendor/dropdownselector
```

3. Install and activate the plugin
```bash
bin/console plugin:install DropdownSelector
bin/console plugin:activate DropdownSelector
```

4. Clear the cache
```bash
bin/console cache:clear
```

### Manual Installation

1. Download the latest release
2. Extract the archive to `custom/plugins/DropdownSelector` in your Shopware installation
3. Install and activate the plugin through the Shopware Admin Panel:
   - Go to Settings > System > Plugins
   - Find "DropdownSelector" in the plugin list
   - Click "Install" and then "Activate"
4. Clear the cache through the Shopware Admin Panel

## Configuration

1. Go to Settings > System > Plugins
2. Find "DropdownSelector" in the plugin list
3. Click on "Config" to adjust the plugin settings

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

For questions and support, please contact 3close Agency UG (haftungsbeschränkt) at:
[https://www.3close.de/answers/contact/](https://www.3close.de/answers/contact/)

You can also open an issue on GitHub for technical inquiries.

## Development

This plugin was developed with the assistance of Microsoft Copilot, leveraging AI technology to ensure high-quality code standards and best practices.
