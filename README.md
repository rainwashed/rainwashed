<img src="./assets/av.png" width="100" height="100">

```typescript
class Person {
  /*
    ...
*/
}
class RainWashed extends Person {
  name: string;
  alias: string;
  gender: "male" | "female" | "etc.";
  age: number;
  location: [string, string];
  languages: string[];
  interests: string[];
  contacts: {
    platform: string;
    contact: string;
  }[];

  constructor() {
    console.log("Hello World!");

    super();
    this.name = "Andrew";
    this.alias = "RainWashed";
    this.gender = "male";
    this.age = -1;
    this.location = [
        "Michigan",
        "United States"
    ];
  }

  assignLanguages(): void {
    this.languages = [
        "Python(3)",
        "JavaScript",
        "HTML & CSS",
        "TypeScript*"
    ];
  }

  assignInterests(): void {
    this.interests = [
        "Programming",
        "Photography",
        "Tennis",
        "Learning"
    ];
  }

  assignContacts(): void {
    this.contacts = [
      /*
            ...
        */
    ];
  }
}
```
