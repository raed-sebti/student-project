# student-project
## docker container run -d --name mysql-instance -P -v /mysql-data:/var/lib/mysql   mysql-instance
#
## docker container run -d -p 4000:4000 --name nodejs-instance  -e MYSQL_USER='root' -e MYSQL_PASSWORD='password' -e MYSQL_DATABASE='test' -e MYSQL_HOST='172.17.0.2' nodejs-instance
#
# Get All students 
##curl -X POST 172.17.0.3:4000/get-students
# Add new student 
## curl --header "Content-Type: application/json" -d '{"rollNo": 1130580, "name": "Raed"}' -X POST localhost:4000/add-studento
