[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# Ruby vs. JavaScript: List Challenge

List processing is a very common task in applied computer science. Ruby and
JavaScript both have good list processing facilities, but they differ quite a
bit. This challenge requires you to solve the same two problems in both Ruby and
JavaScript.

## Prerequisites

-   [ga-wdi-boston/js-array-methods](https://github.com/ga-wdi-boston/js-array-methods)
-   [ga-wdi-boston/ruby-vs-js-arrays](https://github.com/ga-wdi-boston/ruby-vs-js-arrays)

## Instructions

You will be completing your work on CodeWars. **Work in the browser**, and if
you want feedback from consultants on your solution, follow these steps:

1.  Fork and clone this repository.
1.  Change into the new directory.
1.  Install dependencies.
1.  Create and checkout a new branch to work on.
1.  Fulfill the listed requirements.

For consultants to review your code, place it in
[`lib/challenge.js`](lib/challenge.js) and
[`lib/challenge.rb`](lib/challenge.rb).

You may wish to refer to [FAQs](https://github.com/ga-wdi-boston/meta/wiki/)
related to [forking,
cloning](https://github.com/ga-wdi-boston/meta/wiki/ForkAndClone).

## Requirements

Complete these exercises in both Ruby and JavaScript:

-   [True for Any?](http://www.codewars.com/kata/enumerable-magic-number-2-true-for-any)


function any(arr, fun){
  return arr.some(fun)
}

<!-- const any = (arr, fun) => arr.some(fun); -->

def any? list, &block
  list.any?(&block)
end


-   [True for None?](http://www.codewars.com/kata/enumerable-magic-number-4-true-for-none)

function none(arr, fun){
  return !arr.some(fun);
}

def none? list, &block
  list.none?(&block)
end

## Bonus

Complete the previous exercises in Python. You will have to do this on your own,
outside of CodeWars, since these kata have not been translated.

Complete the following exercises in Ruby, JavaScript, and Python:

-   [True for Just One?](http://www.codewars.com/kata/enumerable-magic-number-5-true-for-just-one)
-   [True for All?](http://www.codewars.com/kata/enumerable-magic-number-1-true-for-all)

## [License](LICENSE)

Source code distributed under the MIT license. Text and other assets copyright
General Assembly, Inc., all rights reserved.
