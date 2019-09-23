# CV
## Maksym Ovchynnikov

* 098-13-44-320
* maxim170894@gmail.com
* live:maxim170894
* www.linkedin.com/in/maksym-ovchynnikov-962568150

***

### *Self-presentation*:
<p>My name is Maksym Ovchynnikov, and i want to improve my skills in web development. I have a few years of experience working with web technologies and have extensive background of computer literacy</p>

### *Skills:*
* HTML5
* CSS3
* Flexbox
* SASS/SCSS
* Mobile First
* Bootstrap
* Webpack
* JavaScrypt
* jQuery

### *Code examples:*
```
(function() {
    // Theme switch
    let themeSwitch = document.getElementById('themeSwitch');

    if(themeSwitch) {
      initTheme(); // if user has already selected a specific theme -> apply it
      themeSwitch.addEventListener('change', function(event){
        resetTheme(); // update color theme
      });

      function initTheme() {
        let darkThemeSelected = (localStorage.getItem('themeSwitch') !== null && localStorage.getItem('themeSwitch') === 'dark');
        // update checkbox
        themeSwitch.checked = darkThemeSelected;
        // update body data-theme attribute
        darkThemeSelected ? document.body.classList.add('white-content') : document.body.classList.remove('white-content');
        darkThemeSelected ? document.body.setAttribute('data', 'blue') : document.body.removeAttribute('data');
      };

      function resetTheme() {
        if(themeSwitch.checked) { // dark theme has been selected
          document.body.classList.add('white-content');
          document.body.setAttribute('data', 'blue');
          localStorage.setItem('themeSwitch', 'dark');
        } else {
          document.body.classList.remove('white-content');
          document.body.removeAttribute('data');
          localStorage.removeItem('themeSwitch');
        } 
      };
    }
  }());
  ```

### *Experience:*

* Feb 2019 – now. TapMedia_LLC. HTML/CSS Developer
* Oct 2017 – Feb 2019. TapMedia_LLC. Technical Support
* May 2018 – Nov 2018. TapMedia_LLC. System Administrator

### *Education:*

* 2011 – 2017 Odessa National
Telecommunications Academy
Telecommunication technologies
and equipment.
Master's degree

### *English:*

<p>Level Intermediate. I have enough practical experience communicating with native speakers as technical support engineer.</p>