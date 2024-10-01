```python

from real-life.task import sleep
from real-life.task import code
from real-life.task import eat

class People:
    def __init__(self, name, telegram,
                 age, skills, friends):
        self.name = name
        self.age = age
        self.skills = skills
        self.friends = friends
    def run(self):
        while True:
            sleep(120)
            code(86160)
            eat(120)
            if 1 == 2: break

me = People("Azamat", "@dom_4k", 15,
            ["sleep", "code", "eat"],
            ["@f15999", "notag", "@heshyn1"])
me.run()

```
