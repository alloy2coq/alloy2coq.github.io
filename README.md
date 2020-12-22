# What is alloy2coq~?

Alloy is both a formal language and a tool for software modeling. The
language is basically first order relational logic. The analyzer is
based on instance finding: it tries to refute assertions and if it
succeeds it reports a counterexample. It works by translating Alloy
models and instance finding into SAT problems. If no instance is found
it does not mean the assertion is satisfied. Alloy relies on the small
scope hypothesis: examining all small cases is likely to produce
interesting counterexamples. This is very valuable when developing a
system. However Alloy cannot show their absence. The CompCert compiler
or the seL4 kernel have attained a high level of assurance because
interactive theorem provers have been used to prove the absence of
bugs.

We propose an approach where Alloy can be used as a first step, and
then using a tool we develop, Alloy models can be translated to Coq
code to be proved correct interactively.

# alloy2coq Code

Coming soon !
   
# Current Team

- Frédéric Loulergue (Université d'Orléans, LIFO, France)
- Salwa Souaf (Centrale Supélec, Rennes, France)

# Publications

## Conferences with Proceedings

1. Salwa Souaf and Frédéric Loulergue. A first step in the translation of Alloy to Coq. In International Conference on Formal Engineering Methods (ICFEM), LNCS, pages 455--469. Springer, November 2019, [doi http://dx.doi.org/10.1007/978-3-030-32409-4_28]

## Thesis / Dissertation

1. Salwa Souaf. Formal Methods Meet Security in a Cost Efficient Cloud Brokerage Solution. PhD Thesis, INSA Centre Val-de-Loire, December 2020

## Poster Presentation with Proceedings

1. Salwa Souaf and Frédéric Loulergue. Strong security guarantees: from Alloy to Coq (poster). In International Conference on High Performance Computing and Simulation (HPCS), pages 1057--1058, Orléans, France, IEEE, 2018, [doi http://dx.doi.org/10.1109/HPCS.2018.00167]


