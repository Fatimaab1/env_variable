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

### Nginx as reverse proxy
- Firstly ensure you are inside your vm. 
- Once inside run the following commands:
- `sudo nano /etc/nginx/sites-available/default`- 
- The file will then open for editing
- Within the server block you will find `location/` block, in here you need to replace the content inide with `proxy_pass http://localhost:8080;` 
- Now save changes made using ctrl x and then y
- To ensure syntax is correct run `sudo nginx -t` 
- If there were no errors after running the above command you need to run sudo `systemctl restart nginx` to restart nginx
- Then run npm start and you should see this message 'Your app is ready and listening on port 3000'
- Go to your browser and your app should be running 


