# Laravel 5.4 with laravel-mix & Browsersync setup

#### Install
Composer require

	composer create-project gurinder/lmb AppName --prefer-dist
	
Install npm

	npm install
	
####Browsersync Configuration
`webpack.config.js` is already copied to root folder of the app. To config browsersync plugin find out the following code block and update according to your needs.

```javascript
new BrowserSyncPlugin({
	open: 'external',
	host: 'example.dev',
	proxy: 'example.dev',
	files: ['resources/views/**/*.php', 'app/**/*.php', 'routes/**/*.php']
})
```


### License
[The Laravel framework](https://github.com/laravel/laravel) is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).

Laravel 5.4 with laravel-mix & Browsersync setup  is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).