# hello-world
practicing the GitHub Flow


## About Me

```python
class AboutMe:
    def __init__(self):
        self.name = "Anisha"
        self.role = "pursing Master in Data Science"
        self.interests = ["Music ", "Travel", "Series"]
        self.skills = ["Power Bi", "Programming"]
        self.location = "Dublin"

    def introduce(self):
        return f"Hello! I'm {self.name}, a {self.role} based in {self.location}. My interests include {', '.join(self.interests)}."

    def show_skills(self):
        return f"I have skills in: {', '.join(self.skills)}."
    
    def __str__(self):
        return self.introduce() + "\n" + self.show_skills()

# Create an instance of AboutMe
me = AboutMe()
print(me)

