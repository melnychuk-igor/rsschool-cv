## [rsschool-cv](http://example.com/)

# Igor Melnychuk
## Junior Frontend Developer

---

## Contact information:

**Phone:** +38 0686491989
**E-mail:** igor.melnychuk@gmail.com
**Telegram:** @Igor_Melnychuck
**[LinkedIn](https://www.linkedin.com/in/igor-melnychuck-54144b200/)**

---

## Briefly About Myself:
I am working as a Wordpress developer for 2 years. I have started my career with creating a site layout and then I have continued to work with Wordpress but I would like to work a Front End Developer in the future because I am interested in this field. I have such good qualities as: punctuality, perseverance, responsibility, diligence.

---

## Skills and Proficiency:

- HTML5
- CSS3, Preprocessor Sass/Scss, Bootstrap
- JS/Jquery
- Php
- Adobe Photoshop, Figma
- Cms Wordpress,
- Бібліотеки Aos, GSAP, ScrollMagic
- Slider Swiper/Slick
- Wordpress plugins: ACF, Carbon Fields, Contact Form 7, WPML, Yoast SEO
- Git

---

## Code example:
**Stopwatch on Js**
```
const timer = document.getElementById("timer");
let seconds = 0;
let minutes = 0;
let hours = 0;

function init() {
	setInterval(tick, 1000);
}

function tick() {
	seconds++;
	if (seconds >= 60) {
		minutes++;
		seconds = seconds - 60;
	}
	if (minutes >= 60) {
		hours++;
		minutes = minutes - 60;
	}
	if (seconds < 10) {
		if (minutes < 10) {
			if (hours < 10) {
				timer.innerHTML =
					"0" + hours + ":0" + minutes + ":0" + seconds;
			} else {
				timer.innerHTML =
					hours + ":0" + minutes + ":0" + seconds;
			}
		} else {
			if (hours < 10) {
				timer.innerHTML =
					"0" + hours + ":" + minutes + ":0" + seconds;
			} else {
				timer.innerHTML =
					hours + ":" + minutes + ":0" + seconds;
			}
		}
	} else {
		if (minutes < 10) {
			if (hours < 10) {
				timer.innerHTML =
					"0" + hours + ":0" + minutes + ":" + seconds;
			} else {
				timer.innerHTML =
					hours + ":0" + minutes + ":" + seconds;
			}
		} else {
			if (hours < 10) {
				timer.innerHTML =
					"0" + hours + ":" + minutes + ":" + seconds;
			} else {
				timer.innerHTML =
					hours + ":" + minutes + ":" + seconds;
			}
		}
	}
}

init();
```

---

## Experience:

- Web developer at AWEB System (6 months)
- WordPress developer at SP//DEV (10 months)
- WordPress developer at Wpwp.bz (3 months)

---

## Education:

- **University:** Ivano-Frankivsk National Technical University of Oil and Gas
- **Courses:** Full course on JavaScript + React Course - From Zero to Result

---

## Languages:

- English - Elementary
- Ukrainian - Native
- Russian - Intermediate
