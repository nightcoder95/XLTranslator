# XLTranslator

**XLTranslator** is a Python-based tool that automates the translation of Excel files. It reads data from spreadsheets and translates it to the target language using an AI-driven approach. This utility is perfect for localization projects, where multiple languages need to be supported in large datasets.

## Features
- **Automated Translation**: Uses AI models to translate content in Excel files (.xlsx).
- **Batch Processing**: Supports translating multiple rows or sheets in one go.
- **Customizable**: Allows you to specify source and target languages.
- **Easy to Use**: Simple command-line interface for efficient workflow integration.
- **Supports Various Translation APIs**: Currently works with DeepL, Google Translate, and other APIs.

## Requirements
- Python 3.x
- Required packages: `openpyxl`, `deepl`, `googletrans`, etc.

You can install the dependencies using:
```bash
pip install -r requirements.txt
```

## Installation

To install XLTranslator, clone the repository and navigate to the project directory:

```bash
git clone https://github.com/nightcoder95/XLTranslator.git
cd XLTranslator
```

Next, install the required Python packages:

```bash
pip install -r requirements.txt
```

## Usage

To translate an Excel file, simply run the following command in the terminal:

```bash
python xltranslator.py --input input_file.xlsx --output output_file.xlsx --target fr
```

Where:
- `--input` is the path to the Excel file to be translated.
- `--output` is the path to save the translated file.
- `--target` specifies the target language (e.g., `fr` for French, `es` for Spanish).

You can also specify the source language with `--source`, but by default, it will auto-detect the language.

## Example

```bash
python xltranslator.py --input data.xlsx --output translated_data.xlsx --source en --target es
```

This command will take the `data.xlsx` file, auto-detect English content, and translate it to Spanish, saving the result in `translated_data.xlsx`.

## Contributing

Feel free to submit issues or pull requests. Please ensure that your code adheres to the project style guidelines and includes appropriate tests.

## License

This project is licensed under the MIT License.
## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)

