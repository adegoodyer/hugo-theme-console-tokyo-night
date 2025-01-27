# hugo-theme-console-tokyo-night

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-donate-yellow)](https://www.buymeacoffee.com/adegoodyer)

Minimal terminal styled Hugo theme with colour scheme based on Tokyo Night.

## Installation
```bash
# create new Hugo site
hugo new site example.com

# add theme
git submodule add https://github.com/adegoodyer/hugo-theme-console-tokyo-night.git example.com/themes/hugo-theme-console-tokyo-night

# commit submodule
git add .gitmodules example.com/themes/hugo-theme-console-tokyo-night && \
git commit -m "Added theme submodule"

# update theme
git submodule update --remote --merge

# add theme to `hugo.toml`
theme = "hugo-theme-console-tokyo-night"
```

## Tags

- `latest`: Most recent stable build
- `x.y.z`: Specific version builds (e.g., `2.7.5`)
- `x.y`: Minor version builds (e.g., `2.7`)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- [terminalcss.xyz](https://terminalcss.xyz/)
- [Jonas D](https://github.com/Gioni06/terminal.css)
- [Marcin Mierzejewski](https://github.com/mrmierzejewski)
