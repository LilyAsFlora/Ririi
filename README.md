# Rirī

Rirī is a personal [artistic language](https://en.wikipedia.org/wiki/Artistic_language) (*artlang* for short) designed for art, poetry, song, and diaries. Stemming from "ri", "flower" and "rī", "speech", its name roughly translates to "flower speech" or "floral language".

Rirī is agglutinative and phonetically consistent. You can access a dictionary [here](https://gist.github.com/LilyAsFlora/b89e47fe391010c54a54462f0f354cd0).

## Phonology

### Consonants

Aside from the voiced alveolar tap (/ɾ/), all of Rirī's consonants are present in English. This wasn't always the case. As a Polish speaker, Rirī originally included retroflex affricates /ʈʂ/ and /ɖʐ/ (alongside retroflex fricative /ʂ/) to add variety from English. I removed them later due to their unaesthetic sounds.

|                     | Bilabial | Labiodental | Dental | Alveolar | Postalveolar | Retroflex | Palatal | Velar | Uvular | Epiglottal | Glottal |
|:-------------------:|:--------:|:-----------:|:------:|:--------:|:------------:|:---------:|:-------:|:-----:|:------:|:----------:|:-------:|
|       Plosive       |   p, b   |             |        |   t, d   |              |           |         |  k, g |        |            |         |
|        Nasal        |     m    |             |        |     n    |              |           |         |       |        |            |         |
|        Trill        |          |             |        |          |              |           |         |       |        |            |         |
|     Tap or flap     |          |             |        |     ɾ    |              |           |         |       |        |            |         |
|      Fricative      |          |      v      |        |   s, z   |       ʃ      |           |         |       |        |            |    h    |
|  Lateral fricative  |          |             |        |          |              |           |         |       |        |            |         |
|     Approximant     |          |             |        |          |              |           |         |   w   |        |            |         |
| Lateral approximant |          |             |        |          |              |           |         |       |        |            |         |
|      Affricate      |          |             |        |          |     t̠ʃ, d̠ʒ   |           |         |       |        |            |         |

### Vowels

Rirī features the typical five-vowel system.

|            | Front | Near-front | Central | Near-back | Back  |
|------------|-------|------------|---------|-----------|-------|
| Close      | i, i: |            |         |           | u, u: |
| Near-close |       |            |         |           |       |
| Close-mid  |       |            |         |           |       |
| Mid        | e, e: |            |         |           |       |
| Open-mid   |       |            |         |           | o, o: |
| Near-open  |       |            |         |           |       |
| Open       |       |            | a, a:   |           |       |

### Phonotactics

#### Syllable Shape

Rirī permits both open and closed syllables, using a pattern of **(C)(C)V(C)**.

General constraints:

- All syllables have a nucleus
- Maximum 1 coda
- Only nasals and unvoiced consonants in codas (excluding /h/)
- Maximum of 2 consonants in onset
- Only liquids in secondary onset consonants
- No consonantal clusters joining liquids with fricatives or affricates
- Clusters of two of the same consonant are combined into one (e.g. _amma_ -> _ama_)

#### Stress

Rirī lacks lexical stress. However, in poetry or song, speakers may wish to apply patterns of stressed and unstressed syllables to induce the effect of a rhythmic meter.

## Syntax

### Word Order

Generally, Rirī uses a default word order of SVO (subject-verb-object). This may be changed for poetic effect. Possessors and adjectives may come before or after the noun they modify, whereas adpositions and auxiliary verbs usually precede. 

_Ema vidumja amam wariuam._ — She saw the small sign.

_Waruiam amam vidumja ema._ — _lit._ The sign small saw she. (same meaning as above)

### Existentials

To say there is something, use the verb _pashu_ (to be). 

_Ane pashuo onjiam._ — There is a place.
__

## Grammar

### Personal Pronouns

Rirī includes the universal first, second, and third person pronouns. Notice the distinction between plural and singular _they_. _Emi_ is used in reference to groups with one or more masculine entities. _Emai_ is used in reference to groups of strictly feminine entities. In unclear or non-binary cases, _amī_ may be used.

#### Singular

| Person | Subject                  | Object                        |   
|--------|--------------------------|-------------------------------|
| 1      | _sa_ — I                 | _sām_ — me                    |   
| 2      | _ti_ — you               | _tiam_ — you                   |   
| 3      | _em/ema/ano/ami_ — he/she/it/they | _emam/emām_/anoam/amiam — him/her/it/they |   

#### Plural

| Person | Subject      | Object         |
|--------|--------------|----------------|
| 1      | _sai_ — we   | _saiam_ — me   |
| 2      | _tī_ — you   | _tiam_ — you   |
| 3      | _emi (m.) / emai (f.)_ — they | _emiam (m.) / emaiam (f.)_ — them |

### Plurality

Singular nouns are unmarked. Plurals are marked with suffixes -i or -ī, depending on the noun's ending.

- If the noun ends with a consonant, the suffix -i is appended
- If the noun ends with a vowel, the vowel is replaced with the suffix -i
- If the noun ends with -i, it is replaced with the suffix -ī

_Sa rīumge shosenam._ — I read (a) poem (out loud).

_Sa rīumge shosenami._ — I read poems (out loud).

### Tense

Rirī includes four basic tenses: past, present, future, and conditional. These are expressed with affixation and auxiliary verbs. 

_Ema nenja kronue dwukro._ — She must have waited for a while.

|                              |       simple: unmarked       |        continuous: prefix o-        |          perfect: suffix -e          |   perfect continuous: prefix o-, suffix -e  |
|:----------------------------:|:----------------------------:|:-----------------------------------:|:------------------------------------:|:-------------------------------------------:|
|        past: suffix -m       |    _sa kronum_ — I waited    |     _sa okronum_ — I was waiting    |      _sa kronume_ — I had waited     |      _sa okronume_ — I had been waiting     |
|       present: unmarked      |      _sa kronu_ — I wait     |     _sa okronu_ — I have waited     |      _sa krone_ — I have waited     |      _sa okrone_ — I have been waiting     |
|      future: suffix -sh      |  _sa kronush_ — I will wait  |  _sa okronushe_ — I will be waiting |  _sa kronushe_ — I will have waited  |  _sa okronushe_ — I will have been waiting  |
| conditional: + chū, nenu, etc| _sa chū kronu_ — I would wait| _sa chū okronu_ — I would be waiting| _sa chū kronue_ — I would have waited| _sa chū okrone_ — I would have been waiting |

### Noun Case

Rirī features three marked cases: possessive, instrumental, and accusative. They are indicated with suffixes. 

|              | Singular | Plural    | Example                                                                     |
|--------------|----------|-----------|-----------------------------------------------------------------------------|
| Possessive   | n. + -cha | n. + -chi | _Em gapumja ashira**cha** amjagapane gaprām._ — He tidied the store's messy restroom.|
| Instrumental | n. + -em | n. + -emi | _Ti oribumesh agruk**em**?_ — Were you writing on impulse?                         |
| Accusative   | n. + -am  | n. + -ami | _Ema tes mishja amenane bari**ami**!_ — She also loves British accents!            |


### Personal verb endings

Personal endings are used to inflect verbs by person, allowing omission of subject pronouns. This is one of my favourite grammatical features of any language.

|                  | Suffix | Example                       |
|------------------|--------|-------------------------------|
| I                | -ge      | _Puchuge_ — I think             |
| you (s.)         | -esh   | _Puchuesh_ — You think        |
| you (pl.)        | -āch  | _Puchuachi_ — You think       |
| he/she/they (s.) | -ja    | _Puchuja_ - He/she/they think |
| they (pl.)       | -ji  | _Puchuji_ — They think      |
| it               | -o   | _Puchuo_ — It thinks        |
| we               | -īm   | _Puchuīm_ — We think         |


_Pash**ja** enane; chū mishue**ja** etoe riami._ — She's English; she would have loved these flowers.

_Okronum**īm** e tiam._ — We were waiting for you.

### Correlatives

A table of common correlatives, all of which are affected by noun cases when used as pronouns.

|           |     query    |      this     |      that     |         some         |         no        |          every         |
|:---------:|:------------:|:-------------:|:-------------:|:--------------------:|:-----------------:|:----------------------:|
| adjective | _ga_ — which |  _eto_ — this |  _ano_ — that |    _trōch_ — some   |     _ja_ — no     |     _hās_ — every     |
|   person  |  _ko_ — who  |  _eto_ — this |  _ano_ — that |   _troip_ — someone  |  _jaip_ — no-one  |   _hāsip_ — everyone  |
|   thing   | _sō_ — what |  _eto_ — this |  _ano_ — that | _trosō_ — something | _jasō_ — nothing |  _hāsō_ — everything |
|   place   | _ra_ — where | _abon_ — here | _ane_ — there |  _trora_ — somewhere |  _jara_ — nowhere | _hāsura_ — everywhere |
|    time   | _kē_ — when |  _tera_ — now |  _ana_ — then |  _trokē_ — sometime |  _jakē_ — never  |    _hākē_ — always   |
|    way    |  _vā_ — how |               |  _vem_ — thus |  _trovā_ — somehow  |                   |                        |
|   reason  |  _nē_ — why |               |               |                      |                   |                        |


_Vitesh, shosenge **hākē** mishem._ — You see, I always write with passion.

### Adjectives

Adjectives take three standard forms: positive, comparative, and superlative. Adjectives must use the ending _-e_ when describing plural nouns. Since they act like nouns, they should agree in case. This is done by taking the noun's case inflection (e.g. _-am_) and appending it as a prefix to the adjective.

_Rīuge amtwū chānam._ — I speak hard truth.

| Positive            | Comparative                | Superlative                 |
|---------------------|----------------------------|-----------------------------|
| _gaprane_ — clean   | _gapranhu_ — cleaner     | _gapranshe_ — cleanest      |
| _rīuch_ — talkative | _rīuchhu_ — more talkative | _rīuchshe_ — most talkative |

#### Useful Inflections

| Meaning              | Affix     | Example                      |
|----------------------|-----------|------------------------------|
| opposite; not        | ja-, cha- | _jagroane_ — quiet, not loud |
| lacking              | -mev      | _agruipmev_ — friendless     |
| surfeit              | -nam      | _mishnam_ — lovely           |
| able to              | -meu      | _eshmeu_ — edible            |
| adverb               | -twa      | _vintwa_ — finally           |
| weakening of meaning | -kich     | _prakich_ — girlish          |

_A **vintwa**, mōe agruipi ashumji._ — And finally, my friends went shopping. 

### Yes-no Questions

To form yes-no questions, particles _chī_, _chou_ and _chao_ may be applied at the beginning of a sentence.  _Chi_ can also be used as "or."

#### Chi: neutral

_Chī agresh sām?_ — Do you trust me?

#### Chou: expecting "yes"

_Chou pasho chān?_ — That's true, right?

#### Chao: expecting "no"

_Chao pashuo tomjisushkām?_ — That's not a flamethrower, is it?

### Negation

To negative a sentence, add particle _ja_ (lit. "no") before the verb.

_Em ja sūja amani groam._ — He did not make that noise.

### Conjunctions

Conjunctions work similarly to English, with the addition of distinguishment between exclusive and inclusive.

_X chi Y_ means you may have X or Y or both. 

_Chi X chi Y_ means you can have only either X or Y, not both.
