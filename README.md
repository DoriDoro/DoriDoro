```python

class DoriDoro:

    def __init__(self):
        self.username = 'DoriDoro'
        self.position = 'Python/Django Developer'
        self.portfolio = 'https://www.dorothea-reher.com/en/'
        self.blog = 'https://dev.to/doridoro'
        self.linkedin = 'https://www.linkedin.com/in/dorothea-reher/'
        self.code = {
            'backend': ['Python', 'Django'],
            'database': ['PostgreSQL', 'SQLite3'],
            'operation_system': 'Linux',
            'deployment': ['Vercel', 'Heroku', 'Render'],
            'tools': ['Git', 'GitHub', 'GitHub actions', 'Sentry', 'Docker'],
            'IDE': 'PyCharm',
        }

    def __str__(self):
        return f'{self.username} | {self.position}'


if __name__ == '__main__':
    me = DoriDoro()
    print(me)
```

---

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=DoriDoro&layout=compact&theme=synthwave)

---
