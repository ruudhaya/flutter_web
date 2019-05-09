# flutter_web

Web project created in Flutter

Project Setup - Prerequisites

- flutter upgrade
- Add the dart sdk path to \$PATH

  - export PATH="\$PATH":"<Path to Flutter installation directory>/bin/cache/dart-sdk/bin"

- Create a new Flutter Web Project - Used VSCode
- From the terminal of project directory - install webdev
  - flutter packages pub global activate webdev
  - flutter packages upgrade
- Add Webdev to PATH
  - export PATH="$PATH":"$HOME/development/flutter/.pub-cache/bin"
- Run the web application with
  - webdev serve
    (or)
  - webdev serve --auto restart // For stateless hot-reload

#### Build and deploy

- To Build the project
  - webdev build
    // We can find the /build directory created in project with main html and compiled js files

* /build directory contents can be directly deployed
  Eg: From /build folder using 'surge' will deploy it to random surge url successfully

Note:

Installing and using Surge

- Use latest node version
- Install node package for surge
