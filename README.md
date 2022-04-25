# scriptural-lexicon

A Lexicon File(s) for Pronunciation of Bible and Book of Mormon names, usable with AWS Polly

The pronunciations are in [International Phonetic Alphabet (IPA)](https://en.wiktionary.org/wiki/Wiktionary:International_Phonetic_Alphabet) format.

Not yet complete, but already useful.  

Note that this file specified en-GB but it should be usable with en-US as well if you change the `xml:lang` property.

The [`PutLexicon` documentation](https://docs.aws.amazon.com/polly/latest/dg/gs-put-lexicon.html) can help teach you the format if you're new to it.

To upload it to your AWS Polly account, see [Managing Lexicons Using the Amazon Polly Console](https://docs.aws.amazon.com/polly/latest/dg/managing-lexicons-console.html#managing-lexicons-console-synthesize-speech).
