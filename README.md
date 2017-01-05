## Single Page App Quiz

- Implement a simple "Todo" webapp
- You can use every js framework such as angular / react / vue.js ... etc.
- Webapp have 2 pages
	- Todo ( Main App )
	- Setting ( Simple static page )
- Connect API

```
API Info
http://45.32.114.176:4600/
GET			/todos		# Get all todos list
POST		/todos		# Add new todo
DELETE		/todos/:id	# Delete a todo by id
```

## POST /todos

Body params:

```json
{
  "todo": "some string"
}
```

- Styling webapp similar this design

![http://tui2tone.github.io/mean-todo-quiz/todowebapp.gif](http://tui2tone.github.io/mean-todo-quiz/todowebapp.gif)

### CANNOT
* You CANNOT use any css framework. 
