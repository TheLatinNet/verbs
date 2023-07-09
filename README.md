# The Latin Net - Verbs

The open-source library where we store all the verbs The Latin Net uses.

## Contributions
The file `words.json` contains many different verbs and some information about them:
```
"amo": ["1", "am", "amavi", "love", "loves"]
```
The above example uses the verb 'amare' which means to love. Along with it is:
* The group it is in
  * 1 for verbs like "portare" (group 1)
  * 2 for verbs like "habere" (group 2)
  * 3 for verbs like "bibo" (group 3)
  * 3.5 for verbs like "facere" (mixed 3rd and 4th / group 3 -io)
  * 4 for verbs "dormire" (group 4)
* The stem of the verb
  - Eg. for group 1 "porto, portare" becomes "port"
  - Eg. for group 2 "habeo, habere" becomes "hab"
  - Eg. for group 3 "bibo, bibere" becomes "bib"
  - Eg  for mixed 3rd and 4th "facio, facere" become "fac"
  - Eg. for group 4, "dormio, dormire" becomes "dorm"
* The first person past perfect form of the verb
  *  Eg. for group 1 "porto, portare" becomes "portavi"
  *  Eg. for group 2 "moneo, monere" becomes "monui"
  *  Eg. for group 3 "bibo, bibere" becomes "bibi"
  *  Eg. for mixed 3rd and 4th "facio, facere" becomes "feci"
  *  Eg. for group 4 "dormio, dormire" becomes "dormivi"
* The English Translation
  * Eg. "laborare" would be "work"
  * Also put the English translation for the third person, eg. "~he/she/it~ works" (without the he/she/it part)

Here are examples for all groups:
```
"paro": ["1", "par", "paravi", "prepare", "prepares"]
"timeo": ["2", "tim", "timui", "fear", "fears"]
"lego": ["3", "leg", "legi", "read", "reads"]
"fugio": ["3.5", "fug", "fugi", "flee", "flees"]
"punio": ["4", "pun", "puni", "punish", "punishes"]
```

Fork this repository and add your noun to the end of the previous one, remembering to **add a comma**.
