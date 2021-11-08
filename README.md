```Java
package at.markus;

import java.util.Map;

class Markus extends Human{
    private String name                     = "Markus";
    private String nickName                 = "zgast";
    private String age                      = "17";
    private Map<String,String> currentOS    = Map.of("PC",      "Debian11/Gnome",
                                                     "Laptop",  "Ubuntu/DWM");
    private String[] frameworks             = {"Flutter", "Spring", "React"};
    private String[] technologies           = {"Docker", "Linux", "MongoDB", "git" ,"nginx"};

    public Markus(Coffee firstCoffee){
        this.drink(firstCoffee);
    }
}
```
