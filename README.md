# Jikaku

> [!IMPORTANT]
> This deck assumes that you know everything in [Kaishi 1.5k](https://github.com/donkuri/Kaishi/tree/main). If you are a beginner, please complete Kaishi first.

Jikaku is a Japanese Anki deck designed to quickly build kanji reading proficiency. Each card introduces a new kanji, totalling 3000 kanji taught when combined with Kaishi. The intent is that learning all the words in this deck will make it much easier to learn other words through reading alone without having to mine them. Here is what the cards look like:

![Image showing the front and back of a card](https://github.com/nullsp-ce/Jikaku/blob/main/JikakuCard.png?raw=true)

The front has a word. The back has the word with the reading as furigana, and the pitch accent, audio and meaning below. Many cards also have example sentences with translations.

![Image showing v4's card definitions](https://github.com/nullsp-ce/Jikaku/blob/main/v4card.png?raw=true)

The default dictionary used is Jitendex. You can make the deck monolingual by replacing `{{Jitendex}}` in the note's back template with `{{Sanseido}}{{Daijirin}}`.

> [!CAUTION]
> Replacing `{{Jitendex}}` in the back template with `{{Sanseido}}` or `{{Daijirin}}` only is not recommended because some entries are missing for these dictionaries.

## v3.1
v3.1 introduces a new kanji OR kanji reading with each card (instead of only new kanji). It is around 3x the size of v4 and v3.1-mini.

## Stats
| Metric                             |     v4     |    v3.1    |
|-----------------------------------:|:----------:|:----------:|
| Total Kanji Covered (with Kaishi)  |    3000    |    3000    |
| Total Kanji Covered (standalone)   |    2557    |    2954    |
| Total Cards/Words                  |    2062    |    5858    |
| Total Kanji Readings               |    2775+   |    5858+   |
| Frequency Range                    | Up to ~38k | Up to ~38k |

## Contact
You can contact me on Discord (username: nullsp_ce) if you have any questions, errors to report or want to contribute.

## Credits
- [AJT Japanese](https://github.com/Ajatt-Tools/Japanese) was used to generate furigana, audio and pitch accent on most cards.
- [JMDict](http://jmdict.org/), [Jitendex](https://jitendex.org/), Sanseido and Daijirin were used for card definitions.
- [KANJIDIC](https://github.com/MarvNC/yomitan-dictionaries?tab=readme-ov-file#kanjidic) was used to determine whether a word introduced a new kanji reading.
- Kuuuube's [JPDB v2.2 Frequency](https://github.com/Kuuuube/yomitan-dictionaries?tab=readme-ov-file#jpdb-v22-frequency-1) dictionary was used for frequency information.
