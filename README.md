# HPMOR LLM Translations

LLM-generated translations of [Harry Potter and the Methods of Rationality](http://www.hpmor.com/) in Dutch, and hopefully other languages in the future.

These ePub files were generated using the [llm-epub-translator](https://github.com/vanviegen/llm-epub-translator) tool with the Mistral Large model via OpenRouter.

Besides regular translations, there are bilingual versions that are particularly useful for language learning, as they show the original text followed by the translation for each paragraph.

## Dutch
- [hpmor-dutch.epub](hpmor-dutch.epub) - Full Dutch translation (replaces original text)
- [hpmor-dutch-bilangual.epub](hpmor-dutch-bilangual.epub) - Bilingual English/Dutch (original + translation underneath each paragraph)

## Contributing

Add your language here! If you have 20 minutes of your time, a couple of hours of your computer's time and about $5 to spend on OpenAI API credits, you can generate your own translation. Basically just clone the repo and:

`uv tool run llm-epub-translator hpmor.epub Klingon`

See the [llm-epub-translator](https://github.com/vanviegen/llm-epub-translator) project for details. Please contribute your translations back to this repo by opening a pull request.

## Disclaimer

J.K. Rowling owns Harry Potter, and no one owns The Methods of Rationality.
