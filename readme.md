[中文](./readme-zh.md)
<h1 align="center">Screenshot to Page</h1>

> **Turn screenshots, image links, or sketches into code with PT-4 Vision and convert them into web pages, with support for one-click deployment to the cloud ☁️**.

+ [Online address](https://screenshot-to-page.vercel.app/) (You don't need to fill in anything to experience it).

+ PC

<img src="https://cdn.glitch.global/fd139a45-4a65-41b6-9634-41617ab20cdc/1d77437e-2cbd-4329-8228-1da3ec04190a.image.png?v=1703246640297" width="40%" align="center" /><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;➡️&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img src="https://cdn.glitch.global/fd139a45-4a65-41b6-9634-41617ab20cdc/9335be07-579b-4a10-bc2b-bbccd8269f92.image.png?v=1703246494577" width="40%" align="center" />
+ Mobile

<img src="https://cdn.glitch.global/fd139a45-4a65-41b6-9634-41617ab20cdc/267ca2d1-b7e6-42ab-8713-7c22fd829747.image.png?v=1703214760406" width="30%" align="center"/><span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;➡️&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><img src="https://cdn.glitch.global/fd139a45-4a65-41b6-9634-41617ab20cdc/27148080-fb45-420d-835b-0f5edf978a40.image.png?v=1703214823811" width="30%" align="center"/>

## Milestones 🌊

+ Completely restructured using Next.js, supporting simple deployment on multiple cloud platforms.

+ 2023/12/28 📅: Added support for multiple themes and i18n.

+ 2023/12/31 📅: support googol Gemini (free).
	
## Distinctions 🏄🏿‍♂️
+ Better suited for developers familiar with the js/ts tech stack to get started quickly.
+ Free serverless cloud platform deployment.
+ Support for Excalidraw sketches.
+ Support googol Gemini (free).

## Plans 🌄
+ Implement a code sandbox to support modern, engineered coding practices (coming very soon, the codebase is almost complete).
+ Implement partial update features, similar to V0.
+ ~~I18n~~
+ ~~Support googol Gemini~~.

## Deployment 🪤
### Docker
```sh
docker run -p  3000:3000 jadenxiong/screenshot-to-page
```
### Vercel
+ Click the button on the right to start deployment: ![Deploy with Vercel](https://vercel.com/button)
+ Once deployed, you can start using it;
+ (Optional) [Bind a custom domain](https://vercel.com/docs/concepts/projects/domains/add-a-domain): The DNS of the domain assigned by Vercel is polluted in some regions, binding a custom domain will allow direct connection.
 
## Developers 💪
```sh
# pnpm
pnpm i;
pnpm dev;
```
```sh
# yarn
yarn;
yarn dev;
```

## Acknowledgements 🙏
+ Original repository: [screenshot-to-code](https://github.com/abi/screenshot-to-code/blob/main/README.md) 
+ Forked repository: [ant-codeAI](https://github.com/sparrow-js/ant-codeAI)

## Related 🌲
+ [local-mk-editor-in-browser](https://github.com/Mrxyy/local-mk-editor-in-browser) 👷
+ [chat-query](https://github.com/Mrxyy/chat-query.git) 📖 
