# brands

Brand assets of pixelspringer, the single source for websites, profiles and tools.

Consumers load files from their raw URL.

| Path                               | Content                     | Raw URL                                                                                                                                                    |
| ---------------------------------- | --------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [`ascii/logo.txt`](ascii/logo.txt) | Logo as plain text (ASCII). | [`https://raw.githubusercontent.com/pixelspringer/brands/main/ascii/logo.txt`](https://raw.githubusercontent.com/pixelspringer/brands/main/ascii/logo.txt) |

Current consumers, started by [`.github/workflows/notify.yml`](.github/workflows/notify.yml) whenever a file in `ascii/` changes:

- [`pixelspringer/.github`](https://github.com/pixelspringer/.github) copies the ASCII logo into the organization profile.
- [`pixelspringer/zwiebellook-data`](https://github.com/pixelspringer/zwiebellook-data) embeds it as an HTML comment in the index page of data.zwiebellook.de.

Changing a path here breaks these consumers. A new consumer needs an entry in `notify.yml` and access for the `DISPATCH_TOKEN` secret.

## License

Brand assets, not open source. See [LICENSE](LICENSE).
