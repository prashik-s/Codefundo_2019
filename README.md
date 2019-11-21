# Overview 
We aim on solving the problem for voting procedure proving transparency to the citizens, strengthning the voting procedure and giving voting option to a person living in a different location.

# Major Ideas
## Voting from anywhere in the country | Ability to vote from anywhere
* Here the voting process will be normal for the citizens within the province but following idea will be used for the ones living in different locations. 
* Voter can register with credentials such as Name, DOB, Aadhar Card Number and 3 security questions to get a unique voter key. 
* This key will be used on the voting day to login on the web app. The voter fills all the information again and the key which are then matched to validate the identity.
* Finally the voter can cast the vote from anywhere in the country. The vote is tallied on the blockchain. Also the user can see details of the candidates in his region before voting and we take special care of fake news and credentials.
**Problem:** Verification of the identity of the voter. Aadhar Card Number and other information can be easily hacked. Further how will it be verified that the citizen belongs to which province.
**Solution:** Giving the user 3 security questions provide strength to the key. The use of cryptographic key provides great security. The validation of the citizen will be done of information such as permanent address and a proof of living in another region.

## Fake/Multiple Voter IDs | Vote Counting
* Initially, the user registers to vote by providing his details. In this step, we can check to see if the details are valid and has not been registered previously.Also we ask to upload/take his photo at the moment and match that on his Aadhar using Microsoft's OCR (Microsoft Computer Vision APIs). If all goes well, we create a private and public key for the voter with the certificate authority running on the cloud and add those.
* After that, they use their UID to submit votes, during which the application checks if he has voted before. Then the vote goes through the consensus policy, and the world state is updated. The application then updates the current election standings..
* Since each transaction submitted to the ordering service must have a signature from a valid public-private key pair, we can trace back each transaction to a registered voter of the application, in case of an audit.
* Given that every transaction that has been recorded on the blockchain has reached consensus on the network and is immutable, using blockchain for voting can help ensure trust between the public and the government. In addition, by using smart contracts to automate the tallying of votes, voting becomes a much more secure and cost-effective process.

## Transparent Voting System | Logistics
* The inventories are filled during elections and a lot planning is made along with numerous arrangements. The biggest problem at times is the non transparency of the whole process for a normal citizen
* Every transaction, arrangement, plan, etc will be uploaded to the blockchain giving everyone the access to true data clearing many doubts arising during the elections.



