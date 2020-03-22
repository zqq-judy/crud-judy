# crud-judy


Todo list
<br>
使用node框架，构建一个Restful API，能够完成Todo list的以下功能。<br>
-返回所有Todo任务<br>
-创建一个新的Todo任务<br>
-返回一个指定ID的Todo任务<br>
-删除一个Todo任务<br>
为简化流程，不引入数据存储，即，不需要做数据持久化，可以在服务器运行时满足功能即可。<br>

<br>
Todo中一个任务的JSON格式定义为：<br>
  {                                           <br>
    "id": 1,                                  <br>
    "content": "Restful API homework",        <br>
    "createdTime": "2019-05-15T00:00:00Z"     <br>
  }                                            <br>
  <br>
进一步的功能提示：需完成的四个功能的Restful API定义如下，实现即可。<br>
GET /api/tasks/                               <br>
POST /api/tasks/                              <br>
GET /api/tasks/{id}                           <br>
DELETE /api/tasks/{id}                        <br>
