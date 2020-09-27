# LaTeX-Package `dhpaper` and Template for DHBW Papers

This is a LaTeX template for DHBW reports and project papers.
The formatting for the cover page and necessary packages and configurations for the papers are in the `dhpaper.sty` file, the rest are examples for the use of every package.

List of key LaTeX files:

* `dhpaper.bib` - Bibliography file for use with BibLaTeX.
* `dhpaper.sty` - Style file for proper fonts, cover page, etc.
* `dhpaper.tex` - Main project file, contains configuration for the cover page, table of contents, content listings, and includes constituent chapters.
* `body.tex` - Contains usage examples for images, code, tables (with captions), and acronyms and glossary terms.
* `glossary.tex` - Defines abbreviations, acronyms, and glossary terms.

System-specific compilation scripts:

* `compile.bat` - Windows batch file for compilation of `dhpaper.tex`, including BibTeX bibliography and `glossaries` package (requires a Perl installation).
* `cleanup.bat` - Cleans up intermediately generated files. Packed as a separate file from `compile.bat` for troubleshooting purposes.
* Linux scripts are coming soon.