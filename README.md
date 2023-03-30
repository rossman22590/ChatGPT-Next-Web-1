<div align="center">
<img src="./static/icon.svg" alt="预览"/>

<h1 align="center">ChatGPT Next Web</h1>

One-click free deployment of your private ChatGPT web application.

One-Click to deploy your own ChatGPT web UI.

[演示 Demo](https://chat-gpt-next-web.vercel.app/) / [反馈 Issues](https://github.com/Yidadaa/ChatGPT-Next-Web/issues) / [加入 Discord](https:/ /discord.gg/zrhvHCr79N) / [QQ 群](https://user-images.githubusercontent.com/16968934/228190818-7dd00845-e9b9-4363-97e5-44c507ac76da.jpeg) / [打赏开发者](https://user-images.githubusercontent.com/16968934/227772541-5bcd52d8-61b7-488c-a203-0330d8006e2b.jpg) / [Donate](#捐赠- donate-usdt)

[! [Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FYidadaa% 2FChatGPT-Next-Web&env=OPENAI_API_KEY&env=CODE&project-name=chatgpt-next-web&repository-name=ChatGPT-Next-Web)

[! [Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/Yidadaa/ChatGPT-Next-Web)

! [主界面](./static/cover.png)

</div>

## The main function

- Use Vercel in 1 minute **Free One-Click Deployment**
- Well-designed UI, responsive design, dark color mode support
- Extremely fast first screen load speed (~85kb)
- Massive built-in prompt list from [Chinese](https://github.com/PlexPt/awesome-chatgpt-prompts-zh) and [English](https://github.com/f/awesome-chatgpt-prompts)
- Automatic compression of contextual chat logs to support extra-long conversations while saving Token
- One-click export of chat logs with full Markdown support
- Have your own domain name? Well, it's even better, so you can bind it for fast access from anywhere **without any hassles**.

## Features

- **Deploy for free with one-click** on Vercel in under 1 minute
- Responsive design, and dark mode
- Fast first screen loading speed (~85kb)
- Awesome prompts powered by [awesome-chatgpt-prompts-zh](https://github.com/PlexPt/awesome-chatgpt-prompts-zh) and [awesome-chatgpt- prompts](https://github.com/f/awesome-chatgpt-prompts)
- Automatically compresses chat history to support long conversations while also saving your tokens
- One-click export all chat history with full Markdown support

## Usage

1.Have your [OpenAI API Key](https://platform.openai.com/account/api-keys) ready.
2.Click the button on the right to start deploying:
   [! [Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FYidadaa%) 2FChatGPT-Next-Web&env=OPENAI_API_KEY&env=CODE&project-name=chatgpt-next-web&repository-name=ChatGPT-Next-Web), directly use Github account to log in, remember fill in the API Key in the environment variables page;
3.once deployed, you can start using it;
4.(Optional) [Bind custom domain name](https://vercel.com/docs/concepts/projects/domains/add-a-domain): Vercel assigned domain name DNS is polluted in some areas, bind custom domain name to connect directly.

## Get Started

1.Get [OpenAI API Key](https://platform.openai.com/account/api-keys).2.
2.Click
   [! [Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FYidadaa%) 2FChatGPT-Next-Web&env=OPENAI_API_KEY&env=CODE&project-name=chatgpt-next-web&repository-name=ChatGPT-Next-Web).
3.enjoy :)

## Keep Updated

If you have followed the above steps to deploy your project with one click, you may find that you are always prompted with "There is an update", because Vercel will create a new project for you by default instead of fork this project, which will not detect updates correctly.
We recommend that you follow these steps to redeploy:

- Delete the original repo;
- fork this project;
- Go to the vercel console, delete the original project, then create a new project and select the project you just forked to redeploy it;
- During the redeployment process, please manually add an environment variable named `OPENAI_API_KEY` and fill in your api key as the value.

This project will be continuously updated, if you want to keep the codebase always up to date, you can check [Github's documentation](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with- forks/syncing-a-fork) to learn how to synchronize fork projects with upstream code, and it is recommended that you do this periodically to get new features.

You can star/watch the project or follow the author to be notified of new features.

If you have deployed your own project with just one click following the steps above, you may encounter the issue of "Updates Available" constantly showing This is because Vercel will create a new project for you by default instead of forking this project, resulting in the inability to detect updates correctly.

We recommend that you follow the steps below to re-deploy.

- Delete the original repo.
- Fork this project.
- Go to the Vercel dashboard, delete the original project, then create a new project and select the project you just forked to redeploy.
- Please manually add an environment variable named `OPENAI_API_KEY` and enter your API key as the value during the redeploy process.

This project will be continuously maintained.If you want to keep the code repository up to date, you can check out the [Github documentation](https:// docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork) to learn how to synchronize a forked It is recommended to perform synchronization operations regularly.

You can star or watch this project or follow author to get release notifictions in time.

## Configure password Password

This project provides limited access control, please add an environment variable named `CODE` to the environment variables page of the Vercel project control panel with a custom password separated by commas:

```
code1,code2,code3
```

After adding or modifying this environment variable, please **redeploy** the project to make the changes take effect.

This project provides limited access control.Please add an environment variable named `CODE` on the vercel environment variables page.should be passwords separated by comma like this.

```
code1,code2,code3
```

After adding or modifying this environment variable, please redeploy the project for the changes to take effect.

## Environment Variables

### ``OPENAI_API_KEY`` (required)

OpanAI key.

Your openai api key.

### `CODE` (optional)
Access passphrase, optional, multiple passwords can be separated by comma.

Access passsword, separated by comma.

### `BASE_URL` (optional)

> Default: `api.openai.com`

OpenAI interface proxy URL.

Override openai api request base url.

### `PROTOCOL` (optional)

> Default: `https`

> Values: `http` | `https`

OpenAI interface protocol.

Override openai api request protocol.

## Development Development

Click the following button to start secondary development:

[! [Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/Yidadaa/ChatGPT-Next-Web)

Before you start writing code, you need to create a new `.env.local` file in the project root directory and fill in the environment variables:

Before starting development, you must create a new `.env.local` file at project root, and place your api key into it.

```
OPENAI_API_KEY=<your api key here>
```

### Local Development Local Development

> If you are a mainland China user, it is not recommended to develop locally unless you can solve the OpenAI API local proxy problem independently.

1.install nodejs and yarn, please ask ChatGPT for details;
2.Run `yarn install && yarn dev` and you're done.

### Local Deployment

```shell
bash <(curl -s https://raw.githubusercontent.com/Yidadaa/ChatGPT-Next-Web/main/scripts/setup.sh)
```

### Container Deployment Docker Deployment

```shell
docker pull yidadaa/chatgpt-next-web

docker run -d -p 3000:3000 -e OPENAI_API_KEY="" -e CODE="" yidadaa/chatgpt-next-web
```

## Screenshot Screenshots

![设置 Settings](./static/settings.png)

![更多展示 More](./static/more.png)


## Donate USDT
> BNB Smart Chain (BEP 20)
```
0x67cD02c7EB62641De576a1fA3EdB32eA0c3ffD89
```

## Acknowledgements Special Thanks

### Donors Sponsor

[@mushan0x0](https://github.com/mushan0x0)
[@ClarenceDan](https://github.com/ClarenceDan)
[@zhangjia](https://github.com/zhangjia)
[@hoochanlon](https://github.com/hoochanlon)

### Contributors Contributor

[Contributors](https://github.com/Yidadaa/ChatGPT-Next-Web/graphs/contributors)

## LICENSE

- [Anti 996 License](https://github.com/kattgu7/Anti-996-License/blob/master/LICENSE_CN_EN)
