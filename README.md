> 𝕏 Also, follow [DevBySami](https://x.com/DevBySami) on X for updates and to support their amazing work.

[![madewithlove](https://img.shields.io/badge/made_with-%E2%9D%A4-red?style=for-the-badge&labelColor=orange)](https://github.com/FujiwaraChoki/MoneyPrinterV2)

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-Donate-brightgreen?logo=buymeacoffee)](https://www.buymeacoffee.com/fujicodes)  
[![GitHub license](https://img.shields.io/github/license/FujiwaraChoki/MoneyPrinterV2?style=for-the-badge)](https://github.com/FujiwaraChoki/MoneyPrinterV2/blob/main/LICENSE)  
[![GitHub issues](https://img.shields.io/github/issues/FujiwaraChoki/MoneyPrinterV2?style=for-the-badge)](https://github.com/FujiwaraChoki/MoneyPrinterV2/issues)  
[![GitHub stars](https://img.shields.io/github/stars/FujiwaraChoki/MoneyPrinterV2?style=for-the-badge)](https://github.com/FujiwaraChoki/MoneyPrinterV2/stargazers)  
[![Discord](https://img.shields.io/discord/1134848537704804432?style=for-the-badge)](https://dsc.gg/fuji-community)

An application that automates the process of making money online.  
MoneyPrinterV2 (MPV2) is the second iteration of the MoneyPrinter project—a complete rewrite of the original with an expanded feature set and a modular architecture designed for flexibility and enhanced performance.
<!-- 
> **Note:** MPV2 requires Python 3.9 to function effectively.  
> Watch the YouTube overview [here](https://youtu.be/wAZ_ZSuIqfk). -->

## Features

- [x] Twitter Bot (with CRON Jobs => `scheduler`)
- [x] YouTube Shorts Automater (with CRON Jobs => `scheduler`)
- [x] Affiliate Marketing (Amazon + Twitter)
- [x] Local business discovery & cold outreach

## Versions

MoneyPrinter has been adapted into various versions by the community for the community. Here are some known versions:

- Chinese: [MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo)

If you’re interested in submitting your own version or fork of MoneyPrinter, please open an issue detailing the changes you’ve made.

## Installation

Before getting started, please install [Microsoft Visual C++ Build Tools](https://visualstudio.microsoft.com/de/visual-cpp-build-tools/) to ensure CoquiTTS functions correctly.

> ⚠️ If you plan to contact scraped businesses via e-mail, first install the [Go Programming Language](https://golang.org/).

```bash
git clone https://github.com/FujiwaraChoki/MoneyPrinterV2.git

cd MoneyPrinterV2
# Copy the example configuration and update config.json with your settings
cp config.example.json config.json

# Create a virtual environment
python -m venv venv

# Activate the virtual environment (Windows)
.\venv\Scripts\activate

# Activate the virtual environment (Unix)
source venv/bin/activate

# Install the required packages
pip install -r requirements.txt
```

## Usage

```bash
# Start the application
python src/main.py
```

## Documentation

All relevant documentation can be found [here](docs/).

## Scripts

For easier access to MPV2’s core functionality without user interaction, several scripts are available in the `scripts` directory.  
All scripts should be run from the project’s root directory, for example:
```bash
bash scripts/upload_video.sh
```

## Contributing

Please review [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests. Also, see [docs/Roadmap.md](docs/Roadmap.md) for a list of upcoming features.

## Code of Conduct

For details on the code of conduct and guidelines for contributing, please see [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

## License

MoneyPrinterV2 is licensed under the `Affero General Public License v3.0`. For more details, see [LICENSE](LICENSE).

## Acknowledgments

- [CoquiTTS](https://github.com/coqui-ai/TTS)
- [gpt4free](https://github.com/xtekky/gpt4free)

## Disclaimer

This project is for educational purposes only. The developers are not responsible for any misuse of the provided information. All information on this project is published in good faith and for general informational purposes only. No warranties are made regarding the completeness, reliability, or accuracy of this information. Any action taken based on the information provided (MoneyPrinterV2) is strictly at your own risk, and the developers will not be liable for any losses or damages incurred.