# Telegram Web Apps

Community of developers which are excited to create new applications on Telegram
Web Apps platform.

The main our goal is to create useful, simple and intuitive functionality which
will be comfortable to use while developing Web Apps applications. Additionally,
to make platform research better, we provide documentation for all Web Apps
components with examples. So, deep dive into Web Apps becomes really easy.

## Projects

### [documentation](https://github.com/Telegram-Web-Apps/documentation)

Best point to start learning Web Apps platform from. Provides information about
whole platform, its concepts, opportunities and much more.

### [core](https://github.com/Telegram-Web-Apps/core) <sup><img src="./static/ts.svg" alt="ts" width="16"/></sup>

Web Apps core TypeScript utilities, which are reused in other packages of
ecosystem. You probably don't need to use this package directly, but this will
be useful to know, how other libraries use internally, as long as they use this
package.

### [client-sdk](https://github.com/Telegram-Web-Apps/client-sdk) <sup><img src="./static/ts.svg" alt="ts" width="16"/></sup>

Dead-simple, tree-shakeable, side-effects free, made from scratch TypeScript
library for communication with Telegram Web Apps functionality. Code of this
library was written with aim to make developers communication with Telegram way
easier. It contains a lot of separate components which are responsible for their
own part of Telegram Web Apps ecosystem.

### [init-data-ts](https://github.com/Telegram-Web-Apps/init-data-ts) <sup><img src="./static/ts.svg" alt="ts" width="16"/></sup>

TypeScript isomorphic library to make work with Telegram Web Apps init data
easier. This library includes functions to verify and parse init data sent from
client side of application. 

Used by [client-sdk](https://github.com/Telegram-Web-Apps/client-sdk).

### [init-data-golang](https://github.com/Telegram-Web-Apps/init-data-golang) <sup><img src="./static/go.svg" alt="go" width="16"/></sup>

This library is the same
as [init-data-ts](https://github.com/Telegram-Web-Apps/init-data-ts), but made
with Golang.

### [theme-params](https://github.com/Telegram-Web-Apps/theme-params) <sup><img src="./static/ts.svg" alt="ts" width="16"/></sup>

Web Apps theme parameters specialized repository. Contains ready to use JS
scripts and set of TS utils which are commonly used in projects.

Used by [client-sdk](https://github.com/Telegram-Web-Apps/client-sdk).

## Contribution

Any participation in life of organisation is appreciated. In case, you found a
bug in some library or want new feature to be implemented, please create an
issue in its GitHub repository.

Found Web Apps platform bug or want new platform functionality to be made?
Create
issue [here](https://github.com/Telegram-Web-Apps/client-sdk/issues/new/choose). 