# Viktoriya Nyu
![image info](./assets/myphoto.jpg)

## Contacts
- Email: nyuvv42a@gmail.com
- Discord: Viktoriya#9317
- GitHub: viktoriyavn
- Phone: +7-747-693-86-20

## Summary
I graduated Computing Technology and Software Department and worked as a consultant in EY (IT Risk Department).
My main hobby is learning new technologies.
I enjoy listening to rock music and reading science fiction.
I want to develop professionally and contribute to improving the world around me.

## Skills
- Java
- Node.js
- Manual software testing

## Code<br>
const {chromium} = require('playwright');
(async () => {
const browser = await chromium.launch({
headless:false })
const currentContext = await browser.newContext();
const page = await currentContext.newPage();
await page.goto('https://uppy.io/examples/dashboard/');
await page.click('[id="opts-DashboardInline"]');
let checkboxes = await page.evaluate(() => {
let checkBox1 = document.getElementById('opts-DashboardInline');
return {
checkbox:checkBox1
}; }); })();

## Courses
- Software Functional Testing

## Projects
- Playwright+Node.js example

## Education
- 2015 - 2019 L.N. Gumilyov Eurasian National University, Faculty of Information and Communication Technology

## Languages
- Russian - Native
- Kazakh - A2
- English - B2
