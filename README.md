# Hey there 👋,

### I'm Jhonnatha Solsona!

> Majoring in bachelor of Science and Technology from the <a href="https://ufrn.br/en">Federal University of Rio Grande do Norte</a>!

[![Linkedin: jhonnathasolsona](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jhonnatha-solsona-405064178/)

#### A little bit about me (~/JFelipeSS.class)...

```java
package world.occupants;

import ...

public class JFelipeSS extends Person {

  private final String firstName;
  private final String surname;

  private final Parents parents;

  private final Date birthDate;

  private Skills personalSkills;

  public JFelipeSS() {
    final Person mother = PeopleDAO.findByName("Cristiane...");
    final Person father = PeopleDAO.findByName("João...");

    this.parents = new Parents();

    parents.setMother(mother);
    parents.setFather(father);

    this.birthDate = LocalDate.of(2001, 04, 24);

    this.firstName = "Jhonnatha";
    this.surname = "Solsona";

    this.personalSkills = configurePersonalSkills();
  }

  private Skills configurePersonalSkills() {
    Skills skills = new Skills();

    skills.loadDevelopmentSkills();
    skills.removeAnySportSkills();

    return skills;
  }
}
```

###### TODO: Improve this README file
<img src="https://media3.giphy.com/media/f7b9ltJ4FrhnsKjYx2/giphy.gif">
