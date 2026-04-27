```python
```python
from dataclasses import dataclass

@dataclass
class Developer:
    name: str
    location: str
    languages: list[str]
    currently_learning: list[str]
    projects: list[str]
    interests: list[str]
    goal: str

me = Developer(
    name="David",
    location="Bremerton, WA",
    languages=["Python"],
    currently_learning=["APIs", "OOP", "testing"],
    projects=["Spotify Playlist Tool", "Markov Chain Poetry Generator"],
    interests=["music", "poetry", "typewriters", "RPGs", "anime"],
    goal="Junior Python Developer",
)
```

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=QuothTheRaven42&theme=github-dark)
