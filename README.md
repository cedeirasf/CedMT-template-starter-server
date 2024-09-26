# starter-server-template

<h4 align="center">A minimal and flexible template to quickly deploy a simple server using Docker Compose</h4>

&nbsp;

<div align="center">

<a href="./LICENSE">
	<img alt="License: MIT" src="https://img.shields.io/badge/License-Private-yellow.svg">
</a>
<a href="./CODE_OF_CONDUCT.md">
	<img alt="Contributor covenant: 2.1" src="https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg">
</a>
<a href="https://semver.org/">
	<img alt="Semantic Versioning: 2.0.0" src="https://img.shields.io/badge/Semantic--Versioning-2.0.0-a05f79?logo=semantic-release&logoColor=f97ff0">
</a>

<a href="./issues/new?assignees=&labels=fix&projects=&template=bug_report.md&title=">Report Bug</a>
·
<a href="./issues/new?assignees=&labels=proposal&projects=&template=proposal-feature.md&title=As+a+%5Brole%5D%2C+I+want+to+%5Baction%5D%2C+so+that+%5Bbenefit%5D">Request Feature</a>
·
<a href="https://github.com/mauroalderete/starter-server-template/issues/new?assignees=&labels=question&projects=&template=question.md&title=">Question</a>

<a href="https://x.com/intent/post?text=👋%20Check%20this%20amazing%20repo%20https://github.com/mauroalderete/starter-server-template,%20created%20by%20@_mauroalderete%0A%0A%23DEVCommunity%20%23100DaysOfCode%20%23DevOps%20%23Server">
	<img src="https://img.shields.io/twitter/url?label=Share%20on%20Twitter&style=social&url=https%3A%2F%2Fgithub.com%2Fatapas%2Fmodel-repo">
</a>

</div>

&nbsp;
# :wave: Introducing starter-server-template
A minimal and flexible template to quickly deploy a simple server using Docker Compose. This template includes essential components to set up and manage a lightweight server for various machines, such as Raspberry Pi, personal computers, or other servers in your network

**🎊 Use this template as a starting point for creating personalized server configurations across your network with ease 🎊**

Features:

- `Nginx` as a reverse proxy for handling incoming requests.
- [gethomepage/homepage](https://github.com/gethomepage/homepage) for a customizable landing page.
- Docker discovery service to easily find and manage Docker containers across machines.
- Devcontainer setup for seamless development and containerized environment.

> [!NOTE]
> We appreciate the great effort they put into [gethomepage/homepage](https://github.com/gethomepage/homepage). Don't forget to visit their repository to learn how to configure your homepage and leave your ⭐ in the process.

# :fire: How to use this template

To use this template, click the button **Use this template** shown in the upper section on [root of repository](https://github.com/mauroalderete/starter-server-template), then create a new repository.

Another way is initing the process of creating a new repository and selecting this template in the upper section.

# :building_construction: How to Set up

This template contains many files that you would probably like to know how to configure...

> [!WARNING]
> This section is Work In Progress

## Code of conduct

`/CODE_OF_CONDUCT.md`

This code is based on the covenant code. He is only required to specify an email address to the community to send his messages. Now, this email is alderete.mauro@gmail.com.

## License

`/LICENSE`

This license is a private personal license redacted by chatGPT. This is only an example. I recommend changing this license to other than to be attached better to your needs.
You can replace it with any Open License offered by GitHub, too.

## Versioning

`/.github/workflows/versioning.yml`

The versioning workflow contains the commands to generate a new release. This release could be attached with a binary file result from them of your project's build.

The file shows you a simple build step and package.

## Gitignore

`/.gitignore`

This file is empty. Replace the content with what you think is more convenient.

## Others

This template uses [nginx](https://nginx.org/en/), [devcontainer](https://containers.dev/), and [gethomepage/homepage](https://github.com/gethomepage/homepage) to easily setup a minimal server... feel free to check out how to configure each component by visiting their documentation sections.
