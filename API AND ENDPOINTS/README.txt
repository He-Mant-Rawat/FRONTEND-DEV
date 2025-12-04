Assignment 10 - Solutions (Quick start)
Each question has its own folder with an index.html and db.json. JSON Server should be run on different ports as below (examples):

Q1 Live Search      -> folder Q1_live_search     (db.json)  -> run: json-server --watch db.json --port 3001
Q2 Employees        -> folder Q2_employee_dashboard (db.json) -> run: json-server --watch db.json --port 3002
Q3 Tasks            -> folder Q3_task_manager    (db.json)  -> run: json-server --watch db.json --port 3003
Q4 Multi APIs       -> folder Q4_multi_api_dashboard has 3 files:
                      db_users.json (port 3004)
                      db_orders.json (port 3005)
                      db_products.json (port 3006)
Q5 Timetable        -> folder Q5_timetable_viewer (db.json) -> run: json-server --watch db.json --port 3007
Q6 Registration     -> folder Q6_registration    (db.json)  -> run: json-server --watch db.json --port 3008

Open the index.html in each folder in your browser after starting the corresponding JSON Server.
Ports used in HTML/JS are the ones shown above. Adjust if you prefer other ports.
