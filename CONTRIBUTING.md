# Contributing

This document describes the guidelines contrbutors should follow when making changes to Predator.


## General Guidelines

These guidelines describe general rules for Predator that you should be aware of before making any changes.

- Predator and all it's dependencies should be completely free and open source.
    - Changes that involve a proprietary dependency or service will be immediately rejected.
- Predator should never connect to the internet unless explicity asked to be the user.
    - This especially includes analytics. Predator should not "phone home" with analytics or other information.
    - This also includes automatic crowd-sourcing that doesn't ask the user for confirmation before it sends information. Predator is designed to be a stand-alone, self contained, primarily offline tool.
- Predator is designed for individual hobbyists, not law enforcement or commercial applications. Keep this in mind when considering the audience your changes will be used by.


## Coding Guidelines

These guidelines describe how changes to Predator's code should be made.

- Use proper grammar and punctuation in your code and comments.
- Make extensive use of comments. If possible, practically every line of code should have a comment describing what it does, what it's there, and other things that other contributors may need to know.
- Don't place code above the "configuration section" at the top of the script.
- Variable names should be all lowercase with underscores separating words.
    - Example: `my_variable_name`
- Make use of line-breaks to visually separate sections of code.
    - For example, a function definition should have 3 or 4 line-breaks before and after it to visually separate it from the surrounding code.
- Place function definitions near the top of the script, after the configuration section.
