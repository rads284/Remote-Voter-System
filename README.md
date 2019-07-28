# Remote-Voter-System

## Idea: Make an application that helps people to vote from remote locations.

A good percentage of today's student and working population do not live in the consituency in which they are registered voters. We are attempting to solve this problem by providing verified and anonymous voting remotely, to such voters, leveraging a blockchain based remote voting solution. 

Issues to be tackled:
- Voting list can not be verified when person not in the location he/she was registered in.
- Identity of voter has to be verified.
- Anonimity of vote has to be maintained.
- Verifiability of each vote

Suggested Solution:
- The identity of the voter can be authenticated by verifying against a distributed ledger of already existent government records, such as Voters id or Aadhar. 
- An app that records the vote of the user by first matching his credentials (possibly biometric) against the data stored in the blockchain is used for collection of votes. 
- Anonimity of the user is maintained by using private/public keys as in the bitcoin system 
- Verifiability of the vote against falsification can be done through the issuance of a digital token for each vote that is cast
