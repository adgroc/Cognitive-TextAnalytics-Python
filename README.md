![Text Analytics](docs/images/text-analytics.png)

# Text Analytics API: Python SDK & Sample

[![Build Status](https://travis-ci.org/lastcoolnameleft/Cognitive-TextAnalytics-Python.svg?branch=master)](https://travis-ci.org/lastcoolnameleft/Cognitive-TextAnalytics-Python)

## Overview
Text Analytics API is a suite of text analytics services built with Azure Machine Learning and offers APIs for sentiment analysis, key phrase extraction and topic detection for English text, as well as language detection for 120 languages.

The solution contains the SDK and a sample application that allows you to enter your API key and text to perform the following actions:
- Language identification
- Sentiment analysis
- Key phrase detection
- Topic detection

## Installation

```bash
pip install cognitive_textanalytics
```

## Development

### Dev Setup

NOTE: Assumes you've already run `virtualenv venv`.

```bash
# Initial setup
. ./venv/bin/activate

# Install requirements
make init

# Validate
make test
```

## Installation from Source Code

```bash
make install
```

## Contributing
Contributions are welcome. Feel free to file issues and pull requests on the repo and we'll address them as we can. Learn more about how you can help on our [Contribution Rules & Guidelines](/CONTRIBUTING.md).

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## License
All Microsoft Cognitive Services SDKs and samples are licensed with the MIT License. For more details, see [LICENSE](/LICENSE.md).

## Developer Code of Conduct
Developers using this project are expected to follow the “Developer Code of Conduct for Microsoft Cognitive Services” at [http://go.microsoft.com/fwlink/?LinkId=698895](http://go.microsoft.com/fwlink/?LinkId=698895).

## Disclaimer
The image, voice, video or text understanding capabilities of the Text Analytics Python SDK and sample use Microsoft Cognitive Services. Microsoft will receive the images, audio, video, and other data that you upload (via this app) for service improvement purposes.

## Report Abuse
To report abuse of the Microsoft Cognitive Services to Microsoft, please visit the Microsoft Cognitive Services website at [https://www.microsoft.com/cognitive-services](https://www.microsoft.com/cognitive-services), and use the "Report Abuse" link at the bottom of the page to contact Microsoft.

## Privacy Policy
For more information about Microsoft privacy policies please see their privacy statement here: [https://go.microsoft.com/fwlink/?LinkId=521839](https://go.microsoft.com/fwlink/?LinkId=521839).
