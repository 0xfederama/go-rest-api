# go-rest-api
A repository developed while studying Go REST APIs based on the wonderful work made by Eli Bendersky on his website, specifically on [this blog post](https://eli.thegreenplace.net/2021/rest-servers-in-go-part-1-standard-library/).

While developing this project, I also took the opportunity to learn `curl` to test the API. 

The project emulates a REST API for a task management appliations, supporting these operations:
```
POST   /task/              :  create a task, returns ID
GET    /task/<taskid>      :  returns a single task by ID
GET    /task/              :  returns all tasks
DELETE /task/<taskid>      :  delete a task by ID
GET    /tag/<tagname>      :  returns list of tasks with this tag
GET    /due/<yy>/<mm>/<dd> :  returns list of tasks due by this date
```

