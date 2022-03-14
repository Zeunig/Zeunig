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
        return "💫 Hello, my name is %s, also known as %s 💫\n🔆 I'm from %s and I'm %s, learning : %s.\n👨‍💻 But in 2022, I also want to learn : %s.\n✅ My current projects are : %s\n👋 That's all about me, bye :)"%(self.name,self.nickname,self.country,'a student' if self.amIAStudent == True else 'not a student',self.myProgrammingLanguages_withCommas if self.myProgrammingLanguages_withCommas != None else 'Nothing',self.whatIWantToLearn_withCommas if self.whatIWantToLearn_withCommas != None else 'Nothing',self.myCurrentProjects_withCommas if self.myCurrentProjects_withCommas != None else 'Nothing')

if __name__ == "__main__":
    print(myREADME())

<!--
**Zeunig/Zeunig** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
