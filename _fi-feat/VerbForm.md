---
layout: feature
title: 'VerbForm'
shortdef: 'form of verb or deverbative'
---

Finnish has multiple infinitive forms, often termed the first
infinitive, second infinitive, etc. Traditionally five different
infinitives have been recognized, but UD Finnish follows the modern
[ISK grammar](http://scripta.kotus.fi/visk/etusivu.php) in only
recognizing three verb forms as infinitives, namely those known as the
first, second and third infinitives (alternatively termed the A‑, E-
and MA-infinitives, see e.g. [VISK §
119](http://kaino.kotus.fi/visk/sisallys.php?p=119); in Finnish).

### `Fin`: finite verb

Verbs that inflect for mood ([Mood]()), tense ([Tense]()) or person
([Person]()) are finite and are assigned the `VerbForm` value `Fin`.
Additionally, the negation verb *ei* only has finite forms ([VISK §
108](http://scripta.kotus.fi/visk/sisallys.php?p=108); in Finnish),
and is always annotated with `VerbForm=Fin`.

#### Examples

* [fi] _Minä <b>ostin</b> kahvia "I <b>bought</b> coffee"
* [fi] _Minulla <b>ei</b> ole autoa_ "I <b>do not</b> have a car"

### `Inf`: infinitive

Words in the first infinitive form (also known as the A-infinitive)
are assigned the `VerbForm` value `Inf`.

The base form of the first infinitive is used as the dictionary form
for verbs.

#### Examples

* [fi] _He haluavat <b>jutella</b>_ "They want to <b>talk</b>"

### `Inf2`: infinitive

Words in the second infinitive form (also known as the E-infinitive)
are assigned the `VerbForm` value `Inf2`.

#### Examples

* [fi] _<b>ottaen</b> huomioon_ "<b>taking</b> into account"

### `Inf3`: infinitive

Words in the third infinitive form (also known as the MA-infinitive)
are assigned the `VerbForm` value `Inf3`.

#### Examples

* [fi] _Menen <b>katsomaan</b> musikaalia_ "I am going to <b>see</b> a musical"

### `Part`: participle

Words in participle forms are assigned the `VerbForm` value `Part`.

#### Examples

* [fi] _Puolue on <b>saanut</b> tukea_ "The party has <b>received</b> support"

### References

* <http://en.wikipedia.org/wiki/Finnish_verb_conjugation#Infinitives_and_participles>
* <http://scripta.kotus.fi/visk/sisallys.php?p=444> (in Finnish)
* <http://scripta.kotus.fi/visk/sisallys.php?p=108> (in Finnish)
* <http://kaino.kotus.fi/visk/sisallys.php?p=120> (in Finnish)
* <http://kaino.kotus.fi/visk/sisallys.php?p=121> (in Finnish)