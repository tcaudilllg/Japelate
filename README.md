# Japelate
Web app for entering Japanese characters into Google Translate. It is self contained and will run on website or from local filesystem no issues.

# Usage

Click any Japanese character on the page and it will appear in the box at top. Copy that text into Google Translate box at bottom.

This app assumes that the vast majority of non-Japanese people who want to read Japanese will never master the language even at a novice level. To that end, characters are organized based on their similarity to Roman characters. This makes it easier to recognize a character seen in print or a game, for instance, from the list.

Unfortunately Google is strict about access to their online tools. A programmer can't pre-select Japanese from the menu by URL... hence you the user will need to select it yourself. It is also programmatically impossible to directly copy phrases built from selected characters into Google Translate itself (browser won't allow due to questionable security concerns)... that copy-paste job will be up to you I'm afraid.

The current version supports kana, hiragana, and common kanji. Next version may include diacritics and user interface improvements.

I may introduce a version packaged in Electron or NW.js which has fewer limitations (if there is enough demand).
