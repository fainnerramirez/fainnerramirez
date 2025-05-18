
# Hey! que tal <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Telegram-Animated-Emojis/main/Smileys/Smiling%20Face%20With%20Sunglasses.webp" alt="Smiling Face With Sunglasses" width="50" height="50" />


```typescript  
class SoftwareDeveloper {

  private name: string;
  private alias: string;
  private passion: string;
  private role: string;
  private language: Array<string>;

  constructor() {
    this.name = "Fainner Ramirez";
    this.alias = "Fai";
    this.passion = "Desarrollar Side Projects"
    this.role = "FullStack Web Developer";
    this.language = ["es_ES", "COL"];
  }

  public Welcome(): void {
    console.log("¡Gracias por ver mi perfíl!...espero que encuentres algo interesante de mi trabajo");
  }
}

const me = new SoftwareDeveloper();
me.Welcome();
```
