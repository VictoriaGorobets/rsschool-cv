****
# Victoria Gorobets
****
## Student of RS Scope courses, stage 1
****
## Contact information:
* **E-mail:** vickyhome1996@gmail.com
* **Phone:** +370-666-89-125 
* **Telegram:** @VictoriaGorobets
* **GitHub:** [VictoriaGorobets](https://github.com/VictoriaGorobets)
* **Discord:** victoriagorobets_13219
****
## About Myself:
I am a responsible person, always ready to learn new things. Worked as an engineer, designed security systems.
****
## Skills
* HTML
* CSS
* JS
****
## Education
* Bachelor, Belarusian National Technical University, technical maintenance of safety
****
## Experience 
Worked as an security engineer. Now I am a tutor in physics and mathematics.

**** 
## Code Example
```
class Tinder {
  constructor (){
    this.arrayOfForms = [];
  }
  add(form) {
    this.arrayOfForms.push(form);
  }
  findPairs(){
    const arrayOfMales = this.arrayOfForms.filter(form => this.isMale(form));
    const arrayOfFemales = this.arrayOfForms.filter(form => !this.isMale(form));
    const pairs = [];
    arrayOfMales.forEach(maleForm => {
      const femaleMatch = arrayOfFemales
        .filter(femaleForm => femaleForm.age <= maleForm.maxPartnerAge
                               && maleForm.age <= femaleForm.maxPartnerAge);
      femaleMatch.forEach(femaleForm => pairs.push(new Pair(maleForm, femaleForm)))
    })
    return pairs;
  }
  
  isMale(form) {
     return form.gender === Gender.male;
  }
}
```
****
## English
A2-B1
****
![](https://avatars.githubusercontent.com/u/106545511?s=400&u=07d521c4e542b7d9195d3ac82cb2225c530386a6&v=4)
