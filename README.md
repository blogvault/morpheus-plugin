# Morpheus Plugin

## Introduction

The Morpheus Plugin ensures uninterrupted WordPress core and plugin updates by providing a failover mechanism. If your WordPress site is unable to connect to the official WordPress.org update server, Morpheus steps in to mirror the updates, ensuring your site remains up-to-date even during connectivity issues.

## Installation

1. **Download the Plugin**:  
   Download the latest version of the Morpheus plugin from the [Releases page](https://github.com/blogvault/morpheus-plugin/releases).

2. **Install via WordPress Dashboard**:
   - Go to your WordPress admin dashboard.
   - Navigate to `Plugins` > `Add New`.
   - Click `Upload Plugin` and select the `.zip` file you downloaded from the releases.
   - Click `Install Now` and activate the plugin once the installation is complete.

## How It Works

Once the plugin is activated, it will monitor the connection between your WordPress site and WordPress.org for updates. If the connection fails:

1. The plugin will automatically switch to the Morpheus mirror server.
2. Updates (WordPress core or plugins) will be fetched from the mirror.
3. Once the connection to WordPress.org is restored, the plugin will automatically switch back to the default update source.

## Features

- **Seamless Failover**: Automatically switches to the Morpheus mirror if the WordPress.org update server is unreachable.
- **Supports Core and Plugin Updates**: Ensures both WordPress core and plugin updates continue even during connectivity issues.

## GitHub Releases

We use GitHub's release system to distribute new versions of the Morpheus Plugin. To download the latest version, visit the [Releases page](https://github.com/blogvault/morpheus-plugin/releases).

- **Versioning**: Follows semantic versioning.
- **Changelog**: Each release will include a changelog for easy tracking of changes and updates.

## Learn More

For more information about Morpheus, including details on how the service works, visit the main [Morpheus repository](https://github.com/blogvault/morpheus).

## License

Morpheus Plugin is licensed under the [MIT License](LICENSE).
