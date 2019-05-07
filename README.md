First you need to have Node.js installed, which can be download form https://nodejs.org/en/.
After you have Node.js installed, you could install other packages by using NPM like this:
```
npm i -g  @angular/cli ionic typescript electron
```
Where includes 4 packages and they might need to be run with sudo
Then just open the project folder where the pacakage.json exists, and run
```
npm i
```
This will download the dependencies of the project automatically, which might take a while
After that, you should be able to run npm run electron-serve in the same folder, which would build and launch the app.
 
Here are some package that I used in this project:
[Angular](https://angular.io/) (used for data binding and routing)
[Ionic](https://ionicframework.com/) (just use it for my UI components)
[TypeScript](https://www.typescriptlang.org/) (used by Angular)
[Electron](https://electronjs.org/) (used to build desktop app)
