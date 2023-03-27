# [Backstage](https://backstage.io)

This is your newly scaffolded Backstage App, Good Luck!

To start the app, run:

```sh
yarn install
yarn dev
```


History
#1 Installation
Installed nvm (@stable ~19) 

Installed yarn
attempt to create Backstage app (npx): FAIL - yarn works with up to nvm 18

Installed nvm (@18)
attempt to create Backstage app (npx): SUCCESS

:: BACKSTAGE RUNNING WITH IN-MEMORY DATABASE

#2 Adding database

Installed postgres (12) on WSL: 
$ service postgresql start
FAIL: Port already in use

- Stopped local Windows Postgres, resumed to run WSL postgres 
$ service postgresql start
SUCCESSS

:: Created user + changed password + reconfigured app-config.yaml
-- Troubleshooting credentials and permissions
SUCCESS 

#3 Adding Google Identity Provider 
 - Setting up Google as Identity Provider
 :: Troubleshooting error "The Google provider is not configured to support sign-in
 - Added resolver to auth.ts
 :: Troubleshooting error "User not found"
 - Mapping user to 'user:default/guest': FAIL
 - Adding resolver to skip database user lookup: OK

 IdP for 

SUCCESS
	
#4 Adding GitHub IdP
 - Setting up Google as Identity Provider
 - Added resolver to auth.ts

FAIL: No error thrown, but Auth Windows is Blank
