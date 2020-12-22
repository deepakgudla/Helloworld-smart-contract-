# Helloworld-smart-contract-
This is a basic smart contract written in solidity using truffle
 This repository is done using WSL on windows 10 of  vUbuntu 20.04.1 LTS (GNU/Linux 4.4.0-19041-Microsoft x86_64)
 ### 
 
 0..to create a truffle project we need to install a npm package for truffle, => cmd - (npm install -g truffle) in wsl [you can also use powershell]
 
 1. to start project = truffle init 
 
 2. to create contract = truffle create contract <contract name >  {Helloworld in this case}
  
 3. write your code using vim or your preferred editor ( used vs code via wsl ) cmd to go to vs code through WSL is (code .)
 
 4. to create migration file = truffle create migration < contract name >  ( a numbered migration file will be created )
 
 5. copy the 1_initial_migration.js file and paste in the starting ine of the numbered migration......
 
 6. to build contract =  truffle compile 
                          ( after typing this command a local port will appear which says at which port the truuffle project has started
                            and also there will be account keys and private keys
                            in addition to the key a mnemonic will appear which is private to you ## DO NOT SHARE THIS INFO WITH ANYONE## )

7. now type migrate and the contract will be deployed showing the info related to the contract

8. to check your contract has successfully built type your contract name 
                                              info will be displayed regarding your smart contract such as bytecode ( in hash ) etc....
                                              
                                            ##### THANK YOU #####
