---
id: design-principles
title: Design Principles
---

_This section is a work in progress._

- Easy to learn but most things are still achievable by users, even if it takes them more code and more time to write. Not having abstractions is better than having the wrong abstractions, and we don't want users to have to hack around the wrong abstractions. Mandatory talk - [Minimal API Surface Area](https://www.youtube.com/watch?v=4anAwXYqLG8)
- Intuitive project structure - users will not feel overwhelmed when looking at the project directory of a Docusaurus project. It should look intuitive and easy to build on top of.
- The separations of concerns between each layer of our stack (content/theming/styling) should be clear - well-abstracted and modular.
- Sensible defaults - Common and popular performance optimizations and configurations will be done for users but they are given the option to override them.
- No vendor-lock in - Users are not required to use the default plugins or CSS, although they are highly encouraged to. Certain lower-level infra level stuff like React Loadable, React Router are fine, but not higher level ones, such as choice of Markdown engines, CSS frameworks, CSS methodology.

## How Docusaurus Works

<!-- moved in from how Docusaurus works @yangshun -->

We believe that as devlopers, knowing how a library works is helpful in allowing us to become better at using it. Hence we're dedicating effort into explaining the architecture and various components of Docusaurus with the hope that users reading it will gain a deeper understanding of the tool and be even more proficient in using it.

<!--

Explain the principles that guide the development of Docusaurus.

References
---
- https://www.gatsbyjs.org/docs/behind-the-scenes/
- https://reactjs.org/docs/design-principles.html
- https://v1.vuepress.vuejs.org/miscellaneous/design-concepts.html

-->
