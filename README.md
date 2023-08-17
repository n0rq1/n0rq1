
```js
export default class MyProfile {
  constructor() { }

  /**
   * @returns {string} Full Name
   */
  get full_name() {
    return "Austin Norquist";
  }

  /**
   * @returns {string} Gender
   */
  get gender() {
    return "male";
  }

  /**
   * @returns {Array<string>}
   */
  get skillset() {
    return [
      "C++", "C", "Docker", "ReactJS",
      "Flutter", "Python", "Bash", "CSS", "SQL", "OCaml"
    ];
  }

  /**
   * @returns {Object}
   */
  get socials() {
    return {
      "discord": "DynoNugget7"
    }
  }

}
```
