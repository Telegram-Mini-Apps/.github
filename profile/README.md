# Telegram Mini Apps

This GitHub organization aims at improving the developer experience for the Telegram Mini Apps platform. 
It provides complete documentation, templates, and a wide range of packages for various programming languages.

## Motivation

### Single source

One of the purposes of this organization is to provide a single source of information for the platform, 
significantly decreasing the barrier for entry. Telegram's documentation can sometimes be difficult to 
research and find the specific information that developers need. This is the reason why community needs
this kind of organization.

### Public development

The other idea behind the organization is to make platform development public. Developers would like to
see what is going on behind the scenes or at least know what is going to be implemented in near future.
This is rather rare feature for big companies, but we believe that Telegram is able to help with this.

Everything provided by the organization is the result of hard work and is available for free to everyone.

## Useful Links

- Learn more about packages and platform - [documentation](https://docs.telegram-mini-apps.com)
- Report a bug or suggest a platform enhancement - [repository](https://github.com/Telegram-Mini-Apps/issues)
- Join public developers discussions - [Telegram chat](https://t.me/devs)

## Boilerplates

### [@telegram-mini-apps](https://github.com/telegram-mini-apps)

Boilerplates mentioned in this section are `@tma.js`-based. They don't use the SDK provided by Telegram,
but it's better alternative.

All boilerplates in this section also utilize such frontend tool as [Vite](https://vitejs.dev/). This 
bundler is recognized as a good alternative for such technology as [Webpack](https://webpack.js.org/).

#### [vanillajs-template](https://github.com/Telegram-Mini-Apps/vanillajs-template)

Boilerplate using pure JavaScript and [@tma.js/sdk](https://www.npmjs.com/package/@tma.js/sdk) package 
presented as an IIFE module.

> ⚠️ Using IIFE modules is considered as non-effective. It is recommended to use bundlers along with ES6
> modules. As the alternative, you could use [typescript-template](https://github.com/Telegram-Mini-Apps/typescript-template).

#### [typescript-template](https://github.com/Telegram-Mini-Apps/typescript-template)

Boilerplate using TypeScript and [@tma.js/sdk](https://www.npmjs.com/package/@tma.js/sdk).

### [@telegram-mini-apps-dev](https://github.com/telegram-mini-apps-dev)

Boilerplates mentioned in this section use the SDK provided by Telegram.

#### [vanilla-js-boilerplate](https://github.com/Telegram-Mini-Apps-Dev/vanilla-js-boilerplate)

Basic and straightforward boilerplate based on simple web technologies: JavaScript, HTML, and CSS. This
project aims to provide a minimalistic example of how to create a simple Telegram Mini App and launch it
within Telegram without relying on complex build tools or bleeding-edge libraries.

#### [vite-boilerplate](https://github.com/Telegram-Mini-Apps-Dev/vite-boilerplate)

[Vite](https://vitejs.dev/) is a modern frontend tool that offers several advantages over traditional build
tools, including faster development times, smaller bundle sizes, and improved developer experience. It
supports React, Vue, Svelte and many more. This example based on:
- React
- TypeScript
- Deploy with GitHub Actions and GitHub Pages

## [Figma](https://www.figma.com/file/AwAi6qE11mQllHa1sOROYp/Telegram-Mini-Apps-Library?type=design&node-id=26%3A1081&mode=design&t=Sck9CgzgyKz3iIFt-1)

Design component library in Figma, which will make it easier for designers to design apps for Telegram 
Mini Apps. The components fully mimic the Telegram interface, use it as a foundation, and inherit all 
existing principles. Libraries are available iOS, Android and other platforms.

## Communication

If you have any questions or suggestions about the particular tool, you are welcome to create an Issue or Pull
Request. In case of any other questions, you can join our [Telegram chat](https://t.me/devs).
