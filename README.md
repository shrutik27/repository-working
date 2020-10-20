# repository-working
 ### login-system:
 create a login system for every user to manage file properly 
##### how to find how many repository they have
 query to find repository
 < var query = select 'repo' where user ='user'>
 //where repo and user re column
 
 ### search-box:
  create a simple form for serach
  ##### how to show only public repository and not private
<var query = select'repo' where type='public'>
  //where repo and type are column
  
 ### unique url for each repository
 to give unique url to each repository we will use dynamic url where url can be 
 
 ##### eg: https:/sitename/username/reponame 
 as each user can create a unique repository name so each username/reponame will be unique
 
 
 ### pull request
user can send pull request which will take file from user and store in database if the admin accept the pull request will be merged or else will be deleted

###  creating readme.md file automatically
will use text box  from where it will take input and create a file reade.md which will be predefined usinf the fs module in node and to display readme.md file will open the file readme.md file using <Github API - Markdown on your javascript.https://github.com/evilstreak/markdown-js.>

### how to make search fatser:
we sill save repository in a table which will have id equal to the id of user
##### eg: id of user is 1 then id of repository is also 1 then query will be var query = select data where id='1'

### clone option:
   button to download file in local system 
