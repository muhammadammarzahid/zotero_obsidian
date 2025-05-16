# Zotero → Obsidian Admonition Template

This repository contains a ready-to-use Obsidian note template for exporting Zotero metadata and annotations into Obsidian, with enhanced support for the Admonition plugin. By leveraging Admonition instead of default callouts, this template avoids common rendering issues and improves compatibility across themes.

> **NOTE:** Install [_Admonition_ Plugin](https://github.com/javalent/admonitions) from Obsidian’s third-party plugin interface and enable it. This will ensure the template is consistent on all themes with minimal bugs or glitches.

## 📋 How to Use

Follow these steps to set up and use this template in your Obsidian vault:

1. **Install the Zotero Integration plugin**

   * Watch this tutorial video: [https://www.youtube.com/watch?v=WNBLR-5zPmk](https://www.youtube.com/watch?v=WNBLR-5zPmk)
   * Follow the instructions to connect Zotero with Obsidian.

2. **Install the Admonition plugin**

   * Visit the plugin repository: [https://github.com/javalent/admonitions](https://github.com/javalent/admonitions)
   * Install it via Obsidian’s third-party plugin interface and enable it.

3. **Add the Template to Your Vault**

   * Copy the contents of the provided `zotero_integration.md` file into your vault’s `Templates` folder (or any folder you prefer).
   * In Obsidian, set up your core Templates plugin (or Templater) to point to this file.

--- 

## 🚀 Features

* **YAML Front Matter**: Automatically generates standardized front matter with metadata fields such as title, authors, year, publisher, keywords, DOI, and more.
* **Embedded Webpage Section**: Easily preview the source webpage via an `<iframe>`.
* **Persistent Notes & Annotations**: Uses Obsidian’s `persist` blocks to store your personal notes and imported “Reading notes” from Zotero annotations.
* **Admonition Support**: Utilizes the Admonition plugin for consistent, theme-agnostic callouts that handle special characters and links correctly.

---


## ⚠️ Why Admonition?

The default Obsidian callouts can be problematic:

1. **Theme Inconsistency**: Some Obsidian themes render the built-in callout syntax incorrectly, leading to visual glitches.
2. **Special Character Breaks**: Content containing the `>` symbol can prematurely terminate a callout.
3. **Page Link Issues**: Zotero page number links (e.g., `page. 23`) are often interpreted as the callout title and thus broken.

By using Admonition, this template remedies all of these issues:

* Admonition blocks render reliably across themes.
* They handle `>` and other markdown characters without breaking.
* Links and titles are parsed correctly, preserving all Zotero-provided references.
