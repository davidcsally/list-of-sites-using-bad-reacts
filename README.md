# list-of-sites-using-bad-reacts
A running list of websites I have seen using old or non production react builds. Detected using the React Developer Tools extension for Chrome

* Non production: Unminified build of React, most likely not setting NODE_ENV=production
* Outdated: React version <= 15.0 ([I think... ](https://github.com/facebook/react-devtools/blob/2f05848dc8c68d939b3f9077f876650cf48e1874/backend/installGlobalHook.js#L112))

### Non production builds
| Company | Website | Issue | Date Checked |
|---------|---------|-------|--------------|
| AppAcademy | https://www.appacademy.io/ | Non Production | 6/20/2018 |
| Avvo | https://www.avvo.com/ | Non Production | 6/6/2018 |
| AWS console | https://us-east-2.console.aws.amazon.com/console/home | Non Production | 6/19/2018 |
| Clash of the Clans | https://clashofclans.com/ | Non Production | 6/19/2018 |
| Fullstack Academy | https://www.fullstackacademy.com/ | Non Production | 6/20/2018 |
| Mattermark |https://mattermark.com/ | Non Production | 6/6/2018 |
| JustWorks (logged in) | https://secure.justworks.com/ | Non Production | 6/19/2018 |
| Rotten Tomatoes | https://www.rottentomatoes.com/ | Non Production | 6/19/2018 |

### Outdated versions
| Company | Website | Issue | Date Checked |
|---------|---------|-------|--------------|
| Arbor Bridge | https://www.arborbridge.com/ | Outdated | 6/19/2018 |
| Bloc | https://www.bloc.io/learn-to-code/ | Outdated | 6/20/2018 |
| Flipboard | https://flipboard.com/ | Outdated | 6/19/2018 |
| Grailed | https://www.grailed.com/ | Outdated | 6/7/2018 |
| IMDB | https://www.imdb.com/title/tt3778644/ | Outdated | 6/19/2018 |
| JustWorks (landing page) | https://justworks.com/ | Outdated | 6/19/2018 |
| Mr. Porter | https://www.mrporter.com/ | Outdated | 6/7/2018 |
| The New York Times | https://www.nytimes.com/ | Outdated | 6/19/2018 |
| Nudie Jeans | https://www.nudiejeans.com/ | Outdated | 6/7/2018 |
| Scribd | https://www.scribd.com/ | Outdated | 6/6/2018 |

Special shout outs:
  * JustWorks uses an outdated version for their sign up page, but their main application uses an unminified version.
  * Both AppAcademy and Fullstack Academy teach React, but use non production builds.
