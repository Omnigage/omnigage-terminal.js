# Omnigage Terminal

This repository is for manually implementing the static resources of Terminal.

Note: The embed code generated when creating a Terminal under account settings is the quickest and easiest method of implementation.

## Getting Started

1. Download the latest release: https://github.com/omnigage/omnigage-terminal.js/releases
2. Obtain a terminal ID from your account.

## Install

Start by extracting the contents of the release.

- See `index.html` for example of including JavaScript and CSS assets
- After the JavaScript import, define the terminal ID using the JavaScript API:
```html
    <script type="text/javascript">
      Omnigage.terminal.config({
        terminalId: '<insert-terminal-id>'
      });
    </script>
```

If you have any questions or need support, feel free to contact us here: https://help.omnigage.com/
