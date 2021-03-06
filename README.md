<h1 align="center">GitLab Roadmap</h1>

<p align="center">
<a href="https://github.com/eventOneHQ/gitlab-roadmap/blob/master/LICENSE"><img src="https://img.shields.io/github/license/eventOneHQ/gitlab-roadmap.svg" alt="GitHub license"></a>
<a href="https://travis-ci.com/eventOneHQ/gitlab-roadmap"><img src="https://travis-ci.com/eventOneHQ/gitlab-roadmap.svg?branch=develop" alt="Build Status"></a>
<a href="http://commitizen.github.io/cz-cli/"><img src="https://img.shields.io/badge/commitizen-friendly-brightgreen.svg" alt="Commitizen friendly"></a>
<a href="https://standardjs.com"><img src="https://img.shields.io/badge/code_style-standard-brightgreen.svg" alt="JavaScript Style Guide"></a>
<a href="https://github.com/semantic-release/semantic-release"><img src="https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg" alt="semantic-release"></a>

</p>
<p align="center"><b>📢 Create a product roadmap website with GitLab Issue Boards as a backend!</b></p>

## Setup

### Quick Start (Heroku)

Click the button below to deploy on Heroku!

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/eventOneHQ/gitlab-roadmap)

### Development Setup

Want to contribute? Awesome! First checkout the [contribution guidelines](#contributing) then follow these steps to get setup.

Clone the repository

```
$ git clone https://github.com/eventOneHQ/gitlab-roadmap
```

Install the dependencies

```
$ npm install
```

Copy `example.env` to `.env` and edit it to your liking

```
$ cp example.env .env
```

Start the dev server

```
$ npm run dev
```

## Embed
Replace `localhost:3000` with your URL.
```html
<div id="glrm-widget"></div>
<script>
(function (w,d,s,o,f,js,fjs) {
    w['GLRM_Widget']=o;w[o] = w[o] || function () { (w[o].q = w[o].q || []).push(arguments) };
    js = d.createElement(s), fjs = d.getElementsByTagName(s)[0];
    js.id = o; js.src = f; js.async = 1; fjs.parentNode.insertBefore(js, fjs);
}(window, document, 'script', 'glrm', '//localhost:3000/widget.js'));
glrm("init", { widgetRef: "glrm-widget" });
</script>
```

## Contributing

Please read [CONTRIBUTING.md](https://github.com/eventOneHQ/gitlab-roadmap/blob/develop/CONTRIBUTING.md) for details on our [code of conduct](https://github.com/eventOneHQ/gitlab-roadmap/blob/develop/CODE_OF_CONDUCT.md), and the process for submitting pull requests to us.

## Versioning

We use [semantic-release](https://github.com/semantic-release/semantic-release) for versioning. Every commit to `master` will generate a release. For the versions available, see the [releases on the repositories](https://github.com/eventOneHQ/gitlab-roadmap/releases).

## Credits

- **Noah Prail** - _Project Lead_ - [@nprail](https://github.com/nprail)

See also the list of [contributors](https://github.com/eventOneHQ/gitlab-roadmap/contributors) who participated in this project.

## License

[MIT](https://github.com/eventOneHQ/gitlab-roadmap/blob/develop/LICENSE)
