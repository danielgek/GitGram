[![wercker status](https://app.wercker.com/status/5f5956c77be09889ad43e1193b20f60f/s/master "wercker status")](https://app.wercker.com/project/byKey/5f5956c77be09889ad43e1193b20f60f)
# GitGram - Open-source app to follow/discover github repositories

Hi! We are GitGram, a team for @shiftappens working on a open-source solution to follow and discover your favorite github repositories. This app aims to revolutionize the way you spend your waiting times. Let's not waste our time, let's learn with it.

## Development setup 
For the app development process we'll use react-native.

### 1) Clone repository

    $ git clone git@github.com

or using HTTPS:

    $ git clone https://github.com
    
### 2) Install dependencies - Frontend/Node
  Run:
  
    $ npm install
    
or using Yarn:

    $ yarn 

### 3) Init react-native console
  Run:
  
     $ npm run start
     
or using Yarn:

     $ yarn start

### 3) Install app on Android
  Run:
  
    $ npm run android
    
 or using Yarn:

    $ yarn android

### 4) Install app on iOS
  Run:
  
    $ npm run ios
    
 or using Yarn:

    $ yarn ios


## Development

### Git flow

New branches must be created from the most recent `master` with the following convention `GitGram-XXX` where `XXX` is the matching github project card number.

Commits must follow this structure `GitGram-XXX: description of what was done in this commit`.

After merging PRs, delete merged branch.

### Git commands

`cd GitGram`

`git checkout master`

`git pull`

`git checkout -b GitGram-XXX`

`git add <file>` OR `git add -A`

`git commit -m "GitGram-XXX: description of what was done in this commit"`

`git push -u origin GitGram-XXX`

  
## Testing 

We are using [Jest](https://facebook.github.io/jest/) for JS Unit Tests.
  Run tests:
  
      $ npm run test 
      
  or using Yarn:

      $ yarn test


### Javascript

For Javascript we are using tool named [ESLint](http://eslint.org/) with AirBnb conventions.

To use it, run the following command in project root:

 Run tests:

    $ npm run lint 
    
 or using Yarn:

    $ yarn lint


## Team
* Daniel Leal
* Francisco Magalhães
* João Godinho
* Rui Fonseca
