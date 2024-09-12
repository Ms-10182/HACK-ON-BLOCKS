# Survival for Humanities 
## Inspiration
There are so many disasters happening and victims needs aid ASAP and crowd funding in such situation will help a lot in short time but user engagement is low in doing funding . So I created a website and hosted a interesting game there in which we have to survive and kill monsters, for each monsters we will get 1 token then we can donate these tokens to organization listed in the same website where organization will be hosting crowd funding. Playing an online game for free always seems fascinating to me also when we are getting rewards who don't wanna play this game. In this manner organization will get capital and use it for good of victims affected by disasters like flood, earthquake. Also user will be rewarded for donation<br><br>

## How we built it
We used solidity for smart contract development using remix IDE, testing was done on few networks including sepolia, etherlink, avalanche subnet. with complete testing contract was deployed on etherlink. We used HTML+ CSS + javascript for the front end interaction on VS code and Construct 2 for building of game. After loading of website user will click on connect wallet and his wallet will be connected and list of crowd funding will be refreshed. Then users can play game and interact with the dashboard.<br><br>

## What it does
Overall website is designed to target 3 types of people - players, crowd funding organisation and the owner. when the website launches all users will have same dashboard where first they have to connect their wallet, as soon as wallet is connected the crowd funding list will be refreshed. In the dashboard they will have options to check balance, donate,getTokens. These function are meant to be used by the players to check their token balance, get tokens for the kills they did in the game and donate to donate to the organization they wish. Additional option which are useful for organization to host is Register org to raise a funding, then approve org will approve the pending organization request and this is meant for the owner of the contract.<br><br>

## Challenges we ran into
we faced a lot of challenges such as integration of game with front end, Construct 2 is very old software so we faced a lot of incompatibility issue. we faced a lot of issue in perfectly fetching and data form the smart contract. Another challenges we faced were in local development every time we host the game the download dialogue of game files were bombarded on screen, But it doesn't happen for the users, it is seamless for them. One issue that still persists is E,P and R keys are binded with the game so that doesn't work in text area in that web page, user need to copy and paste, but there is not much to type every this is already meant to be copy pasted.<br><br>

## UI of Game
When game starts, player is deployed with a laser gun, now he has survive till he can, kill the monster and when game is over user will get token equal to the number of kills and then player can donate these tokens to different organization as per their wish. For donation they will get reward. the donation will help the organization to save and provide aid to the victims and this reward system will encourage more users to play that will increase traffic and resulting in more donation. Controls: W,A,S,D for movement. P for pause the game, R for resume the game LMB click or E to shoot. NOTE: P,R and E Keys will not work in text area if you are trying to do so please copy and paste. This bug will be fixed soon.<br><br>

## How to interact
The site is divided into 2 parts:
### 1) Game canvas:
This is the canvas where game will be loaded and user will play.
use W,A,S,D to move and LMB click/tab to shoot. Use mouse to aim.
### 2) DashBoard
It also has 2 parts, 1st one where and organisation will register themselves and owner will approve it. for development purpose public approve is also available.
2nd part where the player will get tokens(equal to the no of kills), check tokens, donate tokens.

<br>
Author<br>
[@Mayank Sharma](https://www.linkedin.com/in/mayank-sharma-078278243/)
