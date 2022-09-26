## Every lobster should have a name. Would you agree?

This is the premise for the famous challenge that Cardano's first ever smart contract tried to answer.

With this toy daml model we try to recreate the same contract.

* A DAO decides to create a vote to give a name to Charles' favourite mascot.
* Each end user will be allowed to vote only once.
* Upon voting the user will decide on an  Integer value between 1 and 100.
* Once cast this value is accumulated to others.
* At the end of the vote, the DAO's own vote value is added to the total and its modulo over the number of proposed name serves as an index to the chosen name.


![This is an image](/assets/images//lobstervote.vote.jpg)

![This is an image](/assets/images//lobstervote.voteresult.jpg)




