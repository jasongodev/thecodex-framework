# thecodex-framework
Development framework and style guide for The Codex Library and related plugins.

## File Name Convention

## Plugin Include Locations

## Plugin Code Template

## Coding Style Guide
1. All variables used by The Codex Library and its standard plugins should start with the namespace "codex".
2. Third party plugins should use a consistent namespace that is different from "codex".
3. Variable names should be in lowercase and separated by underscore for variables with 2 or more words.
4. Use 4 whitespaces for indentation. Convert all tabs to 4 whitespaces.
5. Retain any indentation from Kajabi-related files.
6. Leave one blank line for each file.
7. Use {%- ... -%} and {{- ... -}} for Liquid codes unless whitespaces and break lines from the resulting code is a desired consequence for the output.
8. Use single quotes for strings.
9. Use double quotes for strings that contain single quotes.
10. Avoid escaping characters if possible.
11. Put 1 whitespace before and after operators.
