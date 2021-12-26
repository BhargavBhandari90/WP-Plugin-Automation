# WP-Plugin-Automation

Basic WordPress plugin automator.
Automation includes following:
- Minify CSS & JS
- Create pot file
- Correct text domains

## How to use

1. Add `Gruntfile.js` and `package.json` to your plugin
2. In the `package.json`, do following changes according to your plugin

> ![image](https://user-images.githubusercontent.com/19459637/147416105-38943aac-a4a6-4398-a7e7-70507640819d.png)

3. In the `Gruntfile.js`, change according to your plugin

> ![image](https://user-images.githubusercontent.com/19459637/147416137-18492c60-bb37-43f9-a68a-ccf151811ac6.png)
> ![image](https://user-images.githubusercontent.com/19459637/147416161-d0e8eb50-aaba-464b-89f4-d9441de82d46.png)

4. Now, go to plugin root folder where you put these two files.
5. run `npm install`
6. run `npm start` ( to run one time )
7. run `grunt watch` ( to watch events while developing. It will create minify JS & CSS )
