In 1 terminal 


docker compose up


in terminal number 2 

docker compose logs -f 

Then 2 stress test 
docker stop miniraft-replica3    
docker start miniraft-replica3  - to restart the terminal do the above 