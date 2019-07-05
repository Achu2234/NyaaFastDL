This website will help you to download torrent faster than Nyaa website.

The goal was to learn how parse an HTML page by scrapping torrents on Nyaa.si (<3), you need to ask Nyaa.si before using this project.

# This tool uses :

* [Vue.js](https://vuejs.org/) - Progressive framework
* [Ant Design Vue](https://vue.ant.design/) - Component framework for Vue.js

# Requirements
## Classic
* Node.js >= 8.9
* npm
* Vue CLI 3

## Docker
- Docker CE
- Docker-compose

# Dev
In current directory run `npm install` 

In current directory run`npm run serve` and access to the website `http://localhost:8080`

# Production
You can use your own CORS anywhere (Default herokuapp) by changing the constant line 336

Configure default value of input/select by editing `src/App.vue`

Default Value
~~~~
videoQualitySelected: '1080p',
languageSelected: 'VOSTFR',
filterSelected: '0',
categorySelected: '0_0',
sortSelected: undefined,
~~~~
## Classic

In current directory run `npm run-script build` and serve `/dist` with a webserver

## Docker

Use the Dockerfile provided and serve static directory of Dockerfile `/opt/services/NyaaFastDL/static/` with a webserver

# Licence

The code is under CeCILL license.

You can find all details here: http://www.cecill.info/licences/Licence_CeCILL_V2.1-en.html

# Credits

Copyright © Ludovic Ortega, 2019

Contributor(s):

-Ortega Ludovic - mastership@hotmail.fr
