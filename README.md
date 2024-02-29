```python
class ReadMe:
    def __init__(self, username="EstherChuCortes", year=2022):
        self.username = username
        self.name = 'Esther Cortés'
        self.education = {
            'programming': ['Developer Full Stack'],
            'educations': ['Master Developer Full Stack'],
            'Web Development': ['HTML, CSS, javascript'],
            'Backend Tecnologies': ['Python, Node.js'],
            'database': ['MySQL'],
            'Front-End Frameworks': ['Reat','Vue.js'],
            'control_version': ['GitHub'],
            'editor': ['Visual Studio Code'],
            'social': ['X','@BarrioCort7876'],  
        }

    def doing(self, now=2022):
        today = self.year
        if now = today:
            dream = self.education['Devolopment full stack']
            return """
            I am currently learning {code} at {code_academy_ConquerBlock}.
            """.format(code=dream[0], code_academy_ConquerBlock=dream[1])

        elif now > today:
            goal = self.employment['developer']
            return """
            I am eager to collaborate with {teams} on {projects}.
            """.format(teams=goal[0], projects='Devolopment full stack')
        else:
            return """
            ### Hi there 👋
            """
        
    def collaborate(self, role, organization, location):
        opportunity = self.employment
        opportunity[role] = [organization, location]

me = ReadMe(2022)
‘’'’’





