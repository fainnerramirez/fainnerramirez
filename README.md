
```typescript  
class SoftwareDeveloper {

  private name: string;
  private alias: string;
  private passion: string;
  private age: number;
  private height: number;
  private role: string;
  private language: Array<string>;

  constructor() {
    this.name = "Fainner Ramirez";
    this.alias = "Fai";
    this.passion = "Desarrollar Side Projects"
    this.age = 27;
    this.height = 1.88;
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

## Estadísticas de GitHub
![Mis estadísticas de GitHub](https://github-readme-stats.vercel.app/api?username=fainnerramirez&show_icons=true&theme=radical)
