```python
class myREADME():
    def __init__(self):
        self.name = "Bence"
        self.nickname = "Zeunig"
        self.country = "Hungary"
        self.myProgrammingLanguages = ['Python','HTML','CSS']
        self.myProgrammingLanguages_withCommas = ", ".join([str(element) for element in self.myProgrammingLanguages])
        self.whatIWantToLearn = ['JavaScript','SQL']
        self.whatIWantToLearn_withCommas = ", ".join([str(element) for element in self.whatIWantToLearn])
        self.amIAStudent = True
        self.myCurrentProjects = ['Reddit bot','Discord Tools (abandoned)']
        self.myCurrentProjects_withCommas = ", ".join([str(element) for element in self.myCurrentProjects])
    def __str__(self):
        return "š« Hello, my name is %s, also known as %s š«\nš I'm from %s and I'm %s, learning : %s.\nšØāš» But in 2022, I also want to learn : %s.\nā My current projects are : %s\nš That's all about me, bye :)"%(self.name,self.nickname,self.country,'a student' if self.amIAStudent == True else 'not a student',self.myProgrammingLanguages_withCommas if self.myProgrammingLanguages_withCommas != None else 'Nothing',self.whatIWantToLearn_withCommas if self.whatIWantToLearn_withCommas != None else 'Nothing',self.myCurrentProjects_withCommas if self.myCurrentProjects_withCommas != None else 'Nothing')

if __name__ == "__main__":
    print(myREADME())
```
