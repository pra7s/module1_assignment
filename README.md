# module1_assignment
Data Engineering Zoocamp Module 1 Assignment 

# Question 1

docker run -it /
--rm /
--entrypoint=bash / 
python:3.13

# In bash
pip -V
# pip 25.3 from /usr/local/lib/python3.13/site-packages/pip (python 3.13)

# Question 2

Answer : db:5432

Because both pgAdmin and Postgres run inside the same Docker Compose network, pgAdmin connects using the service name (db) and the internal Postgres port (5432), not the host-mapped port (5433).

# Question 3