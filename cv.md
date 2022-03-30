# Ivan Didichenko
### Junior backend developer and blockchain enthusiast
---
### Contact Information
- [Telegram - @virginonline](t.me/virginonline)
- Email - anipeptun@yahoo.com 
- Discord - ////#9041 
---

### About me
---
I like programming and blockchain tech, i want to be fullstack blockchain developer and develop the web3 industry<br>
---
### Skills:
---
```java
public class virginonline extends GitHubUser {
    
    public virginonline(){
        super("Ivan", "Krasnoyarsk");
        this.addLanguages("Java","C#","Solidity","JavaScript Basic", "SQL");
        this.addTools("Vim", "VS Code", "Visual Studio","IntelliJ IDEA", "Git");
    }
}
public abstract GitHubUser{
    @Getter private final String name;
    @Getter private final String city;
    
    private final Set<String> languages = new HashSet<>();
    private final Set<String> tools = new HashSet<>();

    public GitHubUser(String name, String city){
        this.name = name;
        this.city = city;
    }
    public void addLanguages(String ... language){
        this.languages.addAll(language);
    }
    public void addTools(String ... tool){
        this.tools.addAll(tool);
    }
}
```
---

### Languages
- Russian \- Native
- English \- B2
- Chinese \- B2