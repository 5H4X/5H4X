```java

import galaxy.earth.shadow;
public class Shadow{

    static void languages(){
        String languages = {"Java","TypeScript","C++","Python"};
        for(byte control = 0; control <= languages.length; control++){
            System.out.println("I code in :" + languages[0]);
        }
    }
    static void frameworks(){
        String frameworks = {"Next.JS","Arduino","Express.JS","Pytorch","Android"};
        for(byte control = 0; control <= frameworks.length; control++){
            System.out.println("I write in " + frameworks[0] + " framework");
        }
    }
    static void about(){
        String goals = {"Open Source", "DedSquad"};
        for(byte control = 0; control <= goals.length; control++){
            System.out.println("Writing code for" + goals[0]);
        }
    }
    static void main(String args[]){
       Shadow dark = new Shadow();
       dark.languages();
       dark.frameworks();
       dark.about();
    }
}
```
