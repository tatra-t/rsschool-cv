![me](1.jpg)
# Tetiana Dushenko
_____
29.07.1982

Dnipro, Ukraine


but now I live in Inowroclaw, Poland
____
## **Contact:**
tanechka.dush@gmail.com

+48511789425, +380974710404 (viber, telegram)

[Linkedin](https://www.linkedin.com/in/tatiana-dushenko-568a40222), 
[GitHub](https://github.com/tatra-t)
_____
## **About myself:** 

I am a quick learner and never stop at what has been achieved, I am very
responsible and independent, I can make decisions and be responsible for them.
I have extensive experience in working with people, stress-resistant and sociable.

Married, 2 sons (11, 2)

Driving license cat. В

_____
## **Professional skills:** 

HTML, CSS, JavaScript, Visual Studio Code, GitHub, Bootstramp, Hosting, Flexbox, SEO, Responsive,
Figma, Photoshop –beginner
_____
## **Languages:**

* Ukrainian - fluently
* Russian - fluently
* English - Pre-Intermediate
* Polish - Beginner
_____
## **Experience:**

* 2019 – p.t. Maternity leave
* 2015 - 2019 Financial manager - Alef TIC 
* 2007 - 2015 Financial Director - Telemost, LLC 
* 2005 - 2007 Engineer - telecommunications, Ukrtelecom, DF OJSC
_____
## **Education:**

* 2022 - SheCodes, Front-end developer
* 2019 -  QATestLab, testing
* 2005 - 2006 KNURE, Engineering communication networks
* 1999 - 2004 KTU, Urban construction and economy
_____
## **Code examples:**
```javascript
function curPosition(position) {
  let lat = position.coords.latitude;
  let lon = position.coords.longitude;
  console.log(lat, lon);
  let apiKey = "5bd8dd5876af31be7dd1dd4666c7f2a5";
  let apiUrl = `https://api.openweathermap.org/data/2.5/weather?lat=${lat}&lon=${lon}&appid=${apiKey}&units=metric`;
  axios.get(apiUrl).then(timeDate);
  console.log(apiUrl);

  let cityName = response.data.name;
  let h1 = document.querySelector("h1");
  h1.innerHTML = cityName;
}
navigator.geolocation.getCurrentPosition(curPosition);

let curLoc = document.querySelector(".curLoc");
curLoc.addEventListener("click", curPosition);     
```
_____