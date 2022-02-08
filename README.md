# Decentralized Trading Exchange 

A decentralized exchange with accurate live liquidation features stop-loss sets with collateral borrowing limits sending orders and receiving trades with movements of the candlesticks during trading hours lowest wick represents the 1-minute timeframe.



![Capstone 2](https://user-images.githubusercontent.com/59753390/153061842-22aae074-c6c6-40f9-8edf-6811f2ba850d.gif)


![Capstone Project 1 GIF](https://user-images.githubusercontent.com/59753390/153061903-9bd711f3-076e-4e5f-81d4-074f0ed01416.gif)




![Dapp Excahnge 1](https://user-images.githubusercontent.com/59753390/152915289-a6d14cc3-1115-403e-b4e3-0084ec54046b.png)

Run project from directory

#### Heroku Link: https://dashboard.heroku.com/apps

1.) Heroku Install CLI
$ heroku login

#### Create a new Git repository
Intialize a git repository in a new or exsisting directory

```$ Cd my-proect/```
```$ git init```
```$ heroku git:remote -a Dapp-token-exchange```

#### Deploy your application 
Commit your code to the repository and deploy it to heroku using Git.

```$ git add .```
```$ git commit -am "Send test"```
```$ git push heroku master```

Heroku Git URL: https://git.heroku.com/Your-app-name-here.git 


Heroku CLI Install
# Mac OS
$ brew top heroku/brew && brew install heroku

# Ubuntu +16
$ Sudo snap install --classic heroku

# Windows 
32bit installer: https://devcenter.heroku.com/articles/heroku-cli
64bit installer: https://devcenter.heroku.com/articles/heroku-cli


** UPDATE: If you're having trouble deploying to Heroku, then use this

#### Surge Link:  https://surge.sh/

```run: npm run build```
```run: cd build```
```run: npm i -g surge```
```run: surge```

The update specifies the Node.js version in the package.json file so that Heroku builds your app correctly.

If you want to fix your own app quickly, simply add this to your package.json file:

 ```"engines": {

  "node": "8.11.1"

 },```

Then re-deploy to Heroku!

If you get an error in your browser, simply wait for your app to "wake up", and then refresh the page

