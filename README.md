# FoncfubuDSL
A theoretical DSL within Ruby or Python to facilitate dataset specific conditionals between French-language and Japanese-language gamedev teams.

A theoretical scripting language for handling datasets in the context of my science fiction setting in my games.

FunctiegalikidaDSL would be the other name for it, and operates in a similar space in programming. In both cases it serves as a cross-cultural language that factors in words without direct translations.

## Disclaimer
This is not intended or designed for the purpose of programming AAA games, and not intended for that purpose. If you someone using Gpose or Upose or anywhere else, you're likely getting scammed by someone violating the creative commons.

## French Specific
~~~
fonc cette_pomme_et_jaune:
  cette "le pomme" == rouge, mais cette "le banane" == jaune:
    parle("That apple is: '); lisen(rouge).
    parle("That banana is: '); lisen(jaune).
  sinon:
    parle("All else is needs not be written.").
  fin
fin
~~~

Suppose this was a French dialect of that-but that-otherwise. The idea here is some things would be in Francais, and otherwise in Nihongo for things that have no equivalent in Francais. Talk me only in English please.

## Japanese Specific
Shouganai   - Cannot be helped / avoided.        Ex. cette "guillotine" == shouganai; parle("Je suis mort"); mort<br />
Wabi-Sabi   - Finding beauty in imperfection.    Ex. In Fruby, "wabisab", or avoid correcting a dataset when the only change is stylistic.<br />
Boketto     - Gazing vacantly into the distance. Ex. In Fruby, this would be used as a verb: to "a bokette", or "to look into" implying a sleep condition before reading.<br />
Fuubutsushi - Anticipate a shift in the dataset that evoke a particular feeling. Ex. Predict sensationalism.

~~~
fubu(rouge). # records state of rogue.
fubu(jaune). # records state of yellow.

wabisab rogue et jaune:           # If change to code is stylistic, maintains to avoid breaking.
  bokette(rouge); bokette(jaune). # Read file with a sleep condition.
shouganai:                        # If breakage unavoidable, isolates it to a folder that isn't otherwise used..
  mod(rogue); mod(jaune).         # Modifies files to avoid conflicting with other datasets.
~~~
