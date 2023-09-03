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
            'https://dev.to/doridoro/classed-base-views-cbv-register-login-and-logout-4af1'
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


    def job_offer(
        home_office_condition,
        working_condition,
        location,
        working_language,
        present_days_per_month,
        present_monings_per_week,
        spoken_language
    ):
        offer_job = False
        available = True
    
        # Check if the job meets the remote/full-remote criteria
        if home_office_condition in ['full-remote', 'remote'] and working_language in ['english', 'french']:
            if working_condition in ['full-time', 'part-time', 'CDI'] and location in ['Europe', 'Switzerland']:
                offer_job = True
                available = False
    
        # Check if the job meets the hybrid criteria
        if home_office_condition == 'hybrid' and working_condition in ['full-time', 'part-time', 'CDI']:
            if working_language == 'english':
                if present_days_per_month <= 5:
                    if location in ['Europe', 'Switzerland']:
                        offer_job = True
                        available = False

                elif present_monings_per_week in [
                    'Monday morning', 'Tuesday morning', 'Thurdsay morning', 'Friday moning'
                ]:
                    if location in [
                        'Bruz', 'Rennes', 'Guichen', 'Chartres-de-Bretagne', 'Saint-Jacques-de-la-Lande', 'Laille'
                    ]:
                        offer_job = True
                        available = False
    
            elif working_language == 'french' and spoken_language == 'english':
                offer_job = True
                available = False

            


    return offer_job


if __name__ == '__main__':
    me = DoriDoro()
    print(me)
```

---

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=DoriDoro&layout=compact&theme=synthwave)

---
