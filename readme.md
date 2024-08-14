Forall*x* Adelaide
==================

This is a derivative work created by [Antony Eagle](https://antonyeagle.org), based upon [Tim Button](http://www.homepages.ucl.ac.uk/~uctytbu/index.html)'s 2016 Cambridge version of [PD Magnus](https://www.fecundity.com/job/)'s forall*x* (version 1.29). There are pervasive substantive changes in content, theoretical approach, coverage, and appearance – it's fair to say no one will mistake this version for Magnus' original.

License
-------

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License]("http://creativecommons.org/licenses/by/4.0/).

Source code
-----------

The LaTeX source code for this work is available on GitHub at [github.com/antonyeagle/forallx-adl](https://github.com/antonyeagle/forallx-adl)

Current issues and proposed revisions
-------------------------------------

As of early 2022, this text is now broadly stable. I do not envisage making substantive further changes in the near future.

I welcome comments, notification of errors and typos, and any new ideas: [antony.eagle@adelaide.edu.au](mailto:antony.eagle@adelaide.edu.au?subject=forallx-adl). I will update this readme with a list of issues and proposed changes even while teaching from the book, but I will not push major changes to the pdf and source until a given course has been delivered and assessed. (I will tacitly correct typos and small errors.)


Current known issues or proposed changes to the text:

* Clarify discussion of parentheses conventions to ensure no impression given that $A \wedge B$ is a sentence, only that the sentence $(A \wedge B)$ can be unambiguously reconstructed from it.
	- Perhaps also remove rule that permits $(A \vee B \vee C)$ to stand indifferently for $(A \vee (B \vee C))$ and $((A \vee B) \vee C)$.
* Consider adding to §33 a discussion of *ex falso quodlibet*.
* Update to new version of `fitch.sty`: [openlogicproject.org/2023/10/16/selingers-fitch-sty-1-0-beta/](https://openlogicproject.org/2023/10/16/selingers-fitch-sty-1-0-beta/). Check for backwards compatibility.
* In Euler diagram section (§21.7), note that one Euler diagram represents many interpretations. So not every sentence is true or false in a given diagram: e.g., though we assume every region is non-empty, we can't assume how many things are in it. So even if there is a region associated with the predicate $B$, we can't tell if $\exists x \exists y (Bx \wedge By \wedge x≠y)$ need not be uniformly true/false in every interpretation associated with the diagram. So we need to change the language to talk of interpretation*s* associated with a given diagram; and also we probaly need to finesse the talk of true in the diagram as something like 'uniformly true on every interpretation representable by the diagram'.

<!-- None -->


<!-- 
* Chapter 1 (`forallx-adl-what.tex`) 
* Chapter 2 (`forallx-adl-tfl.tex`)
* Chapter 3 (`forallx-adl-truthtables.tex`)
* Chapter 4 (`forallx-adl-fol.tex`)
* Chapter 5 (`forallx-adl-interpretations.tex`)
* Chapter 6 (`forallx-adl-prooftfl.tex`)
* Chapter 7 (`forallx-adl-prooffol.tex`)
* Backmatter
 -->








