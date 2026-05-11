# JT AI SEO Assistant

## Simple. Clean. Lightweight. Functional.

**AI-powered SEO assistance for Joomla!**

**JT AI SEO Assistant** is a Joomla content plugin that helps generate SEO metadata for articles using the OpenAI API.

It can automatically create **meta descriptions** when Joomla articles are saved, with optional support for **meta keywords** generation. The plugin is designed to keep the editorial workflow simple while adding practical AI-powered SEO support directly inside Joomla.

---

## Features

- Automatically generates **meta descriptions** for Joomla articles
- Optional **meta keywords** generation
- Multilingual metadata output support
- Predefined output language options
- Automatic language mode to keep metadata in the same language as the article content
- Custom Language / Locale option for languages or regional variants not listed
- Works directly inside the Joomla administrator
- Configurable OpenAI API key and model
- Overwrite option for existing metadata
- Option to process only published articles
- About tab with usage notes and support links

---

## Multilingual Support

JT AI SEO Assistant is designed for real-world multilingual Joomla websites.

The plugin can generate metadata in different languages using the **Metadata Language** setting.

Available language modes include:

- **Automatic - same as article content**
- **English**
- **Turkish**
- **Croatian**
- **Custom Language / Locale**

The **Custom Language / Locale** option can be used for languages, regional variants, or writing styles that are not listed as predefined options.

Examples:

- Serbian Latin
- Brazilian Portuguese
- Swiss German
- Croatian formal

For multilingual websites, the recommended option is:

**Automatic - same as article content**

---

## Requirements

- Joomla **6.x**
- PHP version supported by Joomla 6
- A valid **OpenAI API key**
- An active OpenAI API billing setup if AI generation is used

---

## Installation

1. Download the latest plugin package from the GitHub releases section.
2. In Joomla Administrator, go to **System → Install → Extensions**.
3. Upload and install the plugin ZIP package.
4. Go to **System → Manage → Plugins**.
5. Search for **JT AI SEO Assistant**.
6. Enable the plugin.

---

## Configuration

After enabling the plugin, open its settings and configure the following options.

### OpenAI API Key

Paste your valid OpenAI API key.

A ChatGPT subscription is not the same as OpenAI API access.  
You need an OpenAI API key with active billing or available credit.

### Model

Recommended default:

`gpt-4o-mini`

### Generate Meta Description

Enables automatic meta description generation.

### Generate Meta Keywords

Enables optional meta keywords generation.

This option is disabled by default.

### Metadata Language

Controls the language used for generated SEO metadata.

You can select a predefined language, use automatic article language detection, or choose a custom language / locale.

### Custom Language / Locale

This field appears when **Custom Language / Locale** is selected.

Use it for languages or regional variants that are not listed in the predefined options.

Examples:

- Serbian Latin
- Brazilian Portuguese
- Swiss German
- Croatian formal

### Overwrite Existing Metadata

Enable this only if you want existing metadata to be replaced.

When disabled, existing meta descriptions or keywords will be preserved.

### Only for Published Articles

If enabled, metadata is generated only for published articles.

---

## How It Works

When an article is saved in Joomla, the plugin checks the article content and metadata fields.

If enabled and properly configured, the plugin can:

- generate a missing meta description
- optionally generate meta keywords
- generate metadata in the selected language
- preserve existing metadata when overwrite is disabled
- skip unpublished articles when configured to do so

This helps improve article metadata during the normal Joomla editorial workflow without adding unnecessary complexity.

---

## Important Notes

- This plugin uses the **OpenAI API**, which is a paid external service.
- A **ChatGPT subscription** is not the same as OpenAI API access.
- You must provide your own **OpenAI API key**.
- If your API account has no active billing or available credit, metadata generation will fail.
- Generated metadata should be reviewed by an editor before publishing on production websites.

---

## Support

- **Website:** [JoomTheme](https://joomtheme.com)
- **Contact:** support@joomtheme.com
- **JED:** [JoomTheme on Joomla Extensions Directory](https://extensions.joomla.org/profile/profile/details/147240/)

---

## Credits

Developed by **JoomTheme**.

---

## License

This plugin is released under the **GNU General Public License version 2 or later (GPL-2.0-or-later)**.

---

## Disclaimer

JT AI SEO Assistant is an independent Joomla extension by JoomTheme.

OpenAI and ChatGPT are third-party services and trademarks of their respective owners.
