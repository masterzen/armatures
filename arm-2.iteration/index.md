---
layout: page
title: Iteration
arm: 2
champion: hlindberg
revision: 1.0.0
project: https://github.com/hlindberg/arm
implementation: ["https://github.com/puppetlabs/puppet/tree/feature/master/future-parser"]
requires-arms: []
issues: ["http://projects.puppetlabs.com/issues/11331", "http://projects.puppetlabs.com/issues/18764"]
main-page: true
---

Index of ARM-2.Iteration
========================
This arm proposes a solution for handling "iteration".

The proposal is based on ruby/java-8 syntax for lambda and enumerables
support adapted to the Puppet Language.

An alternative idea based on a "Unix Pipes" is also presented.

* **[Iteration](iteration.html)**  
  The proposal to add lambda and iteration functions. Start reading here.
* **[Examples](examples.html)**  
  Real world examples expressed using the recommended implementation.
* [Evaluation](evaluation.html)  
  Contains a list of options to consider with rationale why an option may be appealing (or why not).
* [Recommendation](recommendation.html)  
  The current recommendation (i.e. what is described in the main document's description).
* [Implementation](implementation.html)  
  Notes about the available implementation.
* [Pipes Based Alternative](pipe_alternative.html)    
  An alternative syntax for describing iteration based loosely on "unix pipes".
* [Alternatives](alternatives.html)  
  A description of investigated alternatives with rationale why they were considered, and why they were not
  seen as viable solutions. (Viable options and alternatives are in the main document, and in the "Pipe Based Alternative").
