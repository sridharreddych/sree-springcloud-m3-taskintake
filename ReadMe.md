Invoking a Task through via http and spring cloud

using both project sree-springcloud-m3-tasksink and sree-springcloud-m3-taskintake and sree-springcloud-m3-task as jar

the movement m3-tasksink is run you see an entry in rabbitmq

the movement m3-taskintake is run you see the it will consume from rabbitmq and save to database."# sridharreddychsree-springcloud-m3-tasksink"

post this localhost:8082/tasks
with body

station101,BINDAS100,2020-03-12T07:44:22
station101,BINDAS100,2020-03-12T07:44:22
station101,BINDAS100,2020-03-12T07:44:22

and you see entries in database
"# sree-springcloud-m3-taskintake" 
