```
class DoriDoro:

    def __init__(self):
        self.username = 'DoriDoro'
        self.position = 'Python Django Developer'
        self.webdevelopment_formations = {
            'Ironhack Paris': {
                'period': 'August to October2019',
                'skills': ['HTML5', 'CSS3', 'JavaScript', 'React', 'Node'],
            },
            'OpenClassrooms' : {
                'period': 'November 2022 to present',
                'skills': ['Python', 'Django', 'HTMLS5', 'CSS3', 'JavaScript'],
            }
        }
        self.portfolio = 'https://portfolio-dorothea-reher-doridoro.vercel.app'
        self.linkedin = 'https://www.linkedin.com/in/dorothea-reher/'
        self.code = {
            'backend': ['Python', 'Django', 'Flask', 'Node'],
            'database': ['PostgreSQL', 'MySQL', 'SQLite3', 'Mongo DB'],
            'operation_system': ['Linux', 'Mac', 'Windows'],
            'deployment': ['Vercel', 'Heroku'],
            'frontend': ['HTML', 'CSS', 'JavaScript', 'ReactJS', 'Boostrap', 'Bulma'],
            'tools': ['GIT', 'GitHub', 'GitLab', 'Pandas', 'Celery'],
            'IDE': ['PyCharm', 'VSCode', 'Sublime Text']
        }
        self.private = ['dogs', 'horses', 'yoga', 'handicrafts', 'learning', 'coding', 'walking', 'biking', 'movies']
        self.characteristics = ['calm', 'quiet', 'shy', 'easily bored', 'diligent', 'quick learner', 'really sensitive', 'reliable']
        self.interests = ['growing', 'understanding' 'compassion', 'psychologie', 'health']

    def __str__(self):
        return f'{self.username} | {self.position}'

    def job_offer(home_office_condition, working_condition, working_language):
        offer_job = False

        if home_office_condition == 'full-remote' and working_conditon == 'english':
            offer_job = True
            break

        elif working_condition in ['full-time', 'part-time']:
            if home_office_condition == 'full-remote':
                offer_job = True
                break


if __name__ == '__main__':
    me = DoriDoro()
    print(me)
```

---

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=DoriDoro&layout=compact&theme=synthwave)

---
