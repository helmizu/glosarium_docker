# Docker Configuration for Glosarium

# Installation
* Install all depedencies (nginx, docker)
* Execute this command on this Repository
	* `git pull`
	* `git submodule init`
	* `git submodule update`
* Check if Latest Commit Hash are same with the Latest version, if not check **Update** Section of README.md
* Make sure this Folder exists and Empty for the First time
	* mongo_configdb
	* mongo_db
* `docker-compose up -d --build`
* Check if all running well by executing `docker ps -a`
* Make Reverse Proxy with NGINX to Already Configured Port

# Update
* `git submodule update --remote --merge`
* Do All installation beginning on Installation Section on Number 2


