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

This text is approaching stability, yet remains under active, albeit intermittent, revision. The current public version of the text should remain broadly stable for the remainder of 2021, as it is being used as a textbook in our *Introduction to Logic* courses. 

I welcome comments, notification of errors and typos, and any new ideas: [antony.eagle@adelaide.edu.au](mailto:antony.eagle@adelaide.edu.au?subject=forallx-adl). I will update this readme with a list of issues and proposed changes. But I will not push changes until the course is over. 

The following list contains current issues and proposed revisions arranged by chapter, most as rather cryptic notes to myself. Most chapters and sections from chapter 4 onwards also have additional practice problems to be included.

* Chapter 1 (`forallx-adl-what.tex`) 
* Chapter 2 (`forallx-adl-tfl.tex`)
* Chapter 3 (`forallx-adl-truthtables.tex`)
* Chapter 4 (`forallx-adl-fol.tex`)
	- §18
		+ more practice exercises – pure numerical quantification, perhaps from edl textbook or logic manual?
		+ a discussion of how identity, innocuous enough in itself, greatly enriches the expressive power of Quantifier.
	- §19
		- Note that two descriptions can be symbolised with just one existential: `There is someone who: is a spy; and is the unique spy; and is an escapee; and is the unique escapee'.
		- Perhaps replace §19.3 with a section on whether Russell is offering a model or an analysis – the scope stuff is evidence for the analysis, and then the Strawson-Frege view is the rival (in which the apparent scope effects are treated as whether the proposition about the F or a presupposition that there is a unique F is being rejected).

* Chapter 5 (`forallx-adl-interpretations.tex`)
	- §21
		- domains as needed for extensions.
		- add example of euler with a dot – e.g. willard
	- §22
		- deal with one-place and many-place predicates differently. 
		- use notion of `\ntuple` explicitly in defs of truth for atomic.
		- add diagrams showing different extended interpretations stemming from a starting interpretation.
		- add 'why don't we do this?' section to quantifier intepretation 	 
	- §23
		- need to expand with examples, and practice problems
		- change contradiction to logical falsehood
	- §25
		- practice problems
		- mention infinity of intepretations, contrast with sentential case.  	    
* Chapter 6 (`forallx-adl-prooftfl.tex`)
	- §26
		+ Need a practice exercise
		+ add some discussion of epistemology of reasoning – validity is not sufficient for good reasoning, even if it is necessary.
	- §27
		+ add mention that any proof opened with an assumption is already a correct proof.
		+ More on the way that we can use formal proofs to parallel English arguments – the skills are formal, but the motivation is coming up with principles that also govern good arguments in natural language. Indeed, many philosophers write as if they have a natural deduction argument in their head, and their prose just 'de-symbolises' it. Not perhaps the most elegant, but clear, easy to grasp structure, and hopefully good!
	- §28
		+ Mention the first 'rule' which is that we can open an assumption whenever we want. put it alongside Reiteration as a 'connective-insensitive' rule.
	- §29
		+ ramsey quote in conditional intro
	- §31
		- weakening
		- deduction theorem for `\vdash`
		- entailment (doesn't exist a certain kind of valuation) vs provability (does exist a certain kind of proof)
		- general principle about how we can prove a theorem: must finish a proof with the right kind of rule (bi/conditional intro or ¬ rules) becaue every proof begins with an assumption
		- emphasise relation between easy semantic tasks and tricky proofs, and vice versa  
	- §33
		+ §33.1: mention explicitly that reiteration cannot be used outside a subproof 

* Chapter 7 (`forallx-adl-prooffol.tex`)
	- §35
		+ does the `\vdash` terminology get re-introduced?
		+ make explicit that the choice of a new name in `\exists`E is a way of ensuring you meet all the conditions; and make sure that students know choosing a new name is also a way of meeting the conditions on `\forall`I.
	- §37
	- §38 
		+ some ideas about where next in logic
* Backmatter











