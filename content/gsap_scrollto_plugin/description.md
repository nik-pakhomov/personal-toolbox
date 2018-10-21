# GSAP ScrollTo plugin
[Site](https://greensock.com/docs/Plugins/ScrollToPlugin) | [GitHub](https://github.com/greensock/GreenSock-JS/blob/master/src/uncompressed/plugins/ScrollToPlugin.js)

---

GSAP is really powerful set of libraries for cross-browser animations through JavaScript. For anchor scrolling navigation (or just scrolling navigation) _ScrollTo_ plugin should be used. To add GSAP into the project, need to install npm package:
```
> npm i gsap
```

Then just go into the package directory in node_modules folder and add to build system or into the page those files, that needed for task. All info about library API can be found in [GSAP documentation](https://greensock.com/docs).

After _TweenLite_ and _ScrollTo_ plugin will be added to the page, for scroll to some page part just write:
```javascript
TweenLite.to(window, 2, { scrollTo: "elementId" });
```
where: 
 - first (window) is target object which properties should be affected;
 - second (2) animation duration in seconds (can be set with floating number);
 - third is options. For ScrollTo plugin only one parameter will be enough.
