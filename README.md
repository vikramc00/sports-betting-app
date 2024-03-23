# Sports Betting App

## Description
Contains frontend and login for the sports betting app created using React Native and Firebase.

Technologies: Figma, React Native, JavaScript, Java, MySQL, Firebase, React-Native, Metamask, Solidity, sportsDB API

Frontend features: sign-in, account status, betting page, add friends, popular sports games, shop

  
## Objectives
- Allow users to communally place bets and receive payouts based on real-time results.
- Smart contract system to automate the general betting process, ensure secure and efficient transactions.


## Backend: 
- Constructor: initialize contract function
- startGame: caculate total amounts bet on each team
- joinGame (team#, amount): add to address to player mapping, add money to contact pool
- endGame: calculate payouts, iterate through mapping for winning team + calculate payouts
- payout: linked to API (calls- axios, express)
  

## Installation

Make sure you have node package manager installed and run npm install to get all dependencies.

```bash
npm install
```

## Usage

Run the web app(Requires a browser)
```bash
cd frontend
npm run web
```
