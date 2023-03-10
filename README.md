# cherry-pi

To react to unforeseen circumstances or amend abnormal situations in communication-centric systems, programmers are in charge of “undoing” the 
interactions which led to an undesired state. To assist this task, session-based languages can be endowed with reversibility mechanisms. **cherry-pi** is  a formal session-based language enriched with programming facilities to *commit* session interactions, to *roll back* the computation to a previous commit point, and to *abort* the session. Rollbacks in cherry-pi always bring the system to previous visited states and a rollback cannot bring the system back to a point prior to the last commit. Programmers are relieved from the burden of ensuring that a rollback never restores a checkpoint imposed by a session participant different from the rollback requester. Such undesired situations are prevented at design-time (statically) by relying on a decidable compliance check at the type level, implemented in MAUDE. The language satisfies error-freedom and progress of a session.

The used version of MAUDE is 3.2.2 for Mac OS X.
