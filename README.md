


## Installation
Run `npm install` command in root folder and backend folder
```
npm install 
```
## How to Run

```
npm run dev 
```




## Establishment
Run 'npm install' command in root organizer and backend envelope
'''
npm introduce
'''
## How to Run

'''
npm run dev
'''


## Extend Usage:


### Settling Confirmation Issues on Enrollment and Login:


- Adjusted the npm server script to guarantee legitimate operation.
- Essential to run the backend locally as the address 'https://mglcoin.io/api/' was inaccessible.
- Empowered Docker arrangement with 'docker-compose.yml' to run MySQL in a holder, encouraging nearby testing.
- Upgraded e-mail arrangement by supplanting an inert e-mail with a unused one arranged for app secret word informing.

### Joining Ethereum Cost on the Profile Page:


- Situated Ethereum cost data at the best of the profile page beneath "Add up to Adjust Cost."
- ETH cost recovered utilizing the existing token cost recovery instrument, utilizing DEXs on chosen systems (Quickswap for Polygon and Pancakeswap for BSC) utilizing WETH token addresses.

### Actualizing Wallet Interface Usefulness on the Profile Page:


- Created a straightforward wallet association usefulness from scratch with Metamask due to reliance clashes and form prerequisites.
- Included a "Wallet Interface" button within the "Outside Wallet" menu to empower association on the off chance that Metamask is introduced.
- Given a detach usefulness that resets the wallet address state variable. In spite of the fact that it doesn't completely disengage as Metamask remains dynamic.

### Perceptions and Potential Changes:


- The extend contains both 'package-lock.json' and 'yarn.lock' records, recommending a choice is required to settle on one bundle supervisor.
- Numerous out of date conditions constrain the capacity to utilize more current libraries.
- A need of code designing devices such as Prettier or ESLint which may offer assistance keep up code cleanliness.
- Proposed presenting robotization utilizing Imposing for commits to actualize quality doors.
- Contrasts in coding styles, outstandingly utilizing async/await versus callbacks, suggest reliable utilize of async/await for way better meaningfulness and maintaining a strategic distance from settled callbacks.
- No fast way to run the backend locally beyond MySQL, which may well be extended to incorporate a full Docker environment.
- Thought for more secure strategies of overseeing cryptographic keys, such as outside administrations like Web3Auth or OpenZeppelin Guard Transfer.

### Recommended Major Changes for Way better Upkeep and Code Quality:


- Utilizing TypeORM or Prisma for database access and pattern administration.
- Moving to TypeScript for moved forward sort administration and code security.
 