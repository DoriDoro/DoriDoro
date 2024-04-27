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
                'skills': ['Python', 'Django', 'Django REST framework', 'Flask', 'HTMLS5', 'CSS3', 'JavaScript', 'jQuery', 'Vanilla JavaScript', 'Postman', 'Git', 'GitHub', 'GitHub actions', 'Branching', 'Unittest', 'Pytest', 'CLI application', 'SQLite', 'PostgreSQL', 'UML', 'Wireframe', 'User Story', 'ERD', 'Sentry', 'Docker', 'virtuel environment', 'Render'],
            }
        }
        self.portfolio = 'https://portfolio-dorothea-reher-doridoro.vercel.app'
        self.articles = 'https://dev.to/doridoro'
        self.linkedin = 'https://www.linkedin.com/in/dorothea-reher/'
        self.code = {
            'backend': ['Python', 'Django'],
            'database': ['PostgreSQL', 'SQLite3'],
            'operation_system': ['Linux', 'Mac', 'Windows'],
            'deployment': ['Vercel', 'Heroku', 'Render'],
            'frontend': ['HTML', 'CSS', 'JavaScript', 'jQuery', 'Vanilla JavaScript', 'Boostrap'],
            'tools': ['Git', 'GitHub', 'GitHub actions', 'GitLab', 'Pandas', 'Celery', 'Sentry', 'Docker'],
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
