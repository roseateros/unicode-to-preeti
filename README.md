# Unicode-Preeti Text Converter

## Overview

This is a web-based utility for converting text between Unicode and Preeti encoding formats, specifically designed for Nepali language text processing. The application allows users to seamlessly convert text between two different character encodings, which is particularly useful for working with legacy Devanagari text documents.

## Features

- Convert text from legacy Preeti encoding to Unicode
- Convert text from Unicode back to Preeti encoding
- Handles complex Devanagari character transformations
- Supports Nepali numerals and special characters
- Preserves text formatting and diacritical marks

## How It Works

The converter uses two main functions:

1. `convert_to_unicode()`: Transforms text from Preeti encoding to Unicode
2. `convert_to_Preeti()`: Converts Unicode text back to Preeti encoding

Both functions use extensive character mapping arrays to handle the intricate transformations between encoding systems.

## Technical Details

### Conversion Process

- Uses JavaScript arrays to map characters between encodings
- Implements multiple replacement passes to handle special cases
- Corrects positioning of matras (vowel marks)
- Handles special glyphs and ligatures

### Supported Characters

- Full range of Devanagari characters
- Nepali numerals
- Special symbols
- Nukta variants
- Complex consonant clusters

## Usage

1. Enter text in the source text area
2. Select conversion direction (Unicode to Preeti or vice versa)
3. Click convert
4. View the converted text in the target text area

## Limitations

- Requires manual text input
- Works best with clean, well-formed text
- May require manual corrections for extremely complex text layouts

## Browser Compatibility

- Works in modern web browsers
- JavaScript must be enabled

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

[Specify your license here, e.g., MIT, GPL]

## Credits

Developed for the Nepali language text processing community.
