<img width="1012" alt="Screenshot 2023-09-30 at 6 42 21 PM" src="https://github.com/VitaliPri/To-Do-Application/assets/101225909/645ddbd3-5963-4398-b348-eb0a618b2f53">
<img width="1552" alt="Screenshot 2023-05-20 at 5 21 09 PM" src="https://github.com/VitaliPri/To-Do-Application/assets/101225909/9f482296-d2bf-49b3-abc8-783d0306dc60">
<img width="944" alt="Screenshot 2023-05-20 at 3 59 14 PM" src="https://github.com/VitaliPri/To-Do-Application/assets/101225909/a5fc1c79-ff62-455a-89de-4fe99c45a926">


Description:
There are three main entities that are relevant to a todo list app: users, lists, and items. Also defined the attributes for each entity, as well as the relationships between them.

Data model can be used to efficiently store and retrieve data about users, their lists, and the tasks associated with those lists in a todo list app. For example, the schema creates SQL queries that allow to filter, add and delete items in user own list.

Entities:
- Users
- Lists
- Items
  
Attributes:
- Authentication: email, password
- Users list: email, first name, last name
- Lists: list_id, list name, created_at, user_id, items
- Items: item_id, content, status

Relationships:
- Each user can have many lists, but a list can only be associated with one user (one-to-many relationship).
- Each list can contain many tasks, and each task can belong to only one list (one-to-many relationship).
  
Schema:
- Users (user_id, name, email, password)
- Lists (list_id, list name, created_at, user_id, items)
- Items (item_id, content, status).



### PROJECT_PASSWORD ==> Di3qpnYlGJmwDA7w

### ANON_KEY ==> eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6InZ3Z2RoeXhpbnVrY3d3Z2JzcGhxIiwicm9sZSI6ImFub24iLCJpYXQiOjE2ODM1MzM4ODksImV4cCI6MTk5OTEwOTg4OX0.tvxdgt1V1QJuWRL_yJRo4ukhlDzjy0g_046T85txthw

### URL ==> https://vwgdhyxinukcwwgbsphq.supabase.co

### JWT secret ==> 6jNY5AEE3F9ExGAysjku33q6XFr28rxzWRSavLYnJ2THcl1u6/9a2VyV401ZTNybb06YbYqPovIgwVr+9omVrQ==
