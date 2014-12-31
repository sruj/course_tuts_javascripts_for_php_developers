## Tuts+ Course: JavaScript for PHP Developers
### Instructor: Jason Rhodes

In this course I explain the basics and some common advanced pitfalls of JavaScript, framed in a way that will make sense to intermediate to advanced PHP developers. If you know PHP, need to use JavaScript, but can't make sense of it, this course will walk you through converting a small Slim PHP app into a similar JS app so you can see how the concepts relate.

Source files for the Tuts+ course: [JavaScript for PHP Developers](https://code.tutsplus.com/courses/javascript-for-php-developers)

### Usage Notes

* The example PHP application can be found in the /php directory
* The JavaScript starter files are found in the /js directory

**A note about dependencies**

Typically I would .gitignore the vendor and node_modules folders in these apps so that we wouldn't be committing our dependency packages to the repo, but for this example app I thought it was best if you had access to the dependencies without having to worry about running composer or npm.

If you prefer to install your own, remove php/vendor and js/node_modules and then run `composer install` and `npm install` in the respective folders to install dependencies yourself. (At that point you should probably add those folders to your .gitignore in your fork, too.)

