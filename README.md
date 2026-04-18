# JT AI SEO Assistant

**JT AI SEO Assistant** is a Joomla 6 content plugin that helps generate article metadata with OpenAI.

It can automatically create a **meta description** for Joomla articles when they are saved, with optional support for **meta keywords** generation. The plugin is designed to keep article publishing simple while adding AI-assisted SEO support directly inside Joomla.

## Features

- Automatically generates **meta descriptions** for Joomla articles
- Optional **meta keywords** generation
- Supports **English** and **Turkish**
- Works directly in the Joomla administrator
- Configurable OpenAI API key and model
- Overwrite option for existing metadata
- Option to process only published articles
- About tab with usage notes and support links

## Requirements

- Joomla **6.x**
- PHP version supported by Joomla 6
- A valid **OpenAI API key**
- An active OpenAI API billing setup if AI generation is used

## Installation

1. Download the latest plugin package from the GitHub releases section.
2. In Joomla Administrator, go to **System → Install → Extensions**.
3. Upload and install the plugin ZIP package.
4. Go to **System → Manage → Plugins**.
5. Search for **JT AI SEO Assistant** and enable it.

## Configuration

After enabling the plugin, open its settings and configure:

- **OpenAI API Key**  
  Paste your valid OpenAI API key.

- **Model**  
  Recommended default: `gpt-4o-mini`

- **Generate Meta Description**  
  Enables automatic meta description generation.

- **Generate Meta Keywords**  
  Optional. Disabled by default.

- **Overwrite Existing Metadata**  
  Enable this only if you want existing metadata to be replaced.

- **Only for Published Articles**  
  If enabled, metadata is generated only for published articles.

## How It Works

When an article is saved in Joomla, the plugin checks the article content and metadata fields.

If enabled and properly configured, the plugin can:
- generate a missing meta description
- optionally generate meta keywords
- skip existing values when overwrite is disabled

This makes it easier to improve article metadata during normal editorial workflow.

## Important Notes

- This plugin uses the **OpenAI API**, which is a paid external service.
- A **ChatGPT subscription** is not the same as OpenAI API access.
- You must provide your own **OpenAI API key**.
- If your API account has no active billing or credit, metadata generation will fail.

## Language Support

The plugin includes:
- English language support
- Turkish language support

## Support

- **Website:** [JoomTheme](https://joomtheme.com)
- **Contact:** support@joomtheme.com
- **JED:** [JoomTheme on Joomla Extensions Directory](https://extensions.joomla.org/profile/profile/details/147240/)

## Credits

Developed by **JoomTheme**.

This plugin was also prepared with the assistance of **OpenAI ChatGPT**, helping with planning, structure, code refinement, language improvements, and documentation.

## License

This plugin is released under the **GNU General Public License version 2 or later (GPL-2.0-or-later)**.

## Disclaimer

JT AI SEO Assistant is an independent Joomla extension by JoomTheme.  
OpenAI and ChatGPT are third-party services and trademarks of their respective owners.
