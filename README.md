```python

class DoriDoro:

    def __init__(self):
        self.username = 'DoriDoro'
        self.position = 'Python Django Junior Developer'
        self.webdevelopment_formations = {
            'Ironhack Paris': {
                'period': 'August to October 2019',
                'skills': ['HTML5', 'CSS3', 'JavaScript', 'React', 'Node', 'Postman', 'MangoDB'],
            },
            'OpenClassrooms' : {
                'period': 'November 2022 to present',
                'skills': ['Python', 'Django', 'Django REST framework', 'HTMLS5', 'CSS3', 'JavaScript', 'Postman'],
            }
        }
        self.portfolio = 'https://portfolio-dorothea-reher-doridoro.vercel.app'
        self.articles = [
            'https://dev.to/doridoro/deploy-a-django-app-with-postgresql-database-on-vercel-1965',
            'https://dev.to/doridoro/how-to-first-migrate-custom-user-model-within-models-directory-1bdl',
            'https://dev.to/doridoro/classed-base-views-cbv-register-login-and-logout-4af1',
            'https://dev.to/doridoro/create-a-superuser-in-django-with-custom-user-model-attributes-449o',
            'https://dev.to/doridoro/drf-create-property-decorator-in-view-and-use-property-in-serializer-okm',
            'https://dev.to/doridoro/error-str-returned-non-string-type-user-344n',
            'https://dev.to/doridoro/drf-create-validation-in-serializer-421i',
            'https://dev.to/doridoro/what-problems-can-happen-with-different-serializer-in-drf-5e7m',
            'https://dev.to/doridoro/drf-detailed-information-of-user-in-related-serializer-4nif',
            'https://dev.to/doridoro/several-ways-to-create-a-simple-url-2fhh',
            'https://dev.to/doridoro/django-rest-framework-warning-unorderedobjectlistwarning-1p3p'
        ]
        self.linkedin = 'https://www.linkedin.com/in/dorothea-reher/'
        self.code = {
            'backend': ['Python', 'Django'],
            'database': ['PostgreSQL', 'SQLite3'],
            'operation_system': ['Linux', 'Mac', 'Windows'],
            'deployment': ['Vercel', 'Heroku'],
            'frontend': ['HTML', 'CSS', 'JavaScript', 'Boostrap'],
            'tools': ['GIT', 'GitHub', 'GitLab', 'Pandas', 'Celery'],
            'IDE': ['PyCharm', 'VSCode', 'Sublime Text']
        }
        self.private = [
            'dogs', 'horses', 'yoga', 'handicrafts', 'learning', 'coding', 'walking', 'biking', 'movies'
        ]
        self.characteristics = [
            'calm', 'quiet', 'easily bored', 'diligent', 'quick learner', 'really sensitive', 'reliable'
        ]
        self.interests = ['growing', 'understanding' 'compassion', 'psychologie', 'health']


    def __str__(self):
        return f'{self.username} | {self.position}'


if __name__ == '__main__':
    me = DoriDoro()
    print(me)
```

---

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=DoriDoro&layout=compact&theme=synthwave)

---
