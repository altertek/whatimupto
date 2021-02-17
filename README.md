# Whatimupto

> Light and Standalone open source linktree with a git based backend


## Example

https://whatimupto.saxjst.com

<div align="center">
<a href="https://now.saxjst.com">
	<img src="homepage-whatimupto.png" width="200" title="homepage">
	<img src="backend-whatimupto-01.png" style="margin-top:5px;" width="200" title="homepage">
	<img src="backend-whatimupto-02.png" style="margin-top:5px;" width="200" title="homepage">
	<img src="backend-whatimupto-03.png" style="margin-top:5px;" width="200" title="homepage">

</a>
</div>

## Getting Started

Detailed instructions are available in my blog. [Check it out](https://blog.surjithctly.in/neat-stack-create-a-static-website-with-netlify-cms-eleventy-alpinejs-and-tailwindcss)

<a href="https://app.netlify.com/start/deploy?repository=https://github.com/altertek/whatimupto&amp;stack=cms"><img src="https://www.netlify.com/img/deploy/button.svg" alt="Deploy to Netlify" /></a>

<a href="https://gitlab.com/alpha14/whatimupto/-/forks/new">Deploy on Gitlab</a> | <a href="https://github.com/altertek/whatimupto/fork">Fork on Github</a>

### 1\. Clone this Repository

```
git clone https://github.com/altertek/whatimupto.git
```

### 2\. Navigate to the directory

```
cd whatimupto
```

### 3\. Install dependencies

```
npm install
```

### 4\. Build the project to generate the first CSS

This step is only required the very first time.

```
npm run build
```

### 5\. Run Eleventy

```
npm run start
```


## Production

- For the github auth, add the name of your repo [here](https://github.com/altertek/whatimupto/blob/master/src/admin/config.yml#L6)
- For other auth methods, check the [netlify cms documentation](https://www.netlifycms.org/docs/backends-overview)

## Technologies used:

- [Netlify CMS](https://www.netlifycms.org/)
- [Eleventy](https://www.11ty.dev/)
- [Alpine.js](https://github.com/alpinejs/alpine)
- [Bootstrap](https://getbootstrap.com/)
- [Neat Starter](https://github.com/surjithctly/neat-starter)

## License

MIT © [altertek](https://altertek.org)
