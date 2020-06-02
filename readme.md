### Command Notes
build

`sudo docker build --tag reactapp .`

Run

`sudo docker run --detach --publish 3000:3000 --name bb tests`

this works for apps with crap ( create react app)
`docker run --name crap -d -it -p 8080:3000 reactapp`

Prune 

`docker system prune -a --volumes`