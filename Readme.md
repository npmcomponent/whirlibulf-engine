*This repository is a mirror of the [component](http://component.io) module [whirlibulf/engine](http://github.com/whirlibulf/engine). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/whirlibulf-engine`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# whirlibulf

Website: http://whirlibulf.com

## Requirements

* [Node.js](http://nodejs.org) (Required by component)
* [Component](https://github.com/component/component) (Required for installing packages and building)


## Installation

    $ component install whirlibulf/engine


## Introduction

Whirlibulf is an **Entity-Component-System** Javascript game engine.

On its own, it provides only very basic functionality, and is not very useful for developing a game.

The engine depends on external packages called **Systems** and **Components** to provide the tools to develop a game.

Here's some reading material if you haven't encountered the Entity-Component-System design before:

* http://t-machine.org/index.php/2007/11/11/entity-systems-are-the-future-of-mmog-development-part-2/
* http://gamedev.stackexchange.com/questions/31473/role-of-systems-in-entity-systems-architecture/31491#31491

See the [whirlibulf website](http://whirlibulf.com) for documentation.

## Features

* Low-garbage - regularly tested for memory performance
* Lightweight - less than 500 lines of engine code
* Data-oriented - easy to edit and use
* Pooled components - re-use component instances
* Indexed entities - index entities according to their components

## Examples

See a simple pong game implemented with whirlibulf: https://github.com/whirlibulf/pong

## License

  MIT
