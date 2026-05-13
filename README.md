# JT AI SEO Assistant

## Simple. Clean. Lightweight. Functional.

**AI-powered SEO metadata assistance for Joomla!**

**JT AI SEO Assistant** is a Joomla content plugin that helps generate SEO metadata for Joomla articles using the OpenAI API.

It can automatically create **meta descriptions** when Joomla articles are saved, with optional support for **meta keywords** generation. The plugin is designed to keep the editorial workflow simple while adding practical AI-powered SEO support directly inside Joomla.

---

## Features

- Automatically generates **meta descriptions** for Joomla articles
- Optional **meta keywords** generation
- Multilingual metadata output support
- Predefined output language options
- Automatic language mode to keep metadata in the same language as the article content
- Custom Language / Locale option for languages or regional variants not listed
- Category-based control for AI metadata generation
- Option to exclude selected Joomla content categories
- Option to run the plugin only on selected Joomla content categories
- Works directly inside the Joomla administrator
- Configurable OpenAI API key and model
- Overwrite option for existing metadata
- Option to process only published articles
- About tab with usage notes and support links

---

## Category-Based Control

JT AI SEO Assistant includes category-based control for Joomla articles.

This allows site owners, publishers, and editorial teams to decide where AI metadata generation should be applied.

Available category rule modes:

- **Run on all categories**
  - Default behavior. The plugin works on all Joomla article categories.
- **Exclude selected categories**
  - The plugin will not generate meta descriptions or meta keywords for selected categories.
- **Run only on selected categories**
  - The plugin will generate metadata only for selected categories.

This is useful for:

- News portals
- Editorial websites
- Obituary or deceased people sections
- Manually curated content areas
- Sensitive content categories
- Websites with different publishing workflows

If no category restriction is configured, the plugin keeps the default behavior and runs on all categories.

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

After enabling the plugin, open its settings and configure the available options.

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

### Category Rule

Controls how the plugin should behave for Joomla article categories.

Available options:

- **Run on all categories**
- **Exclude selected categories**
- **Run only on selected categories**

The default option is **Run on all categories**, so existing websites continue to work as before.

### Categories

Select one or more Joomla content categories for the selected category rule.

This field is used only when the category rule is set to:

- **Exclude selected categories**
- **Run only on selected categories**

### Overwrite Existing Metadata

Enable this only if you want existing metadata to be replaced.

When disabled, existing meta descriptions or keywords will be preserved.

### Only for Published Articles

If enabled, metadata is generated only for published articles.

---

## How It Works

When an article is saved in Joomla, the plugin checks the article content, metadata fields, publishing state, and configured category rule.

If enabled and properly configured, the plugin can:

- Generate a missing meta description
- Optionally generate meta keywords
- Generate metadata in the selected language
- Preserve existing metadata when overwrite is disabled
- Skip unpublished articles when configured to do so
- Skip excluded categories
- Run only on selected categories when configured

This helps improve article metadata during the normal Joomla editorial workflow without adding unnecessary complexity.

---

## Important Notes

- This plugin uses the **OpenAI API**, which is a paid external service.
- A **ChatGPT subscription** is not the same as OpenAI API access.
- You must provide your own **OpenAI API key**.
- If your API account has no active billing or available credit, metadata generation will fail.
- Generated metadata should be reviewed by an editor before publishing on production websites.
- Category-based rules apply to Joomla article categories and are intended to give publishers more control over where AI metadata generation is used.

---

## Use Cases

JT AI SEO Assistant can be useful for:

- Blogs
- News portals
- Magazine websites
- Multilingual Joomla websites
- Editorial publishing workflows
- Websites with many existing articles
- Websites that need controlled AI metadata generation by category

---

## Support

- **Website:** [JoomTheme](https://joomtheme.com)
- **Contact:** support@joomtheme.com
- **JED:** [JoomTheme on Joomla Extensions Directory](https://extensions.joomla.org/profile/profile/details/147240/)
- **Extension:** [JT AI SEO Assistant on JED](https://extensions.joomla.org/extension/site-management/seo-a-metadata/jt-ai-seo-assistant/)

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
