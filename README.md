# flyff-ranking-scraper
A simple web scraper for the [Official Flyff Universe Ranking](https://universe.flyff.com/sniegu/ranking/characters), which is used in a very similiar way in my project [SiegeStats](https://siegestats.cc) to get extra player data. This webscraper is based upon Puppeteer, which may be overkill. I may replace the usage of Puppeteer with simple HTTP-WebRequests later on.

## Context
[Flyff Universe](https://universe.flyff.com/) is a MMORPG released in 2004 with a fairly active community for its age. It provides a public ranking website, ranking the different ingame characters by their level and providing further data about the characters, such as name, sex, job/class, job-/classrank, guild and the overall playtime.


## Usage
Simply clone the project and install the dependencies (`npm install`). Once you did so, specify the servers to scrape in [index.ts](/src/index.ts#L8C65-L8C65).  
Build the project and run it using `npm run run-ts` or `npx tsc && node ./build/index.js`