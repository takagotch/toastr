### toastr
---
https://github.com/CodeSeven/toastr

https://codeseven.github.io/toastr/

```sh
bower install toastr
npm install --save toastr
yarn add toastr

npm install -g gulp karma-cli
npm install

gulp analyze
gulp test
gulp
```

```rb
gem 'toastr-rails'
```

```scss
@import "toastr";
```

```coffee
#= require toastr
```

```js
toastr.info('Are you the 6 fingered man?')

toastr.warning('My name is Inigo Motoya. You killed my father, prepare to die!')
toastr.success('Have fun storming the castle!', 'Miracle Max Says')
toastr.error('I do not think that word means what you think it means.', 'Inconveivable!')
toastr.remove()
toastr.clear()
toastr.success('We do have the Kapua suite available.', 'Turtle Bay Resort', {timeOut: 5000})

toastr.options.escapeHtml = true;
toastr.options.closeButton = true;
toastr.options.closeHtml = '<button><i class="icon-off"></i></button>';

toastr.options.closeMethod = 'fadeOut';
toastr.options.closeDuration = 300;
toastr.options.closeEasing = 'swing';

toastr.options.newsetOnTop = false;

toastr.options.onShown = function(){ console.log('hello'); }
toastr.options.onHidden = function(){ console.log('goodbya'); }
toastr.options.onclick = function(){ console.log('clicked'); }
toastr.options.onCloseClick = function(){ console.log('close button clicked'); }

toastr.optoins.showEasing = 'swing';
toastr.options.hideEasing = 'linear';
toastr.options.closeEasing = 'linear';

toastr.options.showEasing = 'easeOutBounce';
toastr.options.hideEasing = 'easeInBack';
toastr.options.closeEasing = 'easeInBack';

toastr.options.showMethod = 'slideDown';
toastr.options.hideMethod = 'slideUp';
toastr.options.closeMethod = 'slideUp';

toastr.options.preventDuplicates = true;

toastr.options.timeOut = 30;
toastr.options.extendedTimeOut = 60;

toastr.options.timeOut = 0;
toastr.options.extendedTimeOut = 0;

toastr.options.progressBar = true;
toastr.options.rtl = true;
```

