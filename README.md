# brands

Brand assets of pixelspringer, the single source for websites, profiles and tools.

| Path                               | Content                     |
| ---------------------------------- | --------------------------- |
| [`ascii/logo.txt`](ascii/logo.txt) | Logo as plain text (ASCII). |

Consumers load files from the raw URL, for example:

```text
https://raw.githubusercontent.com/pixelspringer/brands/main/ascii/logo.txt
```

Current consumers:

- [`pixelspringer/.github`](https://github.com/pixelspringer/.github) copies the ASCII logo into the organization profile.
- [`pixelspringer/zwiebellook-data`](https://github.com/pixelspringer/zwiebellook-data) embeds it as an HTML comment in the index page of data.zwiebellook.de.

Changing a path here breaks these consumers.
