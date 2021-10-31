- 👋 Hi, I’m @Pass-word12
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Pass-word12/Pass-word12 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
constructor(param : number, event : CoreEvent) {
  let startIndex = clamp(Number(param), 1, MAP_DATA.length);
-  this.stage = new Stage(startIndex);
+  this.stage = new Stage(4);
    }
  }
