# Omnigage Terminal

This repository is for manually implementing the static resources of Terminal.

Note: The embed code generated when creating a Terminal under account settings is the quickest and easiest method of implementation.

## Getting Started

1. Download the latest release: https://github.com/omnigage/omnigage-terminal.js/releases
2. Obtain a terminal ID from your account.

## Install

Start by extracting the contents of the release.

- Ensure the contents of the release are accessible to your HTML
- Include `omnigage-terminal-api.js` in your HTML
- Define configuration for the `terminalId` and `url` to the `index.html` file included in the release
    - *Note:* For example, replace below "omnigage-terminal/" with the "path/to/your/" assets on your servers 
- Call `.init()`

**Example:**

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Example</title>
  </head>
  <body>
    <script src="omnigage-terminal/assets/omnigage-terminal-api.js"></script>
    <script type="text/javascript">
      let t = Omnigage.terminal;

      t.config({
        terminalId: '<insert-your-terminal-id>',
        url: 'omnigage-terminal/index.html',
      });

      t.init();
    </script>
  </body>
</html>
```

If you have any questions or need support, feel free to contact us here: https://help.omnigage.com/
