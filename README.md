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
    location="Seattle, WA",
    languages=["Python"],
    currently_learning=["dataclasses", "tkinter", "testing"],
    recent_projects=["Spotify-Playlist-Retrieval", "Button-Presser-for-Windows"],
    interests=["music", "typewriters", "turn-based RPGs", "anime", "books", "hiking"],
    goals="Junior Python Developer", "Freelance Developer"
)
```

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=QuothTheRaven42&theme=github-dark)
