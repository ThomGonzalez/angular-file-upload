# Angular File Upload

---

## About

**Angular File Upload** is a module for the [AngularJS](http://angularjs.org/) framework. Supports drag-n-drop upload, upload progress, validation filters and a file upload queue. It supports native HTML5 uploads, but degrades to a legacy iframe upload method for older browsers. Works with any server side platform which supports standard HTML form uploads.

When files are selected or dropped into the component, one or more filters are applied. Files which pass all filters are added to the queue. When file is added to the queue, for him is created instance of `{FileItem}` and uploader options are copied into this object. After, items in the queue (FileItems) are ready for uploading.

You could find this module in bower like [_angular file upload_](http://bower.io/search/?q=angular%20file).

## Demos
1. [Simple example](http://nervgh.github.io/pages/angular-file-upload/examples/simple)
2. [Uploads only images (with canvas preview)](http://nervgh.github.io/pages/angular-file-upload/examples/image-preview)
3. [Without bootstrap example](http://nervgh.github.io/pages/angular-file-upload/examples/without-bootstrap)

## CSRF in Django

The CSRF middleware and template tag provides easy-to-use protection against Cross Site Request Forgeries. This type of attack occurs when a malicious Web site contains a link, a form button or some JavaScript that is intended to perform some action on your Web site, using the credentials of a logged-in user who visits the malicious site in their browser. A related type of attack, ‘login CSRF’, where an attacking site tricks a user’s browser into logging into a site with someone else’s credentials, is also covered. [Cross Site Request Forgery protection](https://docs.djangoproject.com/en/1.8/ref/csrf/#ajax)

## More Info

1. [Introduction](https://github.com/nervgh/angular-file-upload/wiki/Introduction)
2. [Module API](https://github.com/nervgh/angular-file-upload/wiki/Module-API)
3. [FAQ](https://github.com/nervgh/angular-file-upload/wiki/FAQ)
4. [Migrate from 0.x.x to 1.x.x](https://github.com/nervgh/angular-file-upload/wiki/Migrate-from-0.x.x-to-1.x.x)
5. [RubyGem](https://github.com/marthyn/angularjs-file-upload-rails)
