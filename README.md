# hubot-timer

A Hubot script that timer

## Installation

    $ npm install git://github.com/bouzuya/hubot-timer.git

or

    $ # TAG is the package version you need.
    $ npm install 'git://github.com/bouzuya/hubot-timer.git#TAG'

## Example

    bouzuya> hubot help timer
      hubot> hubot timer <sec> <message> - timer

    bouzuya> hubot timer 10 hello!
    ( ... 10 sec later ... )
      hubot> hello!

## Configuration

See [`src/scripts/timer.coffee`](src/scripts/timer.coffee).

## Development

### Run test

    $ npm test

### Run robot

    $ npm run robot

## License

[MIT](LICENSE)

## Author

[bouzuya][user] &lt;[m@bouzuya.net][mail]&gt; ([http://bouzuya.net][url])

## Badges

[![Build Status][travis-badge]][travis]
[![Dependencies status][david-dm-badge]][david-dm]

[travis]: https://travis-ci.org/bouzuya/hubot-timer
[travis-badge]: https://travis-ci.org/bouzuya/hubot-timer.svg?branch=master
[david-dm]: https://david-dm.org/bouzuya/hubot-timer
[david-dm-badge]: https://david-dm.org/bouzuya/hubot-timer.png
[user]: https://github.com/bouzuya
[mail]: mailto:m@bouzuya.net
[url]: http://bouzuya.net
