# flutter_web

Web project created in Flutter

Project Setup - Prerequisites

- flutter upgrade
- Add the dart sdk path to $PATH
    -> export PATH="$PATH":"<Path to Flutter installation directory>/bin/cache/dart-sdk/bin"
- Create a new Flutter Web Project - Used VSCode
- From the terminal of project directory - install webdev
  -> flutter packages pub global activate webdev
  -> flutter packages upgrade
- Add Webdev to PATH
  -> export PATH="$PATH":"$HOME/development/flutter/.pub-cache/bin"
- Run the web application with
  -> webdev serve
  (or)
  -> webdev serve --auto restart // For stateless hot-reload
