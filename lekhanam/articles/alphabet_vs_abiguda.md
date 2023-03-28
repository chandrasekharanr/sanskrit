+++
title = "alphabet vs abiguda"
+++

Source: nikhil on discord

I'm also a proponent of Roman transliteration instead of Devanāgarī́, because alphabets are superior (computationally &c.) to abugidas.  If there were an Indian alphabet that were widely used, I'd use it instead of Latin, but I'm not aware of one that even exists let alone being widely used.

Conceptually: they write consonants and vowels separately, which constitute independent sounds not inherently connected to one another, rather than arbitrarily combining them.  Mitrá and mātr̥ ought to begin with the same glyph, but one begins with मि (with the combining vowel in front of the consonant) while the other begins with मा.

<details><summary>उज्ज्वल-प्रतिक्रिया</summary>

svābhāvika-tvḗna (konsepcualī) ítyayáṁ śábdō dr̥ṣṭi-sāpēkṣáḥ (rilēṭiv). dēvanāgaryā́m ḗkēna lipyakṣarḗṇa (gliph-dvārā́) ḗka ēvá svara-varṇáḥ sūcyata íti tátra sundáram 🙂 . ná tú táthā rōmaka-lipāú 😕.
</details>


Computationally: it is far, far easier to do anything involving string search and manipulation in an alphabet than in an abugida.  As an example, if I want to do a regex search like m[iā]trā, this would be extremely difficult to implement in Devanāgarī́ (where I'd have to use combining diacritics in a standalone form).  This is why there aren't really any computational linguistics tools for Sanskrit using anything but Romanization in the back-end; it isn't practical at all to use Devanāgarī́.

<details><summary>उज्ज्वल-प्रतिक्रिया</summary>

kím idám ucyatē 🤷‍♂️ nikhila! saṅgáṇaṁ lípāv ā́yattaṁ ná bhavati khálu! gurukāryā́ya rōmakalipír ápi ná yujyatē 😞 . yát tú kriyátē tád varṇa-vicchēdá 👈  íti kathyatē, ná tú rōmakalipyā́ lḗkhanam íti 😂 . tátra svárāṇām udāttā-nudāttatváṁ hrasva-dīrghatváṁ, vyáñjanānām mārdava-ghōṣatva-vargādi-parijñā́naṁ ca kartavyàm bhavati. tán ná āi-ē-es-ṭī-madhyḗ darśyatē, ná ca es-el-pī-madhyḗ.
</details>


Graphically: alphabets make it much easier to add onto specific morphemes or phonemes.  For example, suppose I wanted to emphasize astam in **astam**ayá.  This is very regular in an alphabet: **astam**ayá.  In Devanāgarī́, one must awkwardly split the syllable: **अस्तम्**अय.  Similarly for a phoneme, if I want to emphasize i in M**i**trā́ (e.g. to oppose it to mā́trā), this is very regular in an alphabet: Mitrā́.  In Devanāgarī́, I guess something like म्**इ**त्रा would be required.

There aren't any arguments for abugidas other than saving space (hardly a concern these days) and "tradition" (but it's not as though scripts have any religious significance). 