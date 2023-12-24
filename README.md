```python
class ReadMe:
    def __init__(self, username="EstherChuCortes", year=2022):
        self.username = username
        self.name = 'Esther Cortés'
        self.education = {
            'programming': ['Full Stack Software Development blockchain'],
            'educations': ['Master in Blockchain Development and full stack'],
            'my_languages': ['Python,HTML5,CSS3,Javascript,Solidity'],
            'database': ['MySQL'],
            'bookshop': ['Django','Node.js','Reat','Vue.js'],
            'control_version': ['GitHub'],
            'editor': ['Visual Studio Code'],
            'criptocurrency': ['Ethereum'],
            'social': ['Discord','ester6723'],  
        }

    def doing(self, now=2022):
        today = self.year
        if now = today:
            dream = self.education['Blockchain Devolopment and full stack']
            return """
            I am currently learning {code} at {code_academy_ConquerBlock}.
            """.format(code=dream[0], code_academy_ConquerBlock=dream[1])

        elif now > today:
            goal = self.employment['developer']
            return """
            I am eager to collaborate with {teams} on {projects}.
            """.format(teams=goal[0], projects='Blockchain Devolopment and full stack')
        else:
            return """
            ### Hi there 👋
            """
        
    def collaborate(self, role, organization, location):
        opportunity = self.employment
        opportunity[role] = [organization, location]

me = ReadMe(2022)
‘’'’’





