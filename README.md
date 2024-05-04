```javascript
// Welcome to my world!

const displayAboutMe = () => {
  const aboutMe = {
    name: "Masum Billah",
    introduction: "I'm a self-taught web developer dedicated to making online dreams a reality.",
    language: "JavaScript",
    coreTechnologies: ["MongoDB", "Express", "React", "Node"],
    tools: ["Git", "Figma", "Inkscape", "Material UI", "and More..."],
    interests: ["WebTechnologies", "Reading", "Travelling"],
    personalWebSite: "http://billah.dev",
    location: "Manila, Philippines",
    contact: {
      email: "emasumbillah@gmail.com",
      twitter: "/eMasumBillah",
      GitHub: "/billahDotDev",
    }
  };
  console.log(aboutMe);
};

displayAboutMe();

<div style="position: relative; overflow: hidden; white-space: nowrap;">
  <span id="moving-text" style="position: absolute; animation: moveText 5s linear infinite;">Your moving text here</span>
</div>

<style>
  @keyframes moveText {
    0% {
      transform: translateX(0);
    }
    100% {
      transform: translateX(-100%);
    }
  }
</style>



