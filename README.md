# FM-to-Unicode

FM-to-Unicode is a straightforward Google Apps Script designed for Google Docs. Its primary function is to convert regular Sinhala fonts, such as FMAbhaya and FMbindumathi, into Unicode fonts.

## Scope

In Sinhala typing, many documents are written using regular Sinhala fonts that require the specific font to be installed on your device for proper viewing, such as FMAbhaya or FMbindumathi. However, when using cloud-based word processors like Google Docs, which do not support third-party fonts, readability becomes an issue. To address this problem, FM-to-Unicode offers a solution by converting these documents into Unicode fonts, ensuring compatibility and readability across different platforms.

## Usage

1. Open your Google Docs document containing Sinhala text in regular fonts.
2. Click on "Extensions" in the menu.
3. Select "FM-to-Unicode" and click "Convert to Unicode."
4. The script will process the document, converting the Sinhala text into Unicode fonts.

## Installation

To use FM-to-Unicode, follow these steps:

1. Open your Google Docs document.
2. Click on "Extensions" in the menu.
3. Select "Apps Script" and paste the script code.
4. Save the script and run it from the "Apps Script" menu.

## Code Explanation

The Apps Script code comprises several functions to facilitate the conversion process. Here's a brief explanation:

- convertToUnicode(): This function is the entry point for the conversion process. It iterates through the document, identifies Sinhala text in regular fonts, and replaces it with Unicode equivalents.

- getSinhalaTextRanges(): A helper function that identifies the ranges of Sinhala text in regular fonts within the document.

- replaceTextInRange(): Another helper function that replaces text within a specified range with its Unicode equivalent.

- isSinhalaCharacter(): Checks whether a given character is a Sinhala character.

- toUnicode(): Converts a Sinhala character to its Unicode equivalent.

## Notes

- Make sure your Google Docs document is saved before running the script.
- Backup your document before conversion to avoid any potential data loss.

Feel free to contribute to the development of FM-to-Unicode by reporting issues or submitting pull requests. Your feedback and contributions are highly appreciated!
