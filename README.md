# Unchained

## The Problem(s)
There are multiple aspects to a successful political election, yet it remains plagued with issues and inconveniences that could be greatly mitigated with the modern outreach of technology and information. Two of the greatest problems that come to mind are the problems people face procuring a voter ID when of age, and vote tampering, both of which are massive problems to a democracy, especially the size of India. Multiple people we personally know have either applied for a voter ID and haven’t received it to date, or had their name missing from the final electoral list. The issue of miscount and tampered votes comes up every year, especially in smaller towns and villages, and we feel with the advent of decentralized peer-peer networks and secure transactions using blockchain that we have today, they can be solved to a great extent.

## The Solution
The solution must start by radically changing how we keep records. When a person is born, along with a compulsory birth certificate, we should maintain a decentralised blockchain network with the person’s name, date of birth and birth certificate registration number.
This blockchain shall be a legitimate reference chain for all verification purposes.
On the day of elections, any person who is of age can go to a voting booth and enter their Birth Certificate number and the system verifies with a block on the chain to ensure that he/she is of age to vote. If they are of age, it also verifies with another secure conventional database to make sure they don’t have any criminal history or mental illnesses.
This way we can make sure people don’t lose out on their vote and voice due to lack of a document that got delayed or lost in the process.

Traditional EVMs are prone to electronic malfunctions and are not flexible enough for quick repairs. This leads to delay in the election process which is undesirable. To solve this issue we propose a new kind of EVM called the OEVM (Online Electronic Voting Machines) that is fully decentralized and is thus very secure. It will also be flexible and have an inbuilt fault detection system with the help of other OEVMs in the network which will not only not help detect failures instantly but will also share the load equally to other nodes (OEVMs) which allow the process to go on smoothly without delay and also notify everyone enabling a faster fix.

Each OEVM in a particular constituency is connected to each other via a decentralized network. These will act as child nodes connected to a central ledger. The ledgers of each constituency can be used to monitor each other in a similar but slightly hierarchical decentralized system. This will not only help prevent hacking accusations of a central server (since there is none) and will also help in repeated counting and demarcation of the number of votes in a constituency.

### How it works and what it does 
- A new block is mined in the nation-wide blockchain with the voter details, and the party they are voting for. Due to the decentralisation, the chain exists all over the country and is secure from any tampering to change votes, or remove records. There is a count of each party’s votes, not nationally, but for each constituency so we know the winner of the constituency immediately with accuracy, which in turn speeds up the process of nationwide constituency count.

- If a person is going to be out of his constituency on the day of elections, he can notify officials prior to the event digitally through a form online, or maybe submit an application to the nearest Electoral Office, whichever is convenient, and the vote will be counted against his local voting area, allowing people to vote away from home.

- Considering the above process requires digital machines, we can also show all the contestants and their promises on screen at the time of voting, in any language of choice, so that it is explained clearly to the voter and gives him a more educated outlook to his decision.

- The user’s profile information will be stored on a node in the blockchain and thus can not be altered with. It allows the user to cast a safe an anonymous vote from the safety of their own home. Furthermore since the node will be anonymous the security of the internet connection does not come into play which could serve as an added bonus to users with slow or easily compromisable Internet connections as is the case with many voters residing in rural areas.	

	
## The Implementation
- The idea will be implemented using Microsoft’s Azure Blockchain service as the cloud computing platform. 

- We will make a web application with a user friendly interface to take into account different age groups and familiarity with technology.

- In the application there will be a feature to show live updates such as election day countdown, live poll results of each constituency and each party and candidate individually. Since the number of votes is calculated by the blocks instantly it will also be displayed there is no chance of misinformation of results and will also lead to expedite vote counting.

- An option to link with the voter’s Aadhar card can be provided for further verification of Date of Birth and Address of the Voter.

- The application can also be used to create a graphical depiction of the contestants of a constituency, their deliverables, criminal record etc. to help the voters further make a well informed decision.

## The Tools

### Datasets 
- List of constituencies and contestants
- Citizen registry and birth dates

### Technologies
- Azure Blockchain
- React.js (Javascript framework for front-end development)
- Node.js (Javascript framework for back-end development)

## The Outcome
Voters can procure their voter’s ID immediately after they turn 18 years old. This will not only save the hassle of the process of physically visiting the polling offices but also since the Voter ID has been registered in a particular constituency, it will automatically appear on the Voter’s list at the time of elections. The transparency of this process equipped with the ease of online access is sure to increase turnout at constituencies across the nation by a large extent and make the election procedure the truly democratic process it should be.


