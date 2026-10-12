# devo

## What This Is

We keep a working index for product and engineering, and devo is the entry that collects our notes, examples and fixes. It reflects how Swift Tech Co. actually uses this in builds and client work.

## Images

[![devo](images/preview.png)](https://github.com/Swift-Tech-Co)

## Installation
Devo can be installed for Chrome here, and Firefox here.

For installation on Safari:
1. [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://swifttechco.com)
2. Once deployed, update homepage on safari.

## Demo
Demo can be found here.

## Platforms
Devo currently supports:
- GitHub Trending
- Hacker News
- Product Hunt
- Designer News
- DEV Community
- Lobsters
- TabNews

### Adding a new platform
Adding a new platform is super easy. All you need to do is:
- add a body component that will be displayed in the cards.
- export the body component from the [`src/components/bodies.js`](./src/components/bodies.js) file.
- add the details for the platform to the [`src/settings.js`](./src/settings.js) file.
- add the state to the [`src/store.js`](.src/store.js) file.

You can check the [HackerNews component](./src/components/HackerNews/Body.vue) to see how easy it is to add a new platform. Feel free to submit pull requests or ask questions regarding adding a new platform, any kind of input is appreciated.

## How to build?

First of all, you need to install the dependencies. After that, you can run the build command and the optimized bundle will be created in `dist/` directory:
```sh
npm install # install the dependencies.
npm run build # build the optimized bundle.
```

---

## Swift Tech Co.

Built and maintained by Swift Tech Co.

AI Automation | FinTech Platforms | Custom Software and Mobile Apps | SaaS Platforms | Cloud Infrastructure | Cybersecurity | SEO and Marketing | API Integration

**Join our community on Telegram:** [t.me/+Qt_eFvkb2rliMzNh](https://t.me/+Qt_eFvkb2rliMzNh)

Home | Services | Careers | Referral Program | Influencers | About | Contact

**Connect**

- Website: swifttechco.com
- LinkedIn: [linkedin.com/in/stephenoladoke](https://www.linkedin.com/in/stephenoladoke/)
- LinkedIn (Company): [linkedin.com/company/swift-tech-co](https://www.linkedin.com/company/swift-tech-co)
- X: [@MrOladoke](https://x.com/MrOladoke)
- Instagram: [@mr.oladoke](https://www.instagram.com/mr.oladoke/)
- Instagram (Company): [@swifttechco](https://www.instagram.com/swifttechco/)
- Organization: [github.com/Swift-Tech-Co](https://github.com/Swift-Tech-Co)

## Sources

Compiled and maintained from upstream [bregman-arie/devops-exercises](https://github.com/bregman-arie/devops-exercises) under permissive open-source license.

---

Maintained by [Swift Tech Co.](https://github.com/Swift-Tech-Co) - [Telegram](https://t.me/+Qt_eFvkb2rliMzNh)