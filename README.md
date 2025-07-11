<img src="https://raw.githubusercontent.com/loopbackio/loopback.io/gh-pages/images/branding/logo/blue/loopback-sm.png" alt="LoopBack4 logo" width="400"/>

[![Continuous Integration Status](https://github.com/loopbackio/loopback-next/actions/workflows/continuous-integration.yml/badge.svg)](https://github.com/loopbackio/loopback-next/actions/workflows/continuous-integration.yml)
[![Coverage Status](https://coveralls.io/repos/github/loopbackio/loopback-next/badge.svg?branch=master)](https://coveralls.io/github/loopbackio/loopback-next?branch=master)
[![CodeQL Status](https://github.com/loopbackio/loopback-next/workflows/CodeQL/badge.svg)](https://github.com/loopbackio/loopback-next/actions?query=workflow%3ACodeQL)

[![Twitter](https://img.shields.io/twitter/follow/strongloop.svg?style=social&label=Follow%20%40strongloop)](https://twitter.com/strongloop)
[![LinkedIn](https://img.shields.io/badge/Follow%20us-white?logo=linkedIn&color=0077B5&logoColor=white)](https://www.linkedin.com/groups/5046525/)
[![Slack](https://img.shields.io/badge/slack-Join%20workspace-%234A154B?logo=slack)](https://join.slack.com/t/loopbackio/shared_invite/zt-8lbow73r-SKAKz61Vdao~_rGf91pcsw)

LoopBack makes it easy to build modern applications that require complex
integrations.

- Fast, small, powerful, extensible core
- Generate real APIs with a single command
- Define your data and endpoints with OpenAPI
- No maintenance of generated code

## Status: General Availability

LoopBack 4 GA (General Availability) has been released in October 2018, read
more in [the announcement post](http://strongloop.com/strongblog/loopback-4-ga).

The documentation website is https://loopback.io/doc/en/lb4/.

Learn about the latest and greatest
[features and technologies in LoopBack 4](https://loopback.io/doc/en/lb4/Crafting-LoopBack-4.html)
by using it for your next project. Start by having a look at
[Getting Started](https://loopback.io/doc/en/lb4/Getting-started.html).

Check the [API documentation](https://loopback.io/doc/en/lb4/apidocs.index.html)
for all the API usages in each package.

### Long Term Support

We don't provide any LTS version for LoopBack 4 yet. Please join the discussion
in [loopback-next#4398](https://github.com/loopbackio/loopback-next/issues/4398)
if you are interested in a version that's less frequently changed.

| Version    | Status      | Published | EOL                  |
| ---------- | ----------- | --------- | -------------------- |
| LoopBack 4 | Current     | Oct 2018  | Apr 2028 _(minimum)_ |
| LoopBack 3 | End-of-Life | Dec 2016  | Dec 2020             |
| LoopBack 2 | End-of-Life | Jul 2014  | Apr 2019             |

Please refer to our
[Long Term Support Policy](https://loopback.io/doc/en/contrib/Long-term-support.html)
for more details.

## Installation

Make sure you have the following installed:

| Package                                    | Version/-s                                                             | Link                                  | Note                                                                                                  |
| ------------------------------------------ | ---------------------------------------------------------------------- | ------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| [Node.js](https://nodejs.org/en/download/) | Maintenance LTS (_v20_) <br/> Active LTS (_v22_) <br/> Current (_v24_) | https://nodejs.org/en/about/releases/ | <span style="color: yellow;">The use of the current version for production is not recommended</span>. |

You can generate a project with our generator or with the CLI as follows:

```shell
npm create loopback
npx -p @loopback/cli lb app
```

To create your first LoopBack 4 application, see
[Getting Started](http://loopback.io/doc/en/lb4/Getting-started.html).

## Documentation

- [Official documentation](http://loopback.io/doc/en/lb4/)
- [API documentation](https://loopback.io/doc/en/lb4/apidocs.index.html)
- [FAQ](http://loopback.io/doc/en/lb4/FAQ.html)
- [LoopBack 3 vs LoopBack 4](http://loopback.io/doc/en/lb4/migration-overview.html)
- [Tutorials](http://loopback.io/doc/en/lb4/Tutorials.html)
- [Examples](http://loopback.io/doc/en/lb4/Examples.html)

## Contributing

See the following resources to get you started:

- [Contributing Guidelines](./docs/CONTRIBUTING.md)
- [Monorepo overview](./docs/site/MONOREPO.md)
- [Developing LoopBack](./docs/site/DEVELOPING.md)

You can join the team by posting a comment to
[issue #110](https://github.com/loopbackio/loopback-next/issues/110).

### Security

If you think you have discovered a new security issue with any LoopBack package,
**please do not report it on GitHub**. Instead, send an email to
[security@loopback.io](mailto:security@loopback.io) with a full description and
steps to reproduce.

See [SECURITY.md](SECURITY.md) for more details.

## Team

### Project Architect

|                  Raymond Feng                   |
| :---------------------------------------------: |
| [![raymondfeng]](http://github.com/raymondfeng) |

### Technical Steering Committee

|                  Raymond Feng                   |               Diana Lau               |                       Mario Estrada                        |               Rifa Achrinza                |              Francisco Buceta              |            Samarpan Bhattacharya             |
| :---------------------------------------------: | :-----------------------------------: | :--------------------------------------------------------: | :----------------------------------------: | :----------------------------------------: | :------------------------------------------: |
| [![raymondfeng]](http://github.com/raymondfeng) | [![dhmlau]](http://github.com/dhmlau) | [![marioestradarosa]](https://github.com/marioestradarosa) | [![achrinza]](https://github.com/achrinza) | [![frbuceta]](https://github.com/frbuceta) | [![samarpanB]](https://github.com/samarpanB) |

### Other Project Maintainers

|                 Nora Abdelgadir                  |               Matthew Schnee               |                    Hage Yaapa                    |
| :----------------------------------------------: | :----------------------------------------: | :----------------------------------------------: |
| [![nabdelgadir]](https://github.com/nabdelgadir) |  [![mschnee]](https://github.com/mschnee)  | [![hacksparrow]](https://github.com/hacksparrow) |
|                  **Agnes Lin**                   |                 **Madaky**                 |                 **Hugo Da Roit**                 |
|    [![agnes512]](https://github.com/agnes512)    |   [![madaky]](https://github.com/madaky)   |        [![yaty]](https://github.com/yaty)        |
|                  **Nico Flaig**                  |             **Denny Bartelt**              |             **Douglas McConnachie**              |
|      [![nflaig]](https://github.com/nflaig)      |  [![derdeka]](https://github.com/derdeka)  |    [![dougal83]](https://github.com/dougal83)    |
|            **Samarpan Bhattacharya**             |             **Muhammad Aaqil**             |                                                  |
|   [![samarpanB]](https://github.com/samarpanB)   | [![aaqilniz]](https://github.com/aaqilniz) |                                                  |

See
[all contributors](https://github.com/loopbackio/loopback-next/graphs/contributors).

### Alumni

- [@ritch](http://github.com/ritch)
- [@superkhau](https://github.com/superkhau)
- [@rashmihunt](https://github.com/rashmihunt)
- [@kjdelisle](https://github.com/kjdelisle)
- [@virkt25](https://github.com/virkt25)
- [@shimks](https://github.com/shimks)
- [@b-admike](https://github.com/b-admike)
- [@deepakrkris](https://github.com/deepakrkris)
- [@bajtos](http://github.com/bajtos)
- [@jannyhou](http://github.com/jannyHou)
- [@emonddr](https://github.com/emonddr)

## License

[MIT](LICENSE)

[raymondfeng]: https://avatars0.githubusercontent.com/u/540892?v=3&s=60
[ritch]: https://avatars2.githubusercontent.com/u/462228?v=3&s=60
[dhmlau]: https://avatars2.githubusercontent.com/u/25489897?v=3&s=60
[jannyhou]: https://avatars2.githubusercontent.com/u/12554153?v=3&s=60
[hacksparrow]: https://avatars2.githubusercontent.com/u/950112?v=3&s=60
[nabdelgadir]: https://avatars0.githubusercontent.com/u/42985749?v=3&s=60
[marioestradarosa]: https://avatars2.githubusercontent.com/u/4633823?v=3&s=60
[yaty]: https://avatars3.githubusercontent.com/u/11981803?v=3&s=60
[emonddr]: https://avatars0.githubusercontent.com/u/6864736??v=3&s=60
[agnes512]: https://avatars3.githubusercontent.com/u/50331796?v=3&s=60
[deepakrkris]: https://avatars0.githubusercontent.com/u/7688315?v=3&s=60
[derdeka]: https://avatars3.githubusercontent.com/u/13640166?v=3&s=60
[dougal83]: https://avatars0.githubusercontent.com/u/2735881?v=3&s=60
[achrinza]: https://avatars3.githubusercontent.com/u/25147899?v=3&s=60
[frbuceta]: https://avatars2.githubusercontent.com/u/13822438?v=4&s=60
[mschnee]: https://avatars0.githubusercontent.com/u/1375316?v=4&s=60
[madaky]: https://avatars3.githubusercontent.com/u/17172989?v=4&s=60
[nflaig]: https://avatars3.githubusercontent.com/u/38436224?v=4&s=60
[samarpanb]: https://avatars.githubusercontent.com/u/13620435?v=4&s=60
[aaqilniz]: https://avatars.githubusercontent.com/u/25802906?v=4&s=60
