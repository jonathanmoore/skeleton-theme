Skeleton theme
============

The Skeleton theme is an ultra simple Shopify theme with almost no CSS and almost no theme settings.

The reasons why this theme can't be used in production
---------------------

- The Skeleton theme contains almost no CSS. You need to provide your own CSS. You'll find in the included theme style sheet (in /assets/style.css.liquid) the minified content of [normalize.css v1.1.0](http://necolas.github.com/normalize.css/). Normalize.css makes browsers render all elements more consistently and in line with modern standards. It precisely targets only the styles that need normalizing. The Skeleton theme style sheet also contains a few utility classes such as `clearfix`, `left` (to float left), `right` (to float right), and `grid` (to float left and add pading). Use your own CSS framework or Bootstrap or Foundation or any CSS framework.
- The Skeleton theme is super conventional in how it presents content. It is very drab. It presents the barely minimals in terms of that content too. 
- The Skeleton theme is not customizable. Even a custom-made theme built for one client should contain a fair amount of theme settings, to give a merchant some control over his shop. The Skeleton theme offers none of that.

So what is this good for?
---------------------

- The Skeleton theme will show you how to use Liquid in a Shopify theme. If you are a newbie to the Shopify platform, studying this theme will help you. If you are seasoned Shopify designer, you may still learn a few tricks. The main target audience here is professional web designers who are not yet familiar with the Shopfy platform.


