fontawesome:
	yarn add @fortawesome/fontawesome-pro@v6.1.1 -W
	@-mkdir -p static/assets/vendor/fontawesome/js static/assets/vendor/fontawesome/svgs
	cp -r node_modules/@fortawesome/fontawesome-pro/js/all.min.js static/assets/vendor/fontawesome/js
	cp -r node_modules/@fortawesome/fontawesome-pro/svgs/* static/assets/vendor/fontawesome/svgs

static/assets/css/bulma.css: static/assets/css/bulma.scss
	sassc $< $@
