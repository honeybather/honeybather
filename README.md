- 👋 Hi, I’m @honeybather
- 👀 I’m interested in web development.
- 🌱 I’m currently learning advanced JavaScript and Flask.
- 💞️ I’m looking to collaborate on exciting web projects.
- 😄 Pronouns: She/Her
- ⚡ Fun fact: I enjoy long biking adventures and training Muay Thai.
      

<a href="https://www.linkedin.com/in/ritagalkov/" target="_blank">
  <img src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExdGJxYWl6ejVvNXhyOHBwdWhhdDkwOHlyamF0cjg2NDByemtzc3hvNiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/3o6gE51uXycrKW6D84/giphy.gif" alt="Fun GIF" width="200"/>
</a>


## About Me

```python
class Profile:
    def __init__(self, name, description, languages):
        self.name = name
        self.description = description
        self.languages = languages
    
    def __str__(self):
        return f"Name: {self.name}\nDescription: {self.description}\nLanguages: {', '.join(self.languages)}"

    def add_language(self, language):
        if language not in self.languages:
            self.languages.append(language)
    
    def update_description(self, new_description):
        self.description = new_description

# Creating an instance with my information
my_profile = Profile(
    name="Rita Galkov",
    description="Student at Hackbright Academy exploring new opportunities in software engineering.",
    languages=["Python", "JavaScript", "Flask"]
)

# Print profile details
print(my_profile)

# Adding a new language
my_profile.add_language("Java")

# Updating description
my_profile.update_description("Software engineer with a focus on web development and a passion for learning.")

# Print updated profile details
print("\nUpdated Profile:")
print(my_profile)
