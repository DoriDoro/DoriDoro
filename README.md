```python

class DoriDoro:
    """
    Backend-focused Python Developer with strong ownership over
    Django projects, architecture, and data modeling.
    """

    def __init__(self):
        self.username = "DoriDoro"
        self.fullname = "Dorothea Reher"
        self.position = "Python Developer"
        self.company = "DeepOpinion (IFOP Group)"

        self.links = {
            "LinkedIn": "https://www.linkedin.com/in/dorothea-reher/",
            "Blog": "https://dev.to/doridoro",
        }

        self.stack = {
            "backend": ["Python", "Django", "Django REST Framework"],
            "databases": {
                "development": ["SQLite"],
                "production": ["PostgreSQL"],
            },
            "deployment": ["PythonAnywhere", "AWS"],
            "tools": [
                "Git",
                "GitHub",
                "GitHub Actions",
                "Docker",
                "Sentry",
            ],
            "frontend": {
                "experience": ["Bootstrap"],
                "collaboration": ["Vue.js (with frontend developers)"],
            },
            "os": ["Linux", "WSL"],
            "editors": ["PyCharm", "VS Code"],
        }

        self.responsibilities = [
            "Sole backend developer on multiple projects",
            "Designing backend architecture and database schemas",
            "Building and maintaining REST APIs",
            "Translating business and data requirements into Django models",
            "Collaborating with AI-focused teammates and frontend developers",
            "Owning a full backend module within larger projects",
        ]

        self.skills_and_practices = [
            "Strong debugging and problem-solving skills",
            "Performance optimization (select_related, prefetch_related, annotate)",
            "Proposing and justifying technical solutions",
            "Code ownership with iterative review and demo-based feedback",
            "Manual and Django TestCase-based testing (expanding test coverage)",
        ]

        self.preferences = {
            "likes": ["Backend development", "Data modeling", "Clean architecture"],
            "less_likes": ["Heavy frontend work", "JavaScript"],
        }

        self.future = [
            "Growing backend responsibilities as the team scales",
            "Potential mentoring as the team doubles",
            "Improving testing strategy and backend robustness",
        ]

    def __str__(self):
        return f"{self.username} | {self.position} @ {self.company}"


if __name__ == "__main__":
    me = DoriDoro()
    print(me)

```

---

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=DoriDoro&layout=compact&theme=synthwave)

---
