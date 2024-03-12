```python
class ReadMe:
    def __init__(self, username="EstherChuCortes", year=2022):
        self.username = username
        self.name = 'Esther Cortés'
        self.education = {
            'programming': ['Developer Front-End'],
            'educations': ['Master Developer Full Stack'],
            'Web Development': ['HTML, CSS, javascript'],
            'Backend Tecnologies': ['Python, Node.js'],
            'database': ['MySQL'],
            'Front-End Frameworks': ['Reat','Vite.js'],
            'control_version': ['GitHub'],
            'editor': ['Visual Studio Code'],
            'social': ['X','@BarrioCort7876'],  
        }

    def doing(self, now=2022):
        today = self.year
        if now == today:
            dream = self.educations['educations']
            return f"I am currently learning {dream[0]} at {dream[1]}."

        elif now > today:
            goal = self.education['programing']
            return f"I am eager to collaborate with {goal[0]} on Development full stack."
                 else:
            return "### Hi there 👋"

   def collaborate(self, role, organization, location):
        self.employment = [role] = [organization, location] 

      me = ReadMe(2022)
           
     
 
