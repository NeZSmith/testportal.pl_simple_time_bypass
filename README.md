# **testportal.pl simple time bypass**
## [**Check out FAQ**](https://github.com/NeZSmith/E-LEARNING-STARTER-KIT-FOR-ASPIRING-STUDENTS/blob/main/FAQ.md)
### **This script will allow you to bypass time on testportal.pl**

Simple script written in JS will allow you to set unlimited time on your exams
`setInterval(() => {window.startTime = new Date().getTime()},0);`
Paste this to your browser console or use Tempermonkey/Violentmonkey
***exemplary Violentmonkey config***
```
// ==UserScript==
// @name         Testportal simple time bypass
// @namespace    https://*.testportal.pl/
// @version      1.0.0@Stable
// @description  n1
// @author       NeZ
// @match        https://*.testportal.net/*
// @match        https://*.testportal.pl/*
// @grant        none
// ==/UserScript==
setInterval(() => {window.startTime = new Date().getTime()},0);
```
