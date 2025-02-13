# KeystoneJS V4 - MongoDB 6 Compatibility

This package is designed to maintain [KeystoneJS V4](https://v4.keystonejs.com/) as many cloud services have enforced migration to MongoDB 6, while [KeystoneJS](https://v4.keystonejs.com/) does not support MongoDB 6.

## How to Use This Package for Migration to MongoDB 6

To migrate your KeystoneJS V4 project to MongoDB 6, follow these steps:

1. Uninstall the existing Keystone package:
   ```sh
   npm uninstall keystone
   ```
2. Install this package as an alias:
   ```sh
   npm install keystone@npm:keystone-v4-mongodb6
   ```

## Why Maintain KeystoneJS V4?

While [KeystoneJS V5](https://v5.keystonejs.com/) and [KeystoneJS V6](https://keystonejs.com/) exist, neither is a seamless replacement for V4 in certain cases:

- **[KeystoneJS V5](https://v5.keystonejs.com/):** Does not include nested fields, making migration difficult.
- **[KeystoneJS V6](https://keystonejs.com/):** Does not support MongoDB, making it unsuitable for existing MongoDB-based projects.

## Troubleshooting

If you encounter any issues, feel free to open an issue on GitHub. Contributions and bug reports are welcome!

