# cypress/browsers

[![Docker Pulls](https://img.shields.io/docker/pulls/cypress/browsers.svg?maxAge=604800)](https://hub.docker.com/r/cypress/browsers/)

> Docker image with all operating system dependencies and some pre-installed browsers, **but NOT Cypress itself**. See [cypress/included](../included) images if you need Cypress pre-installed in the image.
 
 Name + Tag | Base image | Chrome | Firefox | Edge
--- | --- | --- | --- | ---
[cypress/browsers:node8.9.3-npm6.10.1-chrome75](./node8.9.3-npm6.10.1-chrome75) | `cypress/base:8.9.3-npm-6.10.1` | `75.0.3770.100` | 🚫
[cypress/browsers:node10.16.0-chrome77-ff71](./node10.16.0-chrome77-ff71) | `cypress/browsers:node10.16.0-chrome77` | `77.0.3865.90` | `71.0`
[cypress/browsers:node12.4.0-chrome76](./node12.4.0-chrome76) | `cypress/base:12.4.0` | `76.0.3809.87` | 🚫
[cypress/browsers:node12.6.0-chrome75](./node12.6.0-chrome75) | `cypress/base:12.6.0` | `75.0.3770.100` | 🚫
[cypress/browsers:node12.8.1-chrome78-ff70](./node12.8.1-chrome78-ff70) | `cypress/browsers:node12.13.0-chrome78-ff70` | `78.0.3904.97` | `70.0.1`
[cypress/browsers:node12.13.0-chrome78-ff70](./node12.13.0-chrome78-ff70) | `cypress/base:12.13.0` | `78.0.3904.97` | `70.0.1`
[cypress/browsers:node12.13.0-chrome80-ff74](./node12.13.0-chrome80-ff74) | `node:12.13.0-buster` | `80.0.3987.116` | `74.0`
[cypress/browsers:node12.14.1-chrome83-ff77](./node12.14.1-chrome83-ff77) | `cypress/base:12.14.1` | `83.0.4103.61` | `77.0`
[cypress/browsers:node12.16.1-chrome80-ff73](./node12.16.1-chrome80-ff73) | `cypress/base:12.16.1` | `80.0.3987.122` | `73.0.1`
[cypress/browsers:node12.16.2-chrome81-ff75](./node12.16.2-chrome81-ff75) | `cypress/base:12.16.2` | `81.0.4044.113` | `75.0`
[cypress/browsers:node12.18.0-chrome83-ff77](./node12.18.0-chrome83-ff77) | `cypress/base:12.18.0` | `83.0.4103.61` | `77.0`
[cypress/browsers:node12.19.0-chrome86-ff82](./node12.19.0-chrome86-ff82) | `cypress/base:12.19.0` | `86.0.4240.193` | `82.0.3`
[cypress/browsers:node12.8.1-chrome80-ff72](./node12.8.1-chrome80-ff72) | `cypress/base:node12.8.1` | `80.0.3987.87` | `72.0.2`
[cypress/browsers:node12.18.3-chrome87-ff82](./node12.18.3-chrome87-ff82) | `cypress/base:node12.18.3` | `87.0.4280.66` | `82.0`
[cypress/browsers:node12.18.3-chrome89-ff86](./node12.18.3-chrome89-ff86) | `cypress/base:12.18.3` | `89.0.4389.72` | `86.0.1`
[cypress/browsers:node12.18.4-edge88](./node12.18.4-edge88) | `cypress/base:12.18.4` | 🚫 | 🚫 | `88.0.673.0 dev`
[cypress/browsers:node13.6.0-chrome80-ff72](./node13.6.0-chrome80-ff72) | `cypress/base:13.6.0` | `80.0.3987.87` | `72.0.2`
[cypress/browsers:node13.8.0-chrome81-ff75](./node13.8.0-chrome81-ff75) | `cypress/base:13.8.0` | `81.0.4044.113` | `75.0`
[cypress/browsers:node14.7.0-chrome84](./node14.7.0-chrome84) | `cypress/base:14.7.0` | `84.0.4147.105` | 🚫
[cypress/browsers:node12.14.1-chrome85-ff81](./node12.14.1-chrome85-ff81) | `cypress/base:12.14.1` | `85.0.4183.121` | `81.0`
[cypress/browsers:node14.10.1-edge88](./node14.10.1-edge88) | `cypress/base:14.10.1` | 🚫 | 🚫 | `88.0.673.0 dev`
[cypress/browsers:node14.15.0-chrome86-ff82](./node14.15.0-chrome86-ff82) | `cypress/base:14.15.0` | `86.0.4240.193` | `82.0.3`
[cypress/browsers:node14.17.0-chrome88-ff89](./node14.17.0-chrome88-ff89) | `cypress/base:14.17.0` | `88.0.4324.96` | `89.0.2`
[cypress/browsers:node14.16.0-chrome89-ff77](./node14.16.0-chrome89-ff77) | `cypress/base:14.16.0` | `89.0.4389.72` | `77.0`
[cypress/browsers:node14.16.0-chrome89-ff86](./node14.16.0-chrome89-ff86) | `cypress/base:14.16.0` | `89.0.4389.72` | `86.0.1`
[cypress/browsers:node14.17.0-chrome91-ff89](./node14.17.0-chrome91-ff89) | `cypress/base:14.17.0` | `91.0.4472.114` | `89.0.2`
[cypress/browsers:node16.5.0-chrome94-ff93](./node16.5.0-chrome94-ff93) | `cypress/base:16.5.0` | `94.0.4606.71` | `93.0` 
[cypress/browsers:node16.14.0-slim-chrome99-ff97](./node16.14.0-slim-chrome99-ff97) | `cypress/base:16.14.0` | `99.0.4844.51` | `97.0.1` | `🚫`
[cypress/browsers:node14.17.6-chrome100-ff98](./node14.17.6-chrome100-ff98) | `cypress/base:14.17.6` | `100.0.4896.60` | `98.0.2` | `🚫`
[cypress/browsers:node16.13.2-chrome100-ff98](./node16.13.2-chrome100-ff98) | `cypress/base:16.13.2` | `100.0.4896.60` | `98.0.2` | `🚫`
[cypress/browsers:node17.8.0-chrome99-ff97-slim](./node17.8.0-chrome99-ff97-slim) | `cypress/base:17.8.0` | `99.0.4844.84` | `97.0.1` | `🚫`
[cypress/browsers:node16.14.0-edge](./node16.14.0-edge) | `cypress/base:16.14.0` | `🚫` | `🚫` | `--edge` 
[cypress/browsers:node16.14.0-chrome99-ff97](./node16.14.0-chrome99-ff97) | `cypress/base:16.14.0-slim` | `99.0.4844.51` | `97.0.1` | `🚫` 
[cypress/browsers:node16.14.2-slim-chrome100-ff99-edge](./node16.14.2-slim-chrome100-ff99-edge) | `cypress/base:16.14.2` | `100.0.4896.88` | `99.0.1` | `--edge` 
[cypress/browsers:node14.17.6-slim-chrome100-ff99-edge](./node14.17.6-slim-chrome100-ff99-edge) | `cypress/base:14.17.6` | `100.0.4896.88` | `99.0.1` | `--edge`
[cypress/browsers:node14.19.0-chrome100-ff99-edge](./node14.19.0-chrome100-ff99-edge) | `cypress/base:14.19.0` | `100.0.4896.88` | `99.0.1` | `--edge`
[cypress/browsers:node16.14.2-slim-chrome103-ff102](./node16.14.2-slim-chrome103-ff102) | `cypress/base:16.14.2` | `103.0.5060.53` | `102.0.1` | `🚫`
[cypress/browsers:node18.6.0-chrome105-ff104](./node18.6.0-chrome105-ff104) | `cypress/base:18.6.0` | `105.0.5195.102` | `104.0.1` | `🚫`
[cypress/browsers:node16.16.0-chrome105-ff104-edge](./node16.16.0-chrome105-ff104-edge) | `cypress/base:16.16.0` | `105.0.5195.125` | `104.0.2` | `--edge`
[cypress/browsers:node16.16.0-chrome105-ff99-edge](./node16.16.0-chrome105-ff99-edge) | `cypress/base:16.16.0` | `105.0.5195.125` | `99.0.1` | `--edge`
[cypress/browsers:node16.17.0-chrome106](./node16.17.0-chrome106) | `cypress/base:16.17.0` | `106.0.5249.61` | `🚫` | `🚫` 
[cypress/browsers:node16.16.0-chrome106-ff99-edge](./node16.16.0-chrome106-ff99-edge) | `cypress/base:16.16.0` | `106.0.5249.61` | `99.0.1` | `--edge` 
[cypress/browsers:node16.17.1-chrome105-ff104-edge](./node16.17.1-chrome105-ff104-edge) | `cypress/base:16.17.1` | `105.0.5195.125` | `104.0.2` | `--edge` 
[cypress/browsers:node16.17.1-chrome106-ff105-edge](./node16.17.1-chrome106-ff105-edge) | `cypress/base:16.17.1` | `106.0.5249.91` | `105.0.1` | `--edge` 
 
To find the available Chrome versions, check [https://chromium.cypress.io/](https://chromium.cypress.io/).

## Naming scheme

Each Docker image is named `cypress/browsers:node<full Node version>-chrome<Chrome major version>`. If the image has Firefox browser, then it is named `cypress/browsers:node<full Node version>-chrome<Chrome major version>-ff<Firefox major version>`.

## Other images

Other (older) images:

- Node 8 + Chrome 65 + Firefox 57 [/chrome65-ff57](chrome65-ff57)
- Node 8 + Chrome 67 + Firefox 57 [/chrome67-ff57](chrome67-ff57)
- Node 8 + Chrome 67 [/chrome67](chrome67)
- Node 8.2.1 + Chrome 73 [/node8.2.1-chrome73](node8.2.1-chrome73)
- Node 8.9.3 + Chrome 73 [/node8.9.3-chrome73](node8.9.3-chrome73)
- Node 8.9.3 + Chrome 76 + Firefox 68 [/node8.9.3-npm6.10.1-chrome76-ff68](node8.9.3-npm6.10.1-chrome76-ff68)
- Node 8.15.1 + Chrome 73 [/node8.15.1-chrome73](node8.15.1-chrome73)
- Node 10 + Chrome 69 [/chrome69](chrome69)
- Node 10.2.1 + Chrome 74 [/node10.2.1-chrome74](node10.2.1-chrome74)
- Node 10.11.0 + Chrome 75 [/node10.11.0-chrome75](node10.11.0-chrome75)
- Node 10.16.0 + Chrome 76 [/node10.16.0-chrome75](node10.16.0-chrome76)
- Node 10.16.0 + Chrome 77 [/node10.16.0-chrome77](node10.16.0-chrome77)
- Node 11.13.0 + Chrome 73 [/node11.13.0-chrome73](node11.13.0-chrome73)
- Node 12.0.0 + Chrome 73 [/node12.0.0-chrome73](node12.0.0-chrome73)
- Node 12.0.0 + Chrome 73 + Firefox 68 [/node12.0.0-chrome73-ff68](node12.0.0-chrome73-ff68)
- Node 12.0.0 + Chrome 75 [/node12.0.0-chrome75](node12.0.0-chrome75)
- Node 12.6.0 + Chrome 77 [/node12.6.0-chrome77](node12.6.0-chrome77)
- [/node12.13.0-chrome78-ff70-brave78](node12.13.0-chrome78-ff70-brave78)
- Node 13.1.0 + Chrome 78 + Firefox 70 [node13.1.0-chrome78-ff70](node13.1.0-chrome78-ff70)
- Node 13.3.0 + Chrome 79 + Firefox 70 [node13.3.0-chrome79-ff70](node13.3.0-chrome79-ff70)

We only provide browsers for `Debian`, but you can use our base images and build your own. See Cypress [Docker documentation](https://on.cypress.io/docker).

## Tags

You can find all published image tags in the tables above or at [Docker Hub](https://hub.docker.com/r/cypress/browsers/tags/). We recommend using a full image tag, rather than `latest` for immutable builds.

```
# NOT RECOMMENDED
FROM cypress/browsers:latest

# Best practice
FROM cypress/browsers:node13.6.0-chrome80-ff72
```
