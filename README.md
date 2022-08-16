# env_variable

### Linux variable & Env variable in Linux - Windows - Mac

- How to check existing Env Var `env` or `printenv`
- How to create a var in Linux `Name=Fatima`
- How to check Linux Var `echo $Name`
- Env var we have a key word caled `export` command is `export Last_Name=Barkat`
- Check specific Env var `printenv Last_name` - outcome should be 'Barkat' 

##### How to make Env variable `PERSISTENT`
- research how to make env persistent of your first_name, last_name and DB_HOST=mongodb://192.168.56.151:27017/posts

##### steps:
- edit the .bashrc file:
- Write a line for each variable you wish to add using the following syntax: `export Name='', export Last_Name='', export DB_HOST=''` and ctrl x then y to save.
- Next enter the following command `source .bashrc`
- Result
<img width="374" alt="Screenshot 2022-08-16 at 12 16 02" src="https://user-images.githubusercontent.com/69306840/184867757-0e07a5b7-ceff-484a-915f-a36eb77b9e1f.png">

