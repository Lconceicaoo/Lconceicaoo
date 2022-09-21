### Hi 👋, I'm Leonardo Sousa!


[![Linkedin Badge](https://img.shields.io/static/v1?message=LeonardoSousa&logo=linkedin&labelColor=1182c3&color=1182c3&logoColor=white&label=%20)](https://www.linkedin.com/in/leonardo-sousa-69953217b/)



```python
class Leonardo:

   def __init__(self):
       self.name = 'Leonardo Sousa'
       self.years = '21'
       self.web = 'https://www.linkedin.com/in/leonardo-sousa-69953217b/'
       self.study= 'Information systems'
       self.code = {           
           'backend': ['Python','Java'],
           'database': ['MSSQL', 'PostgreSQL', 'MySQL', 'SQLite3'],
           'tools': ['GIT', 'GitHub'],         
       }
       

   def __str__(self):
       return self.name


if __name__ == '__main__':
   me = Leonardo()
