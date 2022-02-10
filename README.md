class créams {
  constructor(...options) {
    this.height = "1.70"
    this.weight = "50"
    this.age = "16"
    this.type = "human"
    this.job = "student"
    this.sex = "male"
  }
}

class CreateMan extends créams {
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
