```python
class myREADME():
    def __init__(self):
        self.name = "Bence"
        self.nickname = "Zeunig"
        self.country = "Hungary"
        self.myProgrammingLanguages = ['Python','Rust','JavaScript']
        self.myProgrammingLanguages_withCommas = ", ".join([str(element) for element in self.myProgrammingLanguages])
        self.whatIWantToLearn = ['Rust']
        self.whatIWantToLearn_withCommas = ", ".join([str(element) for element in self.whatIWantToLearn])
        self.amIAStudent = True
        self.myCurrentProjects = ['LoL client','Discord token gen']
        self.myCurrentProjects_withCommas = ", ".join([str(element) for element in self.myCurrentProjects])
    def __str__(self):
        return "💫 Hello, my name is %s, also known as %s 💫\n🔆 I'm from %s and I'm %s, learning : %s.\n👨‍💻 But in 2023, I also want to learn : %s.\n✅ My current projects are : %s\n👋 That's all about me, bye :)"%(self.name,self.nickname,self.country,'a student' if self.amIAStudent == True else 'not a student',self.myProgrammingLanguages_withCommas if self.myProgrammingLanguages_withCommas != None else 'Nothing',self.whatIWantToLearn_withCommas if self.whatIWantToLearn_withCommas != None else 'Nothing',self.myCurrentProjects_withCommas if self.myCurrentProjects_withCommas != None else 'Nothing')

if __name__ == "__main__":
    print(myREADME())
```
