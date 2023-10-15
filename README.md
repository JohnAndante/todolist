# todolist

Curso gratuito de java oferecido pela Rocketseat, feito entre os dias 9 e 14 de outubro de 2023.

O projeto se trata de uma API de uma tasklist, onde o usuário pode se cadastrar, e cadastrar ou alterar suas tarefas.

Algumas das tecnologias e recursos utilizados foram Java, SpringBoot, H2Database, Lombok, entre outros.

A API está disponível no endereço https://todolist-rocket-818n.onrender.com/

## HTTP Requests

### Create User

> POST https://todolist-rocket-818n.onrender.com/users/

```
{
    "name": "John Doe Lorem",
    "username": "johndoe",
    "password": "123456"
}
```


### Create Task

> POST https://todolist-rocket-818n.onrender.com/tasks/

```
{
    "description": "Task to edit the todolist repository",
    "title": "Todolist - Java",
    "priority": "HIGH",
    "startAt": "2023-10-20T08:00:00",
    "endAt": "2023-10-21T12:00:00"
}

```

### Update Task

> PUT https://todolist-rocket-818n.onrender.com/tasks/{id}

```
{
    "title": "Todolist - Java & RocketSeat"
}

```

### Get Tasks List

> GET https://todolist-rocket-818n.onrender.com/tasks/
