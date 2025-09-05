# Task Master

**Task Master** is a simple web-based task management application built with **Flask**. It allows users to **add, update, and delete tasks** with a clean and minimal interface.

---

## Features

- Add new tasks
- Update existing tasks
- Delete tasks
- Tasks are displayed with their creation date
- Simple, responsive UI

---

## Technologies Used

- **Python**  
- **Flask**  
- **SQLAlchemy** (SQLite database)  
- **HTML / CSS**  
- **Jinja2** templates  

---

## Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/task-master.git
cd task-master


## How To Run
1. Install `virtualenv`:
```
$ pip install virtualenv
```

2. Open a terminal in the project root directory and run:
```
$ virtualenv env
```

3. Then run the command:
```
$ .\env\Scripts\activate
```

4. Then install the dependencies:
```
$ (env) pip install -r requirements.txt
```

5. Finally start the web server:
```
$ (env) python app.py
```

This server will start on port 5000 by default. You can change this in `app.py` by changing the following line to this:

```python
if __name__ == "__main__":
    app.run(debug=True, port=<desired port>)
```