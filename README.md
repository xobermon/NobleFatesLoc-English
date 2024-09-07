This is the Raw (English) Information Text for Noble Fates. New strings will be added here when the game receives updates.

# Warning
Do not Fork this repository for new translations, use NobleFatesLoc instead.

# Help
The best place to get help is on the Offical Noble Fates Discord: ```https://discord.gg/HeAaQcS```

# loc File Format
The loc File Format is a custom text format used for Noble Fates Translations.

## Single String Format
```
\\\\
\\
\\  Translation Notes
\\
\\	Key=Raw (English)
\\
\\\\
Key=Translation
```

## String Pool Format
```
\\\\
\\
\\  Translation Notes
\\
\\	Key+=Raw (English) 1
\\	Key+=Raw (English) 2
\\
\\\\
Key+=Translation 1
Key+=Translation 2
Key+=Translation 3
```

## Comments
Anything after a \\ on a given line is considered a comment, and is ignored by the game.

## Notes
Strings that are Untranslated will return the English Version. String Pools support any number of translations greater than 0. If no translations are provided, the English strings will be used. Blank Translations are treated as no translation.

If the English string doesn't contain a variable and it isn't listed in the Translation Notes, then it probably isn't available. Do what you can with what's available.

Generally, we do not translate unit abbreviations in the game - so p (Prestige), t (Trait Points), c (Coins), y (Yir), d (Day), h (Hour), m (Minute), n (Nutrition) are intentionally left untranslated.

The game has grammatical issues in English via limitations of its technology and attempts at humor. These are intentional, and it's likely that there will be more or less of them in each language. When writing text, we prioritize information delivery and tone over grammatical correctness.

.Advanced Strings signify places where we've made advances in the tech under the hood to allow for more nuance in translations. Generally these will be marked Optional and the strings they replace are marked Deprecated. It's only necessary to translate the Optional or Deprecated string and its children. We prefer using the .Advanced version for all new translations.

### .con Function
.con is a Conjugation function that conjugates between 1st, 2nd, and 3rd person depending on who the speaker and listener are relative to the character. These can be nested.

### .mf/.mfn Functions
These functions allow the substitution of Masculine, Feminine, or Neutral variants of Text based on the gender of the character (or string) before them.

# Closing
As always, feel free to reach out with issues. We're happy to help!


