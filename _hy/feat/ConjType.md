---
layout: feature
title: 'ConjType'
shortdef: 'conjunction type'
udver: '2'
---

<table class="typeindex" border="1">
<tr>
  <td style="background-color:cornflowerblue;color:white"><strong>Values:</strong> </td>
  <td><a href="#Comp">Comp</a></td>
  <td><a href="#Oper">Oper</a></td>
</tr>
</table>

This feature further subclassifies the parts of speech [CCONJ]() and [SCONJ]();
in Armenian it is used only with `CCONJ`. The main distinction between coordinating and
subordinating conjunctions is done already at the part-of-speech level.

### `Comp`: comparing conjunction

#### Examples 

* _<b>ոչ միայն</b>... <b>այլ նաև</b>_ “as... than”
* _<b>եթե</b>... <b>ապա</b>_ “...”

### `Oper`: mathematical operator

Note that operators can be expressed either using [symbols](SYM) or using words.
The words are considered special kind of coordinating conjunctions and they are marked using
`ConjType=Oper`.

#### Examples

* _<b>x</b>_ “×”, _<b>անգամ</b>_ “times”, _<b>գումարած</b>_ “plus”, _<b>հանած</b>_ “minus”, _<b>բազմապատկած</b>_ “times”