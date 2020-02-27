![image](https://i.loli.net/2020/02/27/9julX8RSnOBtf74.png)

<h1>👓 Dummy Page for ICP censorship</h1>

<h6>A dummy static website for you to serve in case Aliyun warns you about missing ICP banners.</h6>

<h2>Table of contents</h2>

- [Deployment](#deployment)
  - [Docker](#docker)
  - [Direct deployment](#direct-deployment)
    - [Install dependencies](#install-dependencies)
    - [Deploy to Nginx's default web root](#deploy-to-nginxs-default-web-root)
- [Further development](#further-development)
  - [Compiles and hot-reloads for development](#compiles-and-hot-reloads-for-development)
  - [Compiles and minifies for production](#compiles-and-minifies-for-production)
  - [Lints and fixes files](#lints-and-fixes-files)

## Deployment

You can deploy static web pages via docker or directly to Nginx's web root.

### Docker

🚧 [WIP]

### Direct deployment

#### Install dependencies

```bash
yarn install
```

#### Deploy to Nginx's default web root

```bash
yarn deploy
```

This runs the following command in reality:

```bash
vue-cli-service build; rm -rf /var/www/html/*; mv ./dist/* /var/www/html
```

So be sure to backup your Nginx original webroot or your files will be deleted.

## Further development

### Compiles and hot-reloads for development

```bash
yarn serve
```

### Compiles and minifies for production

```bash
yarn build
```

### Lints and fixes files

```bash
yarn lint
```

---

👓 **Dummy ICP Page** ©Spencer Woo. Released under the [MIT License](./LICENSE).

Authored and maintained by Spencer Woo.

[@Portfolio](https://spencerwoo.com) · [@Blog](https://blog.spencerwoo.com) · [@GitHub](https://github.com/spencerwooo)
