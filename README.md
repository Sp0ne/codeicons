# Codeicons

[![GitHub version](https://badge.fury.io/gh/Sp0ne%2Fcodeicons.svg)](https://badge.fury.io/gh/Sp0ne%2Fcodeicons)
[![Bower version](https://badge.fury.io/bo/codeicons.svg)](https://badge.fury.io/bo/codeicons)

A simple icon's collection for development languages, programming tools and other work environment. 

Have a look to the [demo page](https://sp0ne.github.io/codeicons/).

![Codeicons preview](http://i.imgur.com/XYtRtyd.jpg)


---


#### Request

For Icon's request please leave a comment [here](https://github.com/Sp0ne/codeicons/issues). 
Please refer to the contribute section for your request. 
Do you have any additional? Drop me a line or support an issue.



## Install

Install Codeicons as a dependency to your project with _Bower_.

```bash
  bower install --save codeicons
```



## Usage 

_Ways of using Codeicons:_

**FONT ICONS**

Import stylesheet from vendors, add `<style>` for your project and add icon using `<i>` tag with your class name.

```html
  <!-- <head> -->
  <link rel="stylesheet" href="../codeicons.css"/>

  <!-- add style -->
  <style type="text/css" media="screen">
  	[class^="codeicon-"] { ... }
  </style>

  <!-- <body> -->
  <i class="codeicon-git"></i>
```


**SVG ICONS**

Copy/paste svg code from `/svg` folder in your html code. Add your own class if you want.

```html
  <!-- <body> -->
  <svg class="codeicon-github" viewBox="0 0 128 128">
  	<path d="..."/>
  </svg>
```

**Production** _(Optional)_

If you're using Grunt you can copy/paste the fonts with a grunt task [More details](https://github.com/gruntjs/grunt-contrib-copy).
Load  `npm install grunt-contrib-copy --save-dev` and add a task in your `/GruntFile.js`.

```js
  // Grunt task for copy files:
  copy: {
      fonts: { dest: 'path/fonts', src: ['bower/codeicons/fonts/*'] }
  }, ...
  // Add your task in your register Task:
  grunt.registerTask('default', ['copy:fonts']);
```

---



### Road Map in progress : 

- [ ] Contributing section
- [ ] Register Npm packages 
- [ ] Add colored icons (full colored)
- [x] ~~Better how-to-use section (link, comment, img...)~~
- [x] ~~Make better demo~~
- [x] ~~Add news icons~~



- - -



### Changelog

- v1.2.0 - Add news icons svg. (Total : 106 files / ~ 100 icons)
- v1.1.1 - Minors bower fixs and demo.
- v1.1.0 - Add icons svg + add src new icon + readme + minors fixs.
- v1.0.0 - Initialisation Project and Packages on bower.



---



### Contribute & Develop

First of all, thanks for taking the time to contribute!

Please have a look at the CONTRIBUTING.md file for more informations.

Under [MIT Licence](https://github.com/Sp0ne/codeicons/blob/master/LICENSE)

<sub>All brand icons are property of their respective owners. All company, product and service names used in this website are for identification purposes only. Use of these names, logos, and brands does not imply endorsement.</sub>



---



### Credits

- Final font build with [Icomoon app](https://icomoon.io/)
- Inspired and partial fork by [Devicon](https://devicon.fr/)



---



#### Author

_Originally written with ♥ by @Sp0ne ([Vinces](https://vinces.io ) - Digital Developer)_