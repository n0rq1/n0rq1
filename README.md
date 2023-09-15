
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
    return "male (he/him)";
  }

  /**
   * @returns {Array<string>}
   */
  get skillset() {
    return [
      "C++", "C", "Docker", "JavaScript",
      "Dart", "Python", "Bash", "CSS", "SQL", "OCaml"
    ];
  }

  /**
   * @returns {Object}
   */
  get socials() {
    return {
      "discord": "DynoNugget7" /*Feel free to msg me :) */
    }
  }

}
```
