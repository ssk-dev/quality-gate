# quality-gate
Linting and code analysis for Web development.
- SASS/SCSS
- Typescript
- Javascript

## install NodeJS
1. Download NodeJS from https://nodejs.org/
2. Check your ruby versi
3. Type in ``npm -v``
4. Install Dependencies from package.json (location: root) ``npm i``

## install Ruby
1. Install Ruby via RubyInstaller: http://rubyinstaller.org/downloads/
2. Check your ruby version: Start - Run - type in cmd to open a windows console
3. Type in ``ruby -v``

## Install Sass Lint
1. Type in command line tool ``ruby install sass_lint``

#### Configure Scss linter

**Webstorm**
> Navigate : File -> Settings -> Other Settings -> SCSS Linter 
- [x] Enable
- [x] SCSS Lint exe -> C:\Ruby25-x64\bin\scss-lint.bat (in my case on Windows)
- [x] Use specific config file: {root location of current project}\sass-lint.yml

## Run Scripts (console commands)
* Run **Sass/Scss** linter: ``npm run lint.sass``
* Run **Sass/Scss** fix & lint: ``npm run lint.sass:fix``
* Run **Css** lint: ``npm run lint.css``
* Run **Javascript** linter: ``npm run test.js``
* Run **Javascript** fix & lint: ``npm run test.js:fix``
