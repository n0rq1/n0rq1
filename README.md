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
      "C++", "C", "ReactJS",
      "Python", "Flutter", "CSS",
      "Bash", "Docker"
    ];
  }

  /**
   * @returns {Object}
   */
  get socials() {
    return {
      "Discord": "DynoNugget7"
    }
  }
}
