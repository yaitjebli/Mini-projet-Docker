# Mini-projet-Docker


En cours de rédaction


![image](https://user-images.githubusercontent.com/72947514/228953442-8a6146be-1004-4ef4-8ec1-d3a6d6d769aa.png)

sudo docker network create pozosnet

sudo docker run -d --name pozosapi --network pozosnet -v ${PWD}/student_age.json:/data/student_age.json -p 4000:5000 apipozos:v1
![image](https://user-images.githubusercontent.com/72947514/228953278-a033d2de-5b51-4990-b1f1-14fe7a0bb3aa.png)


curl -u toto:python -X GET http://127.0.0.1:4000/pozos/api/v1.0/get_student_ages

![image](https://user-images.githubusercontent.com/72947514/228953082-78dbf5ee-0b53-4d7b-b5b4-f1f706fc87e0.png)
