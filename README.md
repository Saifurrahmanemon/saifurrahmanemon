
```python
class Saif:

    def __init__(self):
        self.username = 'saif'
        self.name = 'Saifur Rahman Emon'
        self.code = {
            'frontend': ['HTML', 'CSS', 'JavaScript', 'ReactJS', 'Material UI' 'Boostrap', 'TailWind'],
            'backend': ['Python','Django', 'NodeJS'],
            'database': ['PostgreSQL', 'SQLite3', 'Mongo DB'],
            'devops': ['Docker', 'GitHub Actions', 'Heroku'],
            'tools': ['GIT', 'GitHub'],
            'misc': ['Firebase', 'GNU/Linux']
        }
        self.architecture = ['RESTful API', 'Serverless', 'microservices']

    def __str__(self):
        return self.name


if __name__ == '__main__':
    me = Saif()
