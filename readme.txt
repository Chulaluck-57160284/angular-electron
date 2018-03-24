https://angularfirebase.com/lessons/desktop-apps-with-electron-and-angular/
create project 
1.download node version > 8.2.1 => install node
2.npm install -g @angular/cli => install angular
3.ng new angular-electron => create angular app
4.cd angular-electron
5.src/index.html change <base href="/"> to <base href="./">
6.npm install electron --save-dev
7.create main.js in root project
8.insert code in main.js
9.insert code in package.json
10.npm run electron-build
deploy project
1.npm install electron-packager -g
2.npm install electron-packager --save-dev
3.electron-packager . --platform=win32 => window