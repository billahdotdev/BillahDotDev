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


// Your JavaScript code here

// Define the image as a Base64-encoded data URL
const imageDataUrl = 'data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsQAAA7EAZUrDhsAAAANSURBVBhXYzh8+PB/AAffA0nNPuCLAAAAAElFTkSuQmCC';

// Create an <img> element and set its src attribute to the data URL
const img = document.createElement('img');
img.src = imageDataUrl;
img.alt = 'Alt text'; // Provide a descriptive alt text

// Append the <img> element to the document body
document.body.appendChild(img);







