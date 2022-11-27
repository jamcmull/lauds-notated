# Lauds of the Roman rite antecedent to the reforms of Pius X

## Liturgical details

The text is according to the Breviarium Romanum of Leo XIII.
Precedence has been given to Sundays over many double rank feasts.

Most of the work has been done for Sundays and feasts that fell on Sundays since this project was started.

Most of the music notation comes from the Antiphonale Romanum 1912 and Liber Antiphonarius 1960.
The Antiphonale Monasticum 1934 and Antiphonale Monasticum 2005 are frequently used.

Hymns are antecendent to the reforms of Urban VIII. Sometimes the monastic melody is used instead of the Roman.

Ancient mode 3 is used often requiring a slightly modified antiphon.

The orations are pointed to be used with the Ancient Solemn tone. See the Liber Usualis (No. 801) pg. 100 for further information.

## Technical details

Built with [TeX Live 2021](https://www.tug.org/texlive/) using LuaLaTeX and [Gregorio](https://gregorio-project.github.io/index.html).
Both LuaLaTeX and Gregorio come with TeX Live.
No additional setup should be required besides the note below.

In order for Gregorio to be able to convert `.gabc` files outside of the immediate directory to `.gtex`, the following line must be added to `texlive\2021\texmf.cnf`:

	openout_any = r

To build a `.pdf`, open the relevant `.tex` file (such as `dom-per-annum.tex`) in TeXworks (included with TeX Live) and click the green "Typeset" button.

This is a work in progress.
Many of the older booklets will not work right away due to several file restructurings.

## Credits

Much thanks are owed to Mr Scott Morton for typesetting knowledge and Mr Alfred Kalantar for rubrical assistance.

Most antiphons come from [GregoBase](https://gregobase.selapa.net/).

Psalm pointing was done using [Psalm Tone Tool](https://bbloomf.github.io/jgabc/psalmtone.html).
