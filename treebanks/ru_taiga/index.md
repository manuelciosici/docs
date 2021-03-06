---
layout: base
title:  'UD_Russian-Taiga'
udver: '2'
---

<!-- This page is automatically generated from the README file and from
     the data files in the latest release.

     Please do not edit this page directly. -->

# UD Russian Taiga

Language: [Russian](/ru/index.html) (code: `ru`)<br/>
Family: Indo-European, Slavic

This treebank has been part of Universal Dependencies since the UD v2.2 release.

The following people have contributed to making this treebank part of UD: Olga Lyashevskaya, Olga Rudina.

Repository: [UD_Russian-Taiga](https://github.com/UniversalDependencies/UD_Russian-Taiga)<br />
Search this treebank on-line: [PML-TQ](https://lindat.mff.cuni.cz/services/pmltq/#!/treebank/udru_taiga22)<br />
Download all treebanks: [UD 2.2](/#download)

License: CC BY-SA 4.0

Genre: blog, news, poetry, social

Questions, comments?
General annotation questions (either Russian-specific or cross-linguistic) can be raised in the [main UD issue tracker](https://github.com/UniversalDependencies/docs/issues).
You can report bugs in this treebank in the [treebank-specific issue tracker on Github](https://github.com/UniversalDependencies/UD_Russian-Taiga/issues).
If you want to collaborate, please contact [olesar&nbsp;(æt)&nbsp;yandex&nbsp;•&nbsp;ru].
Development of the treebank happens outside the UD repository.
If there are bugs, either the original data source or the conversion procedure must be fixed.
Do not submit pull requests against the UD repository.

| Annotation | Source |
|------------|--------|
| Lemmas | annotated manually, natively in UD style |
| UPOS | annotated manually, natively in UD style |
| XPOS | annotated manually |
| Features | annotated manually, natively in UD style |
| Relations | annotated manually, natively in UD style |

## Description

Universal Dependencies treebank is based on data samples extracted from Taiga Corpus and MorphoRuEval-2017 text collections.



UD Russian Taiga has been developed at the School of Linguistics, National Research University Higher School of Economics in Moscow (HSE/Vyshka). The selection of texts is meant to represent those registers that have not been covered by UD Russian SynTagRus and UD Russian Google Stanford Dependencies, mainly e-communication (blogs and social media). The sentences are extracted from two open data collections. Taiga Corpus ([https://tatianashavrina.github.io/taiga_site/](https://tatianashavrina.github.io/taiga_site/)) is an open-source corpus for machine learning collected by students as part of the curriculum of the MA Program in Computational Linguistics at HSE. MorphoRuEval 2017 text collections ([https://github.com/dialogue-evaluation/morphoRuEval-2017](https://github.com/dialogue-evaluation/morphoRuEval-2017)) is an output of the RuEval shared task 'Evaluation of Russian NLP: Morphological analysis, [http://www.dialog-21.ru/en/evaluation/2017/morphology/](http://www.dialog-21.ru/en/evaluation/2017/morphology/)).

The plain text data were tokenized, lemmatized and parsed using UDpipe ([http://ufal.mff.cuni.cz/udpipe](http://ufal.mff.cuni.cz/udpipe)) and checked manually. Corrections were made at all levels: tokenization, lemmata, pos, features, dependency relations.

## Acknowledgments

We are grateful to all the contributors to the original open Russian data collections and especially to Tatiana Shavrina (Taiga) and Alena Fenogenova (MorphoRuEval-2017 data set).

## References

* Lyashevskaya, Olga, Kira Droganova, Daniel Zeman, Maria Alexeeva, Tatiana Gavrilova, Nina Mustafina, and Elena Shakurova.
(2016). Universal Dependencies for Russian: a New Syntactic Dependencies Tagset. In: Series: Linguistics, WP BRP 44/LNG/2016. Moscow.

* Sorokin, Andrey, Tatiana Shavrina, Olga Lyashevskaya, Victor Bocharov, Svetlana Alexeeva, Kira Droganova, Alena Fenogenova, and Dmitry Granovsky. (2017). MorphoRuEval-2017: an Evaluation Track for the Automatic Morphological Analysis Methods for Russian. In Computational Linguistics and Intellectual Technologies, Proceedings of Dialog 2017, Moscow. No 16 (23). Vol. 1, 297-313.

* Lyashevskaya, Olga, Victor Bocharov, Alexey Sorokin, Tatiana Shavrina, Dmitry Granovsky, and Svetlana Alexeeva. (2017).
Text collections for evaluation of Russian morphological taggers. Jazykovedny Casopis, 68 (2), 2017: 258-267.

* Shavrina, Tatiana, Olga Shapovalova. (2017) To the methodology of corpus construction for machine learning: «Taiga» syntax tree corpus and parser. In Proceedings of the International Conference "CORPORA 2017", Saint-Petersbourg, Russia.



# Statistics of UD Russian Taiga

## POS Tags

[ADJ](ru_taiga-pos-ADJ.html) – [ADP](ru_taiga-pos-ADP.html) – [ADV](ru_taiga-pos-ADV.html) – [AUX](ru_taiga-pos-AUX.html) – [CCONJ](ru_taiga-pos-CCONJ.html) – [DET](ru_taiga-pos-DET.html) – [INTJ](ru_taiga-pos-INTJ.html) – [NOUN](ru_taiga-pos-NOUN.html) – [NUM](ru_taiga-pos-NUM.html) – [PART](ru_taiga-pos-PART.html) – [PRON](ru_taiga-pos-PRON.html) – [PROPN](ru_taiga-pos-PROPN.html) – [PUNCT](ru_taiga-pos-PUNCT.html) – [SCONJ](ru_taiga-pos-SCONJ.html) – [SYM](ru_taiga-pos-SYM.html) – [VERB](ru_taiga-pos-VERB.html) – [X](ru_taiga-pos-X.html)

## Features

[Abbr](ru_taiga-feat-Abbr.html) – [Animacy](ru_taiga-feat-Animacy.html) – [Aspect](ru_taiga-feat-Aspect.html) – [Case](ru_taiga-feat-Case.html) – [Degree](ru_taiga-feat-Degree.html) – [Foreign](ru_taiga-feat-Foreign.html) – [Gender](ru_taiga-feat-Gender.html) – [Mood](ru_taiga-feat-Mood.html) – [Number](ru_taiga-feat-Number.html) – [Person](ru_taiga-feat-Person.html) – [Polarity](ru_taiga-feat-Polarity.html) – [Tense](ru_taiga-feat-Tense.html) – [Typo](ru_taiga-feat-Typo.html) – [Variant](ru_taiga-feat-Variant.html) – [VerbForm](ru_taiga-feat-VerbForm.html) – [Voice](ru_taiga-feat-Voice.html)

## Relations

[acl](ru_taiga-dep-acl.html) – [acl:relcl](ru_taiga-dep-acl-relcl.html) – [advcl](ru_taiga-dep-advcl.html) – [advmod](ru_taiga-dep-advmod.html) – [amod](ru_taiga-dep-amod.html) – [appos](ru_taiga-dep-appos.html) – [aux](ru_taiga-dep-aux.html) – [aux:pass](ru_taiga-dep-aux-pass.html) – [case](ru_taiga-dep-case.html) – [cc](ru_taiga-dep-cc.html) – [ccomp](ru_taiga-dep-ccomp.html) – [compound](ru_taiga-dep-compound.html) – [conj](ru_taiga-dep-conj.html) – [cop](ru_taiga-dep-cop.html) – [csubj](ru_taiga-dep-csubj.html) – [dep](ru_taiga-dep-dep.html) – [det](ru_taiga-dep-det.html) – [discourse](ru_taiga-dep-discourse.html) – [dislocated](ru_taiga-dep-dislocated.html) – [expl](ru_taiga-dep-expl.html) – [fixed](ru_taiga-dep-fixed.html) – [flat](ru_taiga-dep-flat.html) – [flat:foreign](ru_taiga-dep-flat-foreign.html) – [flat:name](ru_taiga-dep-flat-name.html) – [goeswith](ru_taiga-dep-goeswith.html) – [iobj](ru_taiga-dep-iobj.html) – [list](ru_taiga-dep-list.html) – [mark](ru_taiga-dep-mark.html) – [nmod](ru_taiga-dep-nmod.html) – [nsubj](ru_taiga-dep-nsubj.html) – [nsubj:pass](ru_taiga-dep-nsubj-pass.html) – [nummod](ru_taiga-dep-nummod.html) – [nummod:entity](ru_taiga-dep-nummod-entity.html) – [nummod:gov](ru_taiga-dep-nummod-gov.html) – [obj](ru_taiga-dep-obj.html) – [obl](ru_taiga-dep-obl.html) – [obl:agent](ru_taiga-dep-obl-agent.html) – [orphan](ru_taiga-dep-orphan.html) – [parataxis](ru_taiga-dep-parataxis.html) – [punct](ru_taiga-dep-punct.html) – [reparandum](ru_taiga-dep-reparandum.html) – [root](ru_taiga-dep-root.html) – [vocative](ru_taiga-dep-vocative.html) – [xcomp](ru_taiga-dep-xcomp.html)

<h2>Tokenization and Word Segmentation</h2>


<ul>
<li>This corpus contains 3264 sentences and 38555 tokens.</li>
</ul>

<ul>
<li>This corpus contains 6405 tokens (17%) that are not followed by a space.</li>
</ul>

<ul>
<li>This corpus does not contain words with spaces.</li>
</ul>

<ul>
<li>This corpus contains 543 types of words that contain both letters and punctuation. Examples: @xxxxxx, @yabloko, http://xxxxxx, https://xxxxxx, @Zhirinovskiy, л., т., что-то, ст., д., @YouTube, @screened-200, ч., из-за, кто-то, @screened-18, P.S., все-таки, г., гр., из-под, п., #ростов, #семейныйотдых, #сочи, @screened-134, @screened-15, @screened-162, @screened-32, В., Сен-Мерри, давным-давно, е., и., как-то, какой-то, кого-то, млн., по-прежнему, чем-то, #astrakhan, #fishing, #gopro, #hotel_grafit, #russia, #sochifornia, #адлер, #астраханскаяобласть, #астрахань, #базавастрахани</li>
</ul>

<ul>
</ul>

<h2>Morphology</h2>

<h3>Tags</h3>

<ul>
<li>This corpus uses 17 UPOS tags out of 17 possible: <a>ADJ</a>, <a>ADP</a>, <a>ADV</a>, <a>AUX</a>, <a>CCONJ</a>, <a>DET</a>, <a>INTJ</a>, <a>NOUN</a>, <a>NUM</a>, <a>PART</a>, <a>PRON</a>, <a>PROPN</a>, <a>PUNCT</a>, <a>SCONJ</a>, <a>SYM</a>, <a>VERB</a>, <a>X</a></li>
</ul>

<ul>
<li>This corpus contains 73 word types tagged as particles (PART): PROFIT, Але, Вроде, Да-да, Даааа, Мож, Неееее, Неужто, Пускай, УСИ, ХАЙ, Хэллоу, а, аж, аль, аминь, бл@, бля, блять, бляь, будто, бы, ведь, вон, вот, все, все-таки, всего, да, давайте, даже, дай, досвидания, единственно, еле, ж, же, и, именно, как, ладно, ли, либо, лиш, лишь, ль, не, неее, нет, неужели, ни, ну, поди, пожалуйста, просто, прямо, пусть, разве, су, также, таки, те, типа, то, тоже, только, уж, ужели, хорошо, хоть, хотя, че, это</li>
</ul>

<ul>
<li>This corpus contains 38 lemmas tagged as pronouns (PRON): goeswith, весь, все, всё, вы, друг, его, котоpый, который, кто, кто-то, мизулина+это, мы, некого, никто, ничего, ничто, он, она, они, оно, оное, се, себя, то, тот, ты, у+мы, че, чем, что, что+бы, что-либо, что-нибудь, что-то, это, этот, я</li>
</ul>

<ul>
<li>This corpus contains 36 lemmas tagged as determiners (DET): cвой, ваш, весь, все, всякий, его, ее, емо, их, каждый, каков, какой, какой-либо, какой-то, клыкастый, любой, мой, наш, некий, некоторый, никакой, овса, один, он, она, оный, сам, свой, сей, таков, такой, твой, тот, чей, это, этот</li>
</ul>

<ul>
<li>Out of the above, 8 lemmas occurred sometimes as PRON and sometimes as DET: весь, все, его, он, она, тот, это, этот</li>
</ul>

<ul>
<li>This corpus contains 3 lemmas tagged as auxiliaries (AUX): б, бы, быть</li>
</ul>

<ul>
<li>Out of the above, 1 lemmas occurred sometimes as AUX and sometimes as VERB: быть</li>
</ul>

<ul>
<li>There are 4 <a href="../feat/VerbForm.html">(de)verbal forms:</a></li>
</ul>

<ul>
  <li>Conv
  <ul>
    <li>AUX: будучи</li>
    <li>VERB: судя, говоря, Благодаря, бежа, видя, встречая, держа, доставши, дрожа, занимаясь</li>
  </ul>
  </li>
</ul>

<ul>
  <li>Fin
  <ul>
    <li>AUX: было, был, будет, была, есть, были, будут, буду, будем, будешь</li>
    <li>NOUN: #самолет</li>
    <li>PROPN: #сургут</li>
    <li>VERB: есть, может, нет, сказал, стоит, говорит, вижу, понимаю, сидит, думаю</li>
  </ul>
  </li>
</ul>

<ul>
  <li>Inf
  <ul>
    <li>AUX: быть</li>
    <li>VERB: сделать, делать, жить, добавить, быть, думать, показать, смотреть, голосовать, видеть</li>
  </ul>
  </li>
</ul>

<ul>
  <li>Part
  <ul>
    <li>NOUN: прошедшим</li>
    <li>VERB: написано, организованных, Восхищена, живущих, изложенным, Беременная, Ведущим, Венчанный, Вспотевшим, Входящая</li>
  </ul>
  </li>
</ul>

<h3>Nominal Features</h3>


<ul>
  <li><a>Gender</a></li>
</ul>

<ul>
  <li>Fem
    <ul>
      <li>ADJ: святую, вторая, дохлой, сама, большую, гражданской, должна, Единой, первая, уверена</li>
      <li>ADV: Нихера</li>
      <li>AUX: была, бывшая</li>
      <li>AUX-Fin: была</li>
      <li>DET: этой, своей, такая, нашу, моей, моя, той, вся, такой, какая</li>
      <li>NOUN: воды, жизни, баба, ночь, партии, зимой, минут, руки, мысли, пропитка</li>
      <li>NUM: две, одна, одной, Тысячи, одну, тысяч</li>
      <li>PRON: она, ней, ей, ее, которая, которой, её, неё, ею, которую</li>
      <li>PROPN: ЛДПР, России, Россия, Русь, кпрф, ЕР, Госдумы, Анна, Анны, Украины</li>
      <li>PUNCT: 1⃣, 2⃣, 3⃣, 4⃣, 5⃣</li>
      <li>SYM: ♥️, ❤️, 🌊🥰</li>
      <li>VERB: видела, сказала, стала, пришла, знала, прошла, стояла, Восхищена, воротилась, думала</li>
      <li>VERB-Fin: видела, сказала, стала, пришла, знала, прошла, стояла, воротилась, думала, заметила</li>
      <li>VERB-Part: Восхищена, Беременная, Входящая, Зимой, Куплена, Назначенной, Пьющая, вручена, выдуманной, грядущая</li>
      <li>X: #дизайнспальни</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Masc
    <ul>
      <li>ADJ: сам, первый, большой, новый, самый, добрый, последний, целый, Европейский, нужен</li>
      <li>ADV: Судак, максимум</li>
      <li>AUX-Fin: был</li>
      <li>DET: этот, мой, наш, свой, каждый, такой, тот, какой, один, ваш</li>
      <li>NOUN: лет, день, раз, люди, года, человек, детей, мир, глаз, людей</li>
      <li>NUM: один, два, одного, оба, 0, одном, полтора</li>
      <li>PRON: он, кто, ему, его, который, него, ним, кого, кому, которого</li>
      <li>PROPN: жириновский, парнас, крым, жириновского, Женя, СССР, жирик, Бог, Крыму, Путина</li>
      <li>SYM: %, $</li>
      <li>VERB: сказал, стал, видел, говорил, начал, решил, успел, вышел, заметил, знал</li>
      <li>VERB-Fin: сказал, стал, видел, говорил, начал, решил, успел, вышел, заметил, знал</li>
      <li>VERB-Part: Венчанный, Вспотевшим, Заглохший, Изрытый, Овеществленный, Приглашён, УМЕРШИЙ, Уничножен, бегущий, блещущий</li>
      <li>X: @screened-18, #НН, корпусе</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Neut
    <ul>
      <li>ADJ: нужно, странно, хорошо, круто, равно, должно, самое, единственное, интересно, невозможно</li>
      <li>ADV: красиво</li>
      <li>AUX-Fin: было</li>
      <li>DET: это, все, такое, то, всё, мое, одно, своё, наше, своем</li>
      <li>NOUN: время, море, фото, спасибо, солнце, место, видео, дело, лицо, слова</li>
      <li>NOUN-Part: прошедшим</li>
      <li>NUM: одно, два, одного, Днём, одним</li>
      <li>PRON: это, что, всё, все, то, всего, том, этого, того, оно</li>
      <li>PROPN: яблоко, яблока, Стереолето, @yabloko, Приднестровье, #подмосковье, #соленье, АВТО.РУ, АТО, Б-А</li>
      <li>SCONJ: что</li>
      <li>VERB: было, случилось, стало, написано, хотелось, понравилось, казалось, оказалось, осталось, повезло</li>
      <li>VERB-Fin: было, случилось, стало, хотелось, понравилось, казалось, оказалось, осталось, повезло, получилось</li>
      <li>VERB-Part: написано, Ведущим, выдавленным, запрещено, затуманенном, зящее, изувечено, имеющее, исходящим, могущее</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Animacy</a></li>
</ul>

<ul>
  <li>Anim
    <ul>
      <li>ADJ: Бывших, Волго-Ахтубинской, Непразднуемых, Одних, ПРАВОСЛАВНЫХ, большого, воцерковленного, главного, дебильных, достойных</li>
      <li>DET: всех, наших, такого, моих, этих</li>
      <li>NOUN: люди, человек, детей, баба, людей, друзья, детям, человека, депутаты, дети</li>
      <li>NUM: двоих, нескольких</li>
      <li>PRON: кто, все, всем, кого, кому, всех, кто-то, кем, которого, кому-то</li>
      <li>PROPN: жириновский, жириновского, Женя, жирик, Бог, Путина, Явлинский, Анна, Анны, Бога</li>
      <li>VERB: Надевши, Рек, желающих, звавшего, наблюдающий, обвиняемого, пирующих, удмурт, указаных</li>
      <li>VERB-Part: желающих, звавшего, наблюдающий, обвиняемого, пирующих, указаных</li>
      <li>X: #НН</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Inan
    <ul>
      <li>ADJ: первый, последние, целый, Европейский, бесполезный, большой, выходные, горячий, детский, другой</li>
      <li>ADV: Нихера, Судак, максимум</li>
      <li>DET: все, свой, этот, каждый, ваши, один, свои, весь, мой, сей</li>
      <li>NOUN: лет, день, раз, время, море, года, фото, воды, мир, жизни</li>
      <li>NUM: несколько, два, один, три, две, 0, Днём, Тысячи, пять, столько</li>
      <li>PRON: это, что, все, то, всё, всего, том, этого, того, чем</li>
      <li>PROPN: ЛДПР, парнас, яблоко, России, Россия, Русь, кпрф, крым, ЕР, СССР</li>
      <li>PUNCT: 1⃣, 2⃣, 3⃣, 4⃣, 5⃣</li>
      <li>SCONJ: что</li>
      <li>SYM: %, $, ♥️, ❤️, 🌊🥰</li>
      <li>VERB: Заглохший, бегущий, блещущий, влекомый, гаснущие, дрожащий, забытый, зажатый, интересующие, наперченный</li>
      <li>VERB-Part: Заглохший, бегущий, блещущий, влекомый, гаснущие, дрожащий, забытый, зажатый, интересующие, наперченный</li>
      <li>X: @screened-18, #дизайнспальни, корпусе</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Number</a></li>
</ul>

<ul>
  <li>Plur
    <ul>
      <li>ADJ: разных, других, золотые, живые, нужны, первые, рады, дохлых, последние, православных</li>
      <li>AUX: были, будут, будем, есть, будете, будьте</li>
      <li>AUX-Fin: были, будут, будем, есть, будете</li>
      <li>DET: все, эти, всех, мои, такие, свои, тех, наших, моих, наши</li>
      <li>NOUN: лет, люди, раз, детей, людей, друзья, минут, руки, детям, глаза</li>
      <li>NUM: 0, Тысячи, тысяч</li>
      <li>PRON: мы, вы, нас, они, вас, их, вам, нам, все, им</li>
      <li>PROPN: Сочи, США, #камызяки, #сургут, Бальмонты, Блоки, Брюсовы, ВС, Весах, Горациев</li>
      <li>PROPN-Fin: #сургут</li>
      <li>SYM: %, $</li>
      <li>VERB: есть, здравствуйте, могут, сидят, пришли, стали, ходят, вышли, говорят, дайте</li>
      <li>VERB-Fin: есть, здравствуйте, могут, сидят, пришли, стали, ходят, вышли, говорят, дайте</li>
      <li>VERB-Part: организованных, живущих, изложенным, Входящим, Гомонящих, Напоминающие, Понаехавшие, Приведенные, Прогретых, Рокочущим</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Sing
    <ul>
      <li>ADJ: святую, нужно, большой, сам, первый, вторая, дохлой, другой, новый, сама</li>
      <li>ADV: Нихера, Судак, красиво, максимум</li>
      <li>AUX: было, был, будет, была, есть, буду, будешь, будь, бывшая</li>
      <li>AUX-Fin: было, был, будет, была, есть, буду, будешь, будь</li>
      <li>DET: этот, такой, мой, наш, этой, свой, своей, какой, это, такая</li>
      <li>NOUN: день, время, море, года, мир, воды, жизни, спасибо, фото, человек</li>
      <li>NOUN-Fin: #самолет</li>
      <li>NOUN-Part: прошедшим</li>
      <li>NUM: один, одна, одно, Днём</li>
      <li>PRON: я, это, он, ты, мне, меня, что, она, всё, кто</li>
      <li>PROPN: жириновский, ЛДПР, парнас, яблоко, России, Россия, Русь, кпрф, крым, жириновского</li>
      <li>PUNCT: 1⃣, 2⃣, 3⃣, 4⃣, 5⃣</li>
      <li>SCONJ: что</li>
      <li>SYM: $, %, ♥️, ❤️, 🌊🥰</li>
      <li>VERB: есть, может, нет, сказал, стоит, говорит, вижу, понимаю, сидит, думаю</li>
      <li>VERB-Fin: есть, может, нет, сказал, стоит, говорит, вижу, понимаю, сидит, думаю</li>
      <li>VERB-Part: написано, Восхищена, Беременная, Ведущим, Венчанный, Вспотевшим, Входящая, Заглохший, Зимой, Изрытый</li>
      <li>X: @screened-18, #НН, #дизайнспальни, корпусе</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Case</a></li>
</ul>

<ul>
  <li>Acc
    <ul>
      <li>ADJ: святую, большую, первый, новую, последние, целый, Европейский, бесполезный, большой, второе</li>
      <li>DET: все, свой, эти, свои, этот, нашу, каждый, это, эту, ваши</li>
      <li>NOUN: день, раз, время, голову, партию, руки, ночь, рот, год, работу</li>
      <li>NUM: много, несколько, два, столько, один, сто, двоих, восемь, двадцать, две</li>
      <li>PRON: что, их, меня, нас, это, вас, себя, его, тебя, все</li>
      <li>PROPN: Русь, крым, госдуму, ПАРНАС, Бога, Жириновского, Россию, Стереолето, Францию, Гиркина</li>
      <li>SCONJ: что</li>
      <li>VERB-Part: Заглохший, бегущий, блещущий, влекомый, гаснущие, дрожащий, желающих, забытый, зажатый, заплеванные</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Dat
    <ul>
      <li>ADJ: другому, крайней, 2м, 3м, Великой, Гражданской, Пастушеской, Продиточному, Русской, Самым</li>
      <li>DET: всем, этому, вашему, каждому, моим, своему, своим, МОЕМУ, Моему, Тому</li>
      <li>NOUN: детям, сожалению, Взрослым, времени, мужчинам, телефону, бандиту, богу, ветрам, годам</li>
      <li>NUM: пяти, стольким</li>
      <li>PRON: мне, себе, вам, нам, им, ему, тебе, всем, ей, кому</li>
      <li>PROPN: Богу, зюганову, Амстердаму, Анастасии, Андреянову, Анне, Балеевой, Вархаре, Васильевой, Вениаминовне</li>
      <li>VERB: изложенным, нечему, Ведущим, Вспотевшим, Входящим, Уносимым, говорящему, действующим, клонившимся, подросшей</li>
      <li>VERB-Part: изложенным, Ведущим, Вспотевшим, Входящим, Уносимым, говорящему, действующим, клонившимся, подросшей, понаехавшим</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Gen
    <ul>
      <li>ADJ: разных, других, Единой, гражданской, дохлых, кривых, самого, самых, Приятного, второго</li>
      <li>DET: всех, этой, наших, тех, нашего, таких, этих, своей, моего, моих</li>
      <li>NOUN: лет, раз, года, воды, детей, дня, минут, раза, людей, партии</li>
      <li>NUM: двух, одного, двоих, многих, 30-ти, восьми, двадцати, десяти, одной, пяти</li>
      <li>PRON: нас, меня, ничего, вас, них, чего, всего, того, этого, тебя</li>
      <li>PROPN: ЛДПР, России, Госдумы, жириновского, СССР, яблока, ЕР, КПРФ, Путина, Анны</li>
      <li>PUNCT: 1⃣, 2⃣, 3⃣, 4⃣, 5⃣</li>
      <li>SYM: %, $, ♥️, ❤️, 🌊🥰</li>
      <li>VERB: нечего, организованных, живущих, Гомонящих, Надевши, Назначенной, Прогретых, Служивших, битых, возвратившихся</li>
      <li>VERB-Part: организованных, живущих, Гомонящих, Назначенной, Прогретых, Служивших, битых, возвратившихся, воспетого, воспринимаемого</li>
      <li>X: Анти, #дизайнспальни</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Ins
    <ul>
      <li>ADJ: тяжелым, Божьим, великим, верхними, внутренней, глубокой, горячей, другими, другой, золотой</li>
      <li>DET: своими, таким, своей, такой, теми, той, этими, каждым, какой, моей</li>
      <li>NOUN: зимой, праздником, водой, помощью, головой, днем, летом, рукой, трудом, P.S.</li>
      <li>NOUN-Part: прошедшим</li>
      <li>NUM: двумя, Днём, одним</li>
      <li>PRON: собой, чем, ним, вами, ней, тем, нами, тобой, мной, ничем</li>
      <li>PROPN: Зюгановым, Анной, Боровом, В, Вадимом, Вассерманом, Вунгтау, ГД, Господом, Дамиром</li>
      <li>VERB-Part: Зимой, Рокочущим, Узаконенными, верующим, выдавленным, замирающей, исходящим, молящейся, освобождаемой, оформленным</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Loc
    <ul>
      <li>ADJ: дохлой, общем, прямом, чужом, водяной, конечном, личной, полном, русском, самом</li>
      <li>DET: этой, этом, моей, нашем, своей, своем, той, том, всех, каждой</li>
      <li>NOUN: жизни, мире, выборах, голове, земле, стране, году, море, числе, воде</li>
      <li>NUM: трех, двух, одной, одном</li>
      <li>PRON: том, себе, этом, чем, нем, ней, всем, мне, чём, которой</li>
      <li>PROPN: Крыму, Москве, России, Сочи, донбассе, Госдуме, Кремле, Латвии, Львове, Перми</li>
      <li>VERB-Part: действующем, затерявшемся, затуманенном, обтягивающих, оккупированном, оставшемся, охраняемых, перекрашенном, сбывшейся, сомкнутых</li>
      <li>X: корпусе</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Nom
    <ul>
      <li>ADJ: сам, вторая, сама, добрый, живые, самый, большой, золотые, новый, первая</li>
      <li>ADV: Нихера, Судак, максимум</li>
      <li>AUX: бывшая</li>
      <li>DET: все, этот, мои, мой, наш, такая, эти, моя, такие, такой</li>
      <li>NOUN: люди, спасибо, мир, человек, баба, время, друзья, мл, море, пропитка</li>
      <li>NUM: три, двое, один, много, одно, два, сколько, четыре, одна, восемь</li>
      <li>PRON: я, это, он, мы, ты, вы, что, кто, они, она</li>
      <li>PROPN: жириновский, Яблоко, парнас, Россия, Женя, ЛДПР, жирик, Бог, Явлинский, Анна</li>
      <li>SCONJ: что</li>
      <li>VERB: Беременная, Венчанный, Входящая, Изрытый, Напоминающие, Овеществленный, Понаехавшие, Приведенные, Пьющая, Рек</li>
      <li>VERB-Part: Беременная, Венчанный, Входящая, Изрытый, Напоминающие, Овеществленный, Понаехавшие, Приведенные, Пьющая, Стоявшие</li>
      <li>X: @screened-18, #НН</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Par
    <ul>
      <li>NOUN: разу, Воску, азу, толку, чаю</li>
      <li>PRON: чего</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Voc
    <ul>
      <li>NOUN: Боже, золотце, ребят</li>
      <li>PROPN: Боже, Катюнь, Серёж</li>
    </ul>
  </li>
</ul>



<h3>Degree and Polarity</h3>


<ul>
  <li><a>Degree</a></li>
</ul>

<ul>
  <li>Cmp
    <ul>
      <li>ADJ: лучше, выше, старше, ближе, больше, дороже, легче, сильнее, Вожделенней, Гнилее</li>
      <li>ADV: больше, более, дальше, лучше, менее, быстрее, раньше, скорее, Подробнее, ащщще</li>
      <li>NOUN: чище</li>
      <li>NUM: больше, меньше</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Pos
    <ul>
      <li>ADJ: святую, нужно, большой, сам, первый, разных, вторая, дохлой, других, другой</li>
      <li>ADV: так, где, как, там, уже, еще, тут, очень, теперь, ещё</li>
      <li>DET: одна, одних, одно</li>
      <li>NOUN: #фотодня, Дома</li>
      <li>NUM: много, один</li>
      <li>PROPN: Тосненский</li>
      <li>SCONJ: пока, Поэтому, так</li>
      <li>VERB: можно, надо, жаль, нельзя, против, нах, охота</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Sup
    <ul>
      <li>ADJ: Добрейшим, крупнейшего</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Polarity</a></li>
</ul>

<ul>
  <li>Neg
    <ul>
      <li>CCONJ: ни</li>
      <li>PART: не, ни, неее</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Variant</a></li>
</ul>

<ul>
  <li>Short
    <ul>
      <li>ADJ: нужно, странно, хорошо, должна, круто, нужны, равно, рады, должно, нужен</li>
      <li>ADV: красиво</li>
      <li>DET: Такова, о́но, таков</li>
      <li>NOUN: тесен</li>
      <li>VERB-Part: написано, Восхищена, Куплена, Приглашён, Уничножен, блюдет, брошен, возвышен, вознагражден, вручена</li>
    </ul>
  </li>
</ul>

<h3>Verbal Features</h3>


<ul>
  <li><a>Aspect</a></li>
</ul>

<ul>
  <li>Imp
    <ul>
      <li>AUX: было, был, будет, быть, была, есть, были, будут, буду, будем</li>
      <li>AUX-Conv: будучи</li>
      <li>AUX-Fin: было, был, будет, была, есть, были, будут, буду, будем, будешь</li>
      <li>AUX-Inf: быть</li>
      <li>NOUN-Fin: #самолет</li>
      <li>PROPN-Fin: #сургут</li>
      <li>VERB-Conv: судя, говоря, Благодаря, бежа, видя, встречая, держа, дрожа, занимаясь, исчезая</li>
      <li>VERB-Fin: есть, может, нет, стоит, говорит, вижу, понимаю, сидит, думаю, здравствуйте</li>
      <li>VERB-Inf: делать, жить, быть, думать, смотреть, голосовать, видеть, идти, есть, играть</li>
      <li>VERB-Part: живущих, Ведущим, Входящая, Входящим, Гомонящих, Зимой, Напоминающие, Пьющая, Рокочущим, Служивших</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Perf
    <ul>
      <li>NOUN-Part: прошедшим</li>
      <li>VERB-Conv: доставши, оставив, поднявши, Исполняся, Присев, Проливши, Склонясь, Угодив, Уйдя, восстав</li>
      <li>VERB-Fin: сказал, стал, пришли, случилось, стали, стало, вышли, дайте, ляжем, начал</li>
      <li>VERB-Inf: сделать, добавить, показать, дать, залить, найти, поставить, взять, довести, изменить</li>
      <li>VERB-Part: написано, организованных, Восхищена, изложенным, Беременная, Венчанный, Вспотевшим, Заглохший, Изрытый, Куплена</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Mood</a></li>
</ul>

<ul>
  <li>Cnd
    <ul>
      <li>AUX: бы, б</li>
      <li>PART: бы</li>
      <li>SCONJ: чтобы, чтоб</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Imp
    <ul>
      <li>AUX: будь, будьте</li>
      <li>AUX-Fin: будь</li>
      <li>PART: давайте</li>
      <li>VERB-Fin: здравствуйте, дайте, давай, думай, надавите, пиши, прости, скажите, уходи, Покажи</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Ind
    <ul>
      <li>AUX-Fin: было, был, будет, была, есть, были, будут, буду, будем, будешь</li>
      <li>NOUN-Fin: #самолет</li>
      <li>PROPN-Fin: #сургут</li>
      <li>VERB-Fin: есть, может, нет, сказал, стоит, говорит, вижу, понимаю, сидит, думаю</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Tense</a></li>
</ul>

<ul>
  <li>Fut
    <ul>
      <li>VERB-Fin: ляжем, скажу, скажет, сможет, даст, получится, поможет, смогу, станет, Поднимем</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Past
    <ul>
      <li>AUX-Fin: было, был, была, были</li>
      <li>NOUN-Part: прошедшим</li>
      <li>VERB-Conv: доставши, оставив, поднявши, Исполняся, Присев, Проливши, Склонясь, Угодив, Уйдя, восстав</li>
      <li>VERB-Fin: сказал, стал, было, видел, видела, говорил, пришли, случилось, стали, стало</li>
      <li>VERB-Part: написано, организованных, Восхищена, изложенным, Беременная, Венчанный, Вспотевшим, Заглохший, Изрытый, Куплена</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Pres
    <ul>
      <li>AUX-Conv: будучи</li>
      <li>AUX-Fin: будет, есть, будут, буду, будем, будешь, будете</li>
      <li>NOUN-Fin: #самолет</li>
      <li>PROPN-Fin: #сургут</li>
      <li>VERB-Conv: судя, говоря, Благодаря, бежа, видя, встречая, держа, дрожа, занимаясь, исчезая</li>
      <li>VERB-Fin: есть, может, нет, стоит, говорит, вижу, понимаю, сидит, думаю, могут</li>
      <li>VERB-Part: живущих, Ведущим, Входящая, Входящим, Гомонящих, Зимой, Напоминающие, Пьющая, Рокочущим, Уносимым</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Voice</a></li>
</ul>

<ul>
  <li>Act
    <ul>
      <li>AUX-Conv: будучи</li>
      <li>AUX-Fin: было, был, будет, была, есть, были, будут, буду, будем, будешь</li>
      <li>AUX-Inf: быть</li>
      <li>NOUN-Fin: #самолет</li>
      <li>NOUN-Part: прошедшим</li>
      <li>PROPN-Fin: #сургут</li>
      <li>VERB-Conv: судя, говоря, Благодаря, бежа, видя, встречая, держа, доставши, дрожа, исчезая</li>
      <li>VERB-Fin: есть, может, нет, сказал, стоит, говорит, вижу, понимаю, сидит, думаю</li>
      <li>VERB-Inf: сделать, делать, жить, добавить, быть, думать, показать, смотреть, голосовать, видеть</li>
      <li>VERB-Part: живущих, Ведущим, Вспотевшим, Входящая, Входящим, Гомонящих, Заглохший, Напоминающие, Понаехавшие, Пьющая</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Mid
    <ul>
      <li>VERB-Conv: занимаясь, пытаясь, Дивяся, Исполняся, Находясь, Отодвигаясь, Склонясь, виясь, возвращаясь, двигаясь</li>
      <li>VERB-Fin: кажется, случилось, надеюсь, хотелось, хочется, боюсь, называется, остается, получается, понравилось</li>
      <li>VERB-Inf: заниматься, улыбнуться, заняться, настояться, нравиться, погрузиться, Выпендриваться, Обращаться, Прикоснуться, ассимилироваться</li>
      <li>VERB-Part: возвратившихся, затерявшемся, казавшаяся, касающихся, клонившимся, купающихся, молящейся, нагревшуюся, оставшемся, открывшихся</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Pass
    <ul>
      <li>VERB-Fin: Вбрасывается, Вздымалась, Делается, водятся, воспитываются, встречался, готовится, использовалась, использовался, используются</li>
      <li>VERB-Inf: приниматься</li>
      <li>VERB-Part: написано, организованных, Восхищена, изложенным, Беременная, Венчанный, Зимой, Изрытый, Куплена, Назначенной</li>
    </ul>
  </li>
</ul>


<h3>Pronouns, Determiners, Quantifiers</h3>






<ul>
  <li><a>Person</a></li>
</ul>

<ul>
  <li>1
    <ul>
      <li>AUX-Fin: буду, будем</li>
      <li>PRON: я, мы, мне, нас, меня, нам, нами, мной, на, унас</li>
      <li>VERB-Fin: вижу, понимаю, думаю, хочу, люблю, могу, знаю, прошу, сижу, говорю</li>
    </ul>
  </li>
</ul>

<ul>
  <li>2
    <ul>
      <li>AUX: будешь, будь, будете, будьте</li>
      <li>AUX-Fin: будешь, будь, будете</li>
      <li>PRON: ты, вы, вас, вам, тебя, тебе, вами, тобой, тобою</li>
      <li>VERB-Fin: здравствуйте, дайте, можешь, давай, думай, знаете, знаешь, хочешь, надавите, пиши</li>
    </ul>
  </li>
</ul>

<ul>
  <li>3
    <ul>
      <li>AUX-Fin: будет, есть, будут</li>
      <li>DET: его, ее</li>
      <li>NOUN-Fin: #самолет</li>
      <li>PRON: он, они, она, их, им, них, его, ему, ней, ним</li>
      <li>PROPN-Fin: #сургут</li>
      <li>VERB-Fin: есть, может, нет, стоит, говорит, сидит, могут, бывает, знает, хочет</li>
    </ul>
  </li>
</ul>




<h3>Other Features</h3>


<ul>
  <li><a>Abbr</a>
    <ul>
      <li>Yes
        <ul>
          <li>ADJ: ст., ч., cт., кв., п., сах., Б., Гос., Сов, бывш.</li>
          <li>ADP: п</li>
          <li>ADV: д., т., т</li>
          <li>DET: т.</li>
          <li>NOUN: л., г, гр., млн., руб., ст, ЗП, МРОТ, ТВ, Щ</li>
          <li>NUM: тыс</li>
          <li>PRON: т., кот.</li>
          <li>PROPN: В., Н., П., R., А., ГД, Д., Е., З., И.</li>
          <li>VERB: е., и., созд</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Foreign</a>
    <ul>
      <li>Yes
        <ul>
          <li>CCONJ: А</li>
          <li>INTJ: Nice</li>
          <li>NOUN: RT, #hotel_grafit, крейзи</li>
          <li>PART: PROFIT, ХАЙ, Хэллоу</li>
          <li>PROPN: ART, ForcePower, iPhone, playstation, :D, @screened-210, Abracadabra, Aluminum, Apple, Billy</li>
          <li>VERB: МАНДРУЕ</li>
          <li>X: *, @screened-200, @screened-134, @screened-15, #astrakhan, #fishing, #gopro, #russia, #sochifornia, @screened-150</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>Typo</a>
    <ul>
      <li>Yes
        <ul>
          <li>NUM: з, не</li>
          <li>VERB-Fin: вопиют</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<h2>Syntax</h2>

<h3>Auxiliary Verbs and Copula</h3>

<ul>
<li>This corpus uses 2 lemmas as copulas (<a>cop</a>). Examples: быть, это.</li>
</ul>

<ul>
<li>This corpus uses 3 lemmas as auxiliaries (<a>aux</a>). Examples: быть, бы, б.</li>
<li>This corpus uses 1 lemmas as passive auxiliaries (<a>aux:pass</a>). Examples: быть.</li>
</ul>

<h3>Core Arguments, Oblique Arguments and Adjuncts</h3>

Here we consider only relations between verbs (parent) and nouns or pronouns (child).
<ul>
  <li><a>nsubj</a>
    <ul>
      <li>VERB--NOUN-Gen (11)</li>
      <li>VERB--NOUN-Nom (4)</li>
      <li>VERB--PRON-Acc (1)</li>
      <li>VERB--PRON-Gen (1)</li>
      <li>VERB--PRON-Nom (2)</li>
      <li>VERB-Conv--NOUN-Nom (1)</li>
      <li>VERB-Fin--NOUN-Acc (3)</li>
      <li>VERB-Fin--NOUN-Gen (55)</li>
      <li>VERB-Fin--NOUN-Gen-ADP(порядка) (1)</li>
      <li>VERB-Fin--NOUN-Nom (934)</li>
      <li>VERB-Fin--NOUN-Nom-ADP(как) (2)</li>
      <li>VERB-Fin--PRON-Acc (1)</li>
      <li>VERB-Fin--PRON-Dat (1)</li>
      <li>VERB-Fin--PRON-Gen (8)</li>
      <li>VERB-Fin--PRON-Nom (740)</li>
      <li>VERB-Inf--NOUN-Acc (1)</li>
      <li>VERB-Inf--NOUN-Gen (2)</li>
      <li>VERB-Inf--NOUN-Nom (13)</li>
      <li>VERB-Inf--PRON-Gen (1)</li>
      <li>VERB-Inf--PRON-Nom (16)</li>
      <li>VERB-Part--NOUN-Nom (7)</li>
      <li>VERB-Part--PRON-Nom (2)</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>obj</a>
    <ul>
      <li>VERB--NOUN-Acc (3)</li>
      <li>VERB--NOUN-Gen (5)</li>
      <li>VERB--PRON-Gen (1)</li>
      <li>VERB--PRON-Par (1)</li>
      <li>VERB-Conv--NOUN-Acc (64)</li>
      <li>VERB-Conv--NOUN-Dat (1)</li>
      <li>VERB-Conv--NOUN-Gen (5)</li>
      <li>VERB-Conv--NOUN-Ins (3)</li>
      <li>VERB-Conv--PRON-Acc (5)</li>
      <li>VERB-Conv--PRON-Nom (1)</li>
      <li>VERB-Fin--NOUN (2)</li>
      <li>VERB-Fin--NOUN-Acc (613)</li>
      <li>VERB-Fin--NOUN-Acc-ADP(в) (1)</li>
      <li>VERB-Fin--NOUN-Acc-ADP(из) (1)</li>
      <li>VERB-Fin--NOUN-Acc-ADP(к) (1)</li>
      <li>VERB-Fin--NOUN-Acc-ADP(среди) (1)</li>
      <li>VERB-Fin--NOUN-Dat (11)</li>
      <li>VERB-Fin--NOUN-Dat-ADP(по) (2)</li>
      <li>VERB-Fin--NOUN-Gen (88)</li>
      <li>VERB-Fin--NOUN-Ins (33)</li>
      <li>VERB-Fin--NOUN-Nom (9)</li>
      <li>VERB-Fin--NOUN-Par (1)</li>
      <li>VERB-Fin--PRON (1)</li>
      <li>VERB-Fin--PRON-Acc (155)</li>
      <li>VERB-Fin--PRON-Dat (5)</li>
      <li>VERB-Fin--PRON-Gen (14)</li>
      <li>VERB-Fin--PRON-Ins (8)</li>
      <li>VERB-Inf--NOUN (5)</li>
      <li>VERB-Inf--NOUN-Acc (233)</li>
      <li>VERB-Inf--NOUN-Acc-ADP(на) (2)</li>
      <li>VERB-Inf--NOUN-Dat (2)</li>
      <li>VERB-Inf--NOUN-Dat-ADP(по) (1)</li>
      <li>VERB-Inf--NOUN-Gen (18)</li>
      <li>VERB-Inf--NOUN-Gen-ADP(на) (1)</li>
      <li>VERB-Inf--NOUN-Ins (8)</li>
      <li>VERB-Inf--NOUN-Nom (1)</li>
      <li>VERB-Inf--NOUN-Par (1)</li>
      <li>VERB-Inf--PRON-Acc (49)</li>
      <li>VERB-Inf--PRON-Dat (1)</li>
      <li>VERB-Inf--PRON-Gen (5)</li>
      <li>VERB-Inf--PRON-Ins (1)</li>
      <li>VERB-Part--NOUN-Acc (18)</li>
      <li>VERB-Part--NOUN-Gen (3)</li>
      <li>VERB-Part--NOUN-Ins (2)</li>
      <li>VERB-Part--PRON-Acc (1)</li>
      <li>VERB-Part--PRON-Ins-ADP(за) (1)</li>
    </ul>
  </li>
</ul>

<ul>
  <li><a>iobj</a>
    <ul>
      <li>VERB--NOUN-Ins (2)</li>
      <li>VERB--PRON-Dat (9)</li>
      <li>VERB-Conv--NOUN-Dat (1)</li>
      <li>VERB-Conv--NOUN-Ins (13)</li>
      <li>VERB-Conv--PRON-Dat (2)</li>
      <li>VERB-Conv--PRON-Ins (1)</li>
      <li>VERB-Fin--NOUN-Acc (1)</li>
      <li>VERB-Fin--NOUN-Dat (51)</li>
      <li>VERB-Fin--NOUN-Dat-ADP(в) (1)</li>
      <li>VERB-Fin--NOUN-Ins (92)</li>
      <li>VERB-Fin--NOUN-Ins-ADP(через) (1)</li>
      <li>VERB-Fin--NOUN-Nom (1)</li>
      <li>VERB-Fin--PRON (1)</li>
      <li>VERB-Fin--PRON-Dat (102)</li>
      <li>VERB-Fin--PRON-Ins (6)</li>
      <li>VERB-Fin--PRON-Nom (1)</li>
      <li>VERB-Inf--NOUN (1)</li>
      <li>VERB-Inf--NOUN-Dat (12)</li>
      <li>VERB-Inf--NOUN-Gen (1)</li>
      <li>VERB-Inf--NOUN-Ins (33)</li>
      <li>VERB-Inf--PRON-Dat (24)</li>
      <li>VERB-Inf--PRON-Ins (5)</li>
      <li>VERB-Part--NOUN-Dat (4)</li>
      <li>VERB-Part--NOUN-Ins (22)</li>
      <li>VERB-Part--PRON-Dat (2)</li>
      <li>VERB-Part--PRON-Ins (1)</li>
    </ul>
  </li>
</ul>




<h3>Relations Overview</h3>

<ul>
<li>This corpus uses 8 relation subtypes: <a>acl:relcl</a>, <a>aux:pass</a>, <a>flat:foreign</a>, <a>flat:name</a>, <a>nsubj:pass</a>, <a>nummod:entity</a>, <a>nummod:gov</a>, <a>obl:agent</a></li>
<li>The following 1 relation types are not used in this corpus at all: <a>clf</a></li>
</ul>
