<p align="center">
	<a href="http://standardjs.com">
		<img src="https://img.shields.io/badge/code%20style-standard-brightgreen.svg" alt="StandardJS">
	</a>
	<a href="https://git.io/col">
		<img src="https://img.shields.io/badge/%E2%9C%93-collaborative_etiquette-brightgreen.svg" alt="Collaborative Etiquette">
	</a>
	<a href="https://discord.gg/bBpQHym">
		<img src="https://img.shields.io/discord/447118387118735380.svg?logo=discord" alt="chat on Discord">
	</a>
	<a href="https://twitter.com/intent/follow?screen_name=eoscostarica">
		<img src="https://img.shields.io/twitter/follow/eoscostarica.svg?style=social&logo=twitter" alt="follow on Twitter">
	</a>
	<a href="#">
		<img src="https://img.shields.io/dub/l/vibe-d.svg" alt="MIT">
	</a>
</p>

<p align="center">
	<a href="https://eoscostarica.io">
		<img src="https://github.com/eoscostarica/assets/blob/master/eoscolors-transparent.png" width="300">
	</a>
</p>

# dmeetup

Decentralized Version of Meetup with Token Incentives for the Community Members.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->

<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

## Contents

* [Getting Started](#getting-started)
* [Contributing](#contributing)
* [Bug Reporting](#bug-reporting)
* [Features](#features)
  * [Phase 1](#phase-1)
  * [Phase 2](#phase-2)
* [Technology](#technology)
  * [Why EOS ?](#why-eos-)
  * [EOS.io Application Stack](#eosio-application-stack)
  * [Building EOS DApps](#building-eos-dapps)
  * [EOS Documentation](#eos-documentation)
  * [EOS Storage](#eos-storage)
  * [IPFS Documentation](#ipfs-documentation)
  * [React Documentation](#react-documentation)
  * [About EOS Costa Rica](#about-eos-costa-rica)
  * [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Getting Started

dmeetup is an EOS based application that allows people to publish meetup events and workshops, you will be able to build a reputation and get rewarded in crypto, as well as allowing to charge in crypto for your workshops. We envision the rep system as something similar to steemit. When this is ready we would like to perform an AirDrop on the EOS blockchain.

It is a 100% open-source and community-driven project and we welcome contributions of all sorts. There are many ways to help, from reporting issues, contributing code, and helping us improve our community.

The main communication channels for organizing and collaborating are this repository and the [EOS Costa Rica Discord server](https://discord.gg/bBpQHym). Feel to join and ask as many questions you may have.

The project lead is [@gaboesquivel](https://github.com/gaboesquivel).

## Contributing

Read the [contributing guidelines](CONTRIBUTING.md) for details.

There a many reasons to get involved in an open source project like this one. If haven't participated in an open source project before and you are still not sure whether you should, this is presentation is for you. [eoscostarica-oss.pdf](https://gaboesquivel.com/slides/eoscostarica-oss.pdf)

## Bug Reporting

Please report bugs big and small by [opening an issue](issues/new). No possible bug report is too small.

## Features

### Phase 1

* Accounts
* User posts a meetup event and tags it
* User makes a reservation to the meetup event
* User votes up the meetup ( reputation )
* Events feed with filters

### Phase 2

* User pays to rsvp the meetup
* Token rewards for the speakers/organizers

# Technology

* EOS
* IPFS
* React.js
* Docker for the dev environment

## Why EOS ?

[![Why EOS](https://monosnap.com/image/CDcIfufeYs0rJPH2viNkCJSPV6bY4O.png)](https://www.youtube.com/watch?v=3kqkTYqTvDA)

![EOS Network](https://github.com/eoscostarica/dmeetup/blob/master/docs/img/eos-network.jpg)

## EOS.io Application Stack

![](https://github.com/eoscostarica/dmeetup/blob/master/docs/img/eos-application-stack.png)  
source https://steemit.com/eos/@eosio/introducing-eos-io-application-stack

## Building EOS DApps

* [Webinar: Building Distributed Apps With EOS.IO Blockchain](https://objectcomputing.com/resources/events/webinars/building-apps-with-eos/webinar-recording)

## EOS Documentation

* Install Gollum and run the wiki locally (MacOS).

```
brew install rbenv ## https://github.com/rbenv/rbenv/
git clone https://github.com/EOSIO/eos.wiki.git
rbenv global/local 2.5.1
gem install gollum rdiscount --no-ri --no-rdoc
gollum
```

* https://github.com/EOSIO/eos/wiki

## EOS Storage

* [5 Reasons Why EOS Storage Will Change Data Storage Forever](https://www.youtube.com/watch?v=7mFzb5SqS9U)
* [EOS.IO Storage White Paper](https://steemit.com/eos/@eosio/eos-io-storage-white-paper-now-available)

## IPFS Documentation

* [github.com/ipfs/ipfs#how-ipfs-works](https://github.com/ipfs/ipfs#how-ipfs-works)
* [beta.docs.ipfs.io](https://beta.docs.ipfs.io)

## React Documentation

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

[docs/create-react-app.md](docs/create-react-app.md)

## About EOS Costa Rica

EOS Blockchain is aiming to become a decentralized operating system which can support large-scale decentralized applications.

EOS Costa Rica supports the global and local open source efforts and development communities by maintaining and contribute to open source initiatives, meetups and workshops.

We challenge ourselves to provide the EOS platform with a strong geographical and political diversity by running the most robust EOS Block Producer possible from Costa Rica; We pledge to leverage our talent, experience, and sustainable internet resources to meet such an important challenge.

[eoscostarica.com](https://eoscostarica.com)

## License

MIT © [EOS Costa Rica](https://eoscostarica.com)  
See LICENSE for more info
