# Custom BibTeX Style for Zotero

This repository offers a modified `bibtex.csl` file, forked from the [citation-style-language/styles](https://github.com/citation-style-language/styles) repository. Its purpose is to improve BibTeX exports from [Zotero](https://www.zotero.org/) when using the **Quick Copy** feature, providing cleaner BibTeX entries.

The [Better BibTeX](https://retorque.re/zotero-better-bibtex/) plugin is excellent for managing citation keys and advanced BibTeX export options. However, it does not export abbreviated journal titles when using "copy BibTeX to clipboard" command. Zotero's Quick Copy with the BibTeX style does support abbreviated journal titles, but it handles citation keys poorly.

To address these issues, the original `bibtex.csl` file is modified to provide a better BibTeX output. This custom file includes the following modifications:

- **Citation Key Integration**: The output citation key is set to use the citation key in zotero entry directly, which can be generated and better managed by Better BibTeX. 
- **Cleaner Output**: Removes unnecessary fields (such as `abstract`, `file`, and `keywords`) for more concise and focused BibTeX entries that are ideal for scientific writing.
- **Improved Formatting**: Refines the structure and formatting of BibTeX output for improved readability and seamless integration with LaTeX documents.
