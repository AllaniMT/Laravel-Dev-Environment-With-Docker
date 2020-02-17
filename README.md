# Laravel-Dev-Environment-With-Docker
Setting-up the necessary Services (Nginx, MySQL database, PHP and Node)

For running the application, please make sure to: 

* install the "Node package manager" in the right folder (In our Case, in the "Code" folder): 
<pre>npm install</pre>

* install the "Yarn package manager" int the right folder (In our Case, in the "Code" folder):
<pre>yarn install</pre>


###### To start running  all containers in the background and leaves them running (in the folder "Larvel-Dev-Environment-With-Docker")
<pre>docker-compose up -d </pre>

###### For Exemple, if we  want to run "Brwosersync" from the service "node"
<pre>docker-compose exec node yarn watch</pre>
