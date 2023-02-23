# Voting-System
It implements a voting contract. The main problems of electronic voting is how to assign voting rights to the correct persons and how to prevent manipulation. 
Vote counting is automatic and completely transparent at the same time.
The idea is to create one contract per ballot, providing a short name for each option. Then the creator of the contract who serves as chairperson will give the right to vote to each address individually.
The persons behind the addresses can then choose to either vote themselves or to delegate their vote to a person they trust.
At the end, winning proposaln will return the proposal with the largest number of votes.
