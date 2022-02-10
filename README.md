```js
class OnurChngr {
  constructor(...options) {
    this.height = "1.70"
    this.weight = "50"
    this.age = "16"
    this.type = "human"
    this.job = "student"
    this.sex = "male"
  }
}

class CreateMan extends OnurChngr {
  constructor(...options) {
    super(options);
  }
  
  private _eating() {
    void "eating 🥩 🍷"
  }
  
  private _coding() {
    void "coding... ❤️"
  }
  
  private _sleep(ms) { return new Promise(resolve => setTimeout(resolve, ms)) }
  
  async createDay() {
    this._eating();
    this._coding();
    await this._sleep(18000000);
    
    this.createDay();
  }
}

let OnurChngr = new CreateMan()
OnurChngr.createDay();
```



##  Dostlarım
- ![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91.svg?style=for-the-badge&logo=visual-studio&logoColor=white)
- ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
- ![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white)
- ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) <img src="https://komarev.com/ghpvc/?username=OnurChngr&label=Ziyaretçi%20Sayısı&color=723F98" alt="OnurChngr"/>
<a href="https://github.com/OnurChngr">
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=OnurChngr&theme=light&hide_langs_below=1" />
</a>


<div align="center">


