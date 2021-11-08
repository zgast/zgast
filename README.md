```Java
package at.zgast;

class Markus extends Human{
    private String name             = "Markus";
    private String nickName         = "zgast";
    private String age              = "17";
    private String[] languages      = {"Java", "Dart", "C", "TypeScript", "GoLang"};
    private String[] frameworks     = {"Flutter", "Spring", "React"};
    private String[] technologies   = {"Docker", "Linux", "MongoDB", "git" , "nginx"};

    public Markus(Coffee firstCoffee){
        this.drink(firstCoffee);
    }
}
```
