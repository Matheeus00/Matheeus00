
### Hi there, Matheeus00 here 👋

- **From:** Brazil :brazil:
- **Graduated:** Analysis and Systems Development :computer:
- **Job:** Full Stack Developer ☕

#### :raising_hand_man: More about me:
```java
public Skill getSkills() {
    Skill skill = new Skill();

    Code code      = new Code("HTML", "CSS", "Java", "JavaScript", "Python");
    Tools tools    = new Tools("Jenkins", "Gradle", "Maven");
    Language langs = new Language("Portuguese", "English");
    Hobby hobbies  = new Hobby("Hacking", "Reading", "Science");

    skill.setName("Matheus");
    skill.setCode(code);
    skill.setTool(tools);
    skill.setLanguage(langs);
    skill.setHobby(hobbies);
    skill.overviewWrittenByMyself(Boolean.TRUE);
    
    return skill;
}
```
