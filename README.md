export default class MyProfile {
  constructor() { }

  /**
   * @returns {string} Full Name
   */
  get full_name() {
    return "Andreas Maerten";
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
      "C++", "C#", "Docker",
      "Fullstack Web", "NodeJS",
      "Lua",  "PHP", "Python",
      "VueJS"
    ];
  }

  /**
   * @returns {Object}
   */
  get socials() {
    return {
      "discord": "https://discord.gg/EG4zHFR", // Don't contact me in my DM's I will block you
      "steam"  : "steamcommunity.com/id/y1mura",
      "twitter": "@Yimura9"
    }
  }

  /**
   * @returns {string}
   */
  getMoreInfo() {
    return "https://andreas.is.a.pieceof.art";
  }
}
