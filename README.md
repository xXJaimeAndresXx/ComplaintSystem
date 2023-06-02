# Complaint System
## A Python-AWS Project
![AWS](https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)

![License](https://img.shields.io/github/license/xXJAimeAndresXx/ComplaintSystem)
## Installation

Complaint System requires [Python](https://www.python.org/) v3.11.3 to run.

Install the dependencies and devDependencies and start the server.

```sh
$ python -m venv c:\path\to\myenv
$ venv\Scripts\activate.bat
$ pip install -r requirements.txt
$ uvicorn main:app
```
Database used: PostgreSQL
If you dont have the database created you can run this script inside your project folder
```sh
$ alembic upgrade head
```
In case you dont have an admin user already on your database, this command could be useful.
replace {...} with the desired data of the user
```sh
$ python commands/create_super_user.py -f {Test} -l {Admin} -e {admin@admin.com} -p {1234} 
-i {ES9121000418450200051332} -pa {1234}
```



## License

MIT

**Free Software, Hell Yeah!**