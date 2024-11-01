# Jikaku

Jikaku is a Japanese Anki deck designed to quickly build kanji reading proficiency. Each card introduces a new kanji or kanji reading. The intent is that learning all the words in this deck will make it much easier to learn other words through reading alone without having to mine them. Here is what the cards look like:

![Image showing the front and back of a card](https://github.com/nullsp-ce/Jikaku/blob/main/JikakuCard.png?raw=true)

The front has a word. The back has the word with the reading as furigana, and the pitch accent, audio and meaning below.

> [!IMPORTANT]
> This deck assumes that you know everything in [Kaishi 1.5k](https://github.com/donkuri/Kaishi/tree/main). If you are a beginner, please complete Kaishi first.

> [!WARNING]
> Jikaku was generated using Python scripts, with errors such as wrong furigana or redundant words fixed manually. There may still be some errors remaining - please report any that you find.

## v3.1-mini
Mini introduces a new kanji with each card (instead of a new kanji OR kanji reading), and is around 1/3 the size of the standard deck. It still covers 3000 kanji (if combined with Kaishi), but only teaches 1 reading for some kanji.

## v4
v4 is an updated version of v3.1-mini with 3 dictionaries to choose from.

![Image showing v4's card definitions](https://github.com/nullsp-ce/Jikaku/blob/main/v4card.png?raw=true)

The default dictionary used is Jitendex. You can make the deck monolingual by replacing {{Jitendex}} in the note's back template with {{Sanseido}} and/or {{Daijirin}}.

## Stats
| Metric                        |    v3.1    | v4 / v3.1-mini |
|------------------------------:|:----------:|:-----------:|
| Total Kanji Covered (with Kaishi)  |    3000    |     3000    |
| Total Kanji Covered (standalone)   |    2954    |     2557    |
| Total Cards/Words             |    5858    |     2062    |
| Total Kanji Readings          |    5858+   |    2775+    |
| Frequency Range               |  Up to ~38k |  Up to ~38k |

## Contact
You can contact me on Discord (username: nullsp_ce) if you have any questions, errors to report or want to contribute.

## Credits
- [AJT Japanese](https://github.com/Ajatt-Tools/Japanese) was used to generate furigana, audio and pitch accent on most cards.
- [JMDict](http://jmdict.org/), Sanseidou and Daijirin was used for card definitions.
- [KANJIDIC](https://github.com/MarvNC/yomitan-dictionaries?tab=readme-ov-file#kanjidic) was used to determine whether a word introduced a new kanji reading.
- Kuuuube's [JPDB v2.2 Frequency](https://github.com/Kuuuube/yomitan-dictionaries?tab=readme-ov-file#jpdb-v22-frequency-1) dictionary was used for frequency information.
