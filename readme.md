Forall*x* Adelaide
==================

This is [Antony Eagle](https://antonyeagle.org)'s version of [Tim Button](http://nottub.com)'s version of [PD Magnus](https://www.fecundity.com/job/)'s forall*x*. There are pervasive differences, big and small, cosmetic and substantial.

License
-------

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License]("http://creativecommons.org/licenses/by/4.0/).

Source code
-----------

The LaTeX source code for this work is available on GitHub at [github.com/antonyeagle/forallx-adl](https://github.com/antonyeagle/forallx-adl)

Current issues and proposed revisions
-------------------------------------

This text is under active yet sporadic revision. The list of items below is primarily for me, and some of it is rather cryptic, but it may be useful for readers to see proposed changes.


* Chapter 1
* Chapter 2
	- Add examples of expressions which are not sentences; explain why.
* Chapter 3
	- Add the use of partial truth tables as a test for validity: e.g., when you can construct one, it is invalid, when you cannot construct one, it is valid. Explain why this works – only finitely many valuations to consider.
* Chapter 4
	- Add something on sentence structure to §15, e.g.,

		> As the textbook emphasises in §4.2, a single English sentence has many structures, depending on how fine-grained one is in the analysis of that sentence. We could symbolise 'Antony owns a car' by an atomic sentence, either using a zero-place predicate (i.e., atomic sentence of `\TFL`) 'A'  or as a subject-predicate sentence 'Wa' (where 'Wx' is '`\gap{x}` owns a car' and 'a' is 'Antony')  or as a complex quantified predicate '∃y (Cy ∧ Oay)' (where 'a' is as before, but 'Cx' means '`\gap{x}` is a car' and 'Oxy' is '`\gap{x}` owns `\gap{y}`'). How to symbolise the structure of a sentence very much depends on what purpose you have in symbolising. In the original symbolisation I gave, I managed to represent enough structure to show that the original argument is valid. Since any more fine-grained analysis of the structure would retain the original structure (as it just adds more detailed substructure), any argument conclusive in virtue of structure will remain conclusive in virtue of any more fine-grained understanding of that very same structure. So you should aim to symbolise just enough structure in your original argument to be able to demonstrate its validity, if indeed it is valid.
	- Add some discussion of generics and contrast with explicit quantifiers, e.g., in discussion of exercise D.3 in §16:
	
		> Note that the second premise doesn't have an explicit quantifier – it doesn't say '*all* old TV shows are black and white'. It is what is known as a **generic** claim: it shares a structure with examples like 'chickens lay eggs' or 'rocks are hard'. Generic claims concern what is typical or normal: the typical chicken lays eggs, the typical rock is hard, the typical old TV show is black and white. Unlike universally quantified claims, generics are *exception-tolerant*: even if some weird chicken doesn't lay eggs, still, chickens lay eggs. We cannot represent this exception-tolerance very easily in `\FOL`; the closest we can come is to use the universal quantifier, as we have done in this example. (Part of the reason we can't represent it easily is that there is very little consensus on just what these generics do mean – see, for example, the various views discussed in Gregory N Carlson and Francis Jeffry Pelletier, eds., *The Generic Book*, University of Chicago Press 1995.) 
* Chapter 5
	* Add new §21.6: 'Graphical representations of intepretations'.
		1. Venn diagrams and 1-place predicates;
		2. Relational graphs and 2-place predicates.
	* Add material to §22 explaining why we have chosen this approach, rather than e.g., quantifying over names. Why force ourselves to use new names, why is it a bad idea to formulate our clauses like this 
	
		> `$\forall\meta{x}\meta{A}\subs{x}{c}$` is true in an interpretation `$I$` iff in **every** interpretation **just like** `$I$` except that it interprets a new name `\meta{c}` not occurring in `\meta{A}`, `$\meta{A}$` is true.
	
	* Alter semantic clauses for quantifiers to talk about a 'previously uninterpreted name'.
* Chapter 6
	* More informal examples in justifying proof rules
	* Rearrange rules to put rules that do not open a subproof first, then gather those that do next (rather than arranged by connective). Do more to motivate understanding of making assumptions in the course of argument – a discussion about making and discharging assumptions in general.
	* Modify negation rules to involve the derivation of an explicit contradiction *within* the scope of the assumption? Should we use DS for disjunction elimination?
		* Con: both ideas destroy the nice feature of the rules that only one connective is used in any rule, which means that can be discussed separately from one another.
		* Pro: dispense with subproofs for disjunction elimination (proof by cases); elimation rule produces a constituent of original sentence, rather than some new 'C'. 
	* Make sure proof rules use brackets! And maybe note some structural rules explicitly: e.g., that A, B ⊦ A ∧ B and A, B ⊦ B ∧ A$, etc.
	* Give an official introduction to the idea of how to prove an argument in ND – i.e., how to apply the proof system after symbolisation of an argument.
* Chapter 7
* Backmatter
	* In quick reference, add page numbers for original introduction of relevant rules.
* Everywhere
	* Incorporate JO tutorial questions into text














