# kanban-gateway

Change express-gateway to krakend gateway

<h2>About the project:</h2>
<p>The main reasons to replace express-gateway in project was: </p>

1. Express-gateway last version was released with an apparently break in the configuration turning maintenance of the config very hard sometimes. 
2. A native support(according to my researches it doesnt work in the version 2.0 of influxdb so this part was useless to me) to influxdb metrics. Express gateway has its own influxdb plugin but it seemed a little bit more confuse to deal with plugins than krakend. 
3. Performance, apparently the performance benchmarks of krakend are impressive and able to tame even the Kong and Tyk gateways. 
4. Curiosity to try a new tool that seemed to fit better with my necessities.

<h2>Initializing the project</h2>
<p>Start docker and run the following command in your terminal</p>

```
"docker-compose up -d"
```

<p>To acess the application</p>

```
"http://localhost:9091/"
/boards
/tasks
/comments
```

[Link to access the mini-kanban repository](https://github.com/KevinDaSilvaS/Mini-Kanban "mini-kanban repository")
###
[Link to access the comments-kanban repository](https://github.com/KevinDaSilvaS/comments-kanban "comments-kanban repository")
###
[Link to access the old kanban-api-gateway repository](https://github.com/KevinDaSilvaS/kanban-api-gateway "kanban-api-gateway repository")
