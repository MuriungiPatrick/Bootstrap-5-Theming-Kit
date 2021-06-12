# Bootstrap v5 Theme Kit
A starter project for making Bootstrap 5 themes with Sass

*** This is simple starter project to help you get started quickly when making a custom Bootstrap theme.

![theming-kit html](https://user-images.githubusercontent.com/11283502/116907735-a58d7280-ac4a-11eb-8dbd-b905648593f8.png)



## Prerequisites

This works on Windows, macOS and Linux.
Node Package Manager are required. Make sure you can `run node --v.`
You can get Node at `nodejs.org`, then install dart-sass using `npm install sass --save-dev`

## Getting started

1. Clone this repo 
2. Then navigate to the to the clone project which will be (Bootstrap-5-Theming-Kit)
3. Run npm install
4. Add any Bootstrap 5 Sass variables you want to override into `scss/_custom.scss`by  copying them from bootstrap ```_variables.scss file```.
 check inside ```node_modules/bootstrap/scss/_variables.scss```
5. On your terminal run ``npm run compile:sass`` to Compile bootstrap.scss and then make sure you link the bootstrap.css stylesheet( check inside css folder ) to the head section of the theming-kit.html
6. Look at theming-kit.html (ideally with a local development webserver).  
7. enjoy :-).