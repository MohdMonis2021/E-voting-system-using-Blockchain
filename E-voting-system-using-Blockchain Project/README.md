# E-voting-system-using-Blockchain-Technology

A website is designed that will be connected to the backend blockchain smart contract. This website will first authenticate and authorize the user. This is done by taking the information from the user and then that given information will be checked by the information that is already stored in the database which will be kept in a server. That server will be connected to our website by PHP and once the voter inserts his/her information, it will check the authenticity of the voter and only if the voter is eligible to vote i.e. his/her information is present in the database and have not voted before only then the voter will be directed to a webpage from which he/she can vote.
This system will keep a check on the duplicacy of votes i.e. no two votes can be cast from one user. When the authorization will be completed the user will be directed to another webpage which will show the options of the candidates participating in the election so that the user can choose from among those and cast his/her votes.
The webpage which shows the list of candidates for the voter to vote is developed in HTML and connected to a backend blockchain smart contract developed in solidity language. Once the voter has casted the vote, the information will flow through the smart contract and the count of votes of the selected candidate will get updated.
The smart contract will contain all the candidates and their vote counts in separate variables which will be getting updated during the process of voting.