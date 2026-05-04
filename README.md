# Avocado
Say hello to Avocado, a hip, geometric site template.

[Papaya](https://www.papayatemplates.com)
[@jrdnbwmn](https://www.twitter.com/jrdnbwmn)

Demo images from [Unsplash](https://unsplash.com/).
Icons from [Entypo](http://entypo.com/).

## Instructions
For local development, run `npm install` in the project root and then `gulp` to start BrowserSync and watch tasks (see [Pear](https://github.com/jrdnbwmn/Pear)).

Development files are in `src`. Everything is compiled into `docs`, which is ready to be deployed with GitHub Pages.

## GitHub Pages deployment
1. Build the site:

	```bash
	gulp build
	```

2. Commit and push the generated `docs` folder.
3. In GitHub repository settings, go to Pages and set source to:
	- Branch: `main`
	- Folder: `/docs`