
This is very simple NGINX website that allows a user to send a tweet. 


Steps to use it:

Build it:
`docker build -t any_name_for_app:tag .`

Run it:
`docker container run --detach -p 8082:8082 any_name_for_app:tag`
