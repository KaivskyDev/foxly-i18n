## Contributing

Want to help translate Foxly?

1. Fork this repository.
2. Open the language folder you want to edit.
3. Translate the files:

   * `messages.po`
   * `messages.ts`
4. Commit your changes.
5. Create a Pull Request.

All contributions will be reviewed before being merged.

## Translation Status

The following languages are considered complete and serve as the reference translations:

* 🇺🇸 English (`en`)
* 🇵🇱 Polish (`pl`)

All other languages may require updates when new strings are added to Foxly.

## Repository Structure

```text
/
├── en/
│   ├── messages.po
│   └── messages.ts
│
├── pl/
│   ├── messages.po
│   └── messages.ts
│
├── de/
│   ├── messages.po
│   └── messages.ts
│
└── ...
```

Each language has its own folder containing translation files used by Foxly.

## Before Creating a Pull Request

Please make sure:

* New translation keys have been translated.
* Existing translations remain accurate.
* Placeholders and variables are preserved.
* Formatting tags are not modified.

Examples:

```text
{username}
{count}
<0></0>
```

These values should never be translated or removed.

## Missing Strings

When Foxly receives new updates, additional translation keys may be added.

Contributors are encouraged to:

* Translate newly added strings.
* Fix outdated translations.
* Improve wording where necessary.
* Report missing or broken translations.

## Adding a New Language

1. Create a new language folder using the locale code.
2. Copy the files from the `en` or `pl` directory.
3. Translate all entries.
4. Submit a Pull Request.

Example:

```text
fr
es
it
de
ja
ko
```

## Notes

English and Polish translations are maintained by the Foxly team and should be treated as the source of truth when translating other languages.

Thank you for helping make Foxly available to users worldwide. 🌍❤️
