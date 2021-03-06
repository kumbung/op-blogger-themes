# OP Blogger Themes

## Notice:

### Recommended Themes
* [New Day](https://github.com/treezi1004/op-blogger-themes/tree/master/2_Columns/New_Day): 2 column, No Mobile SEO Problem, minimized control of theme design to font and color.
* [The Beginning](https://github.com/treezi1004/op-blogger-themes/tree/master/1_Column/The_beginning): 1 column, No Mobile SEO Problem, prototype version of other OP Blogger Themes

### Not Recommended Themes
* Today: Cannot configure categories from layout page.
* RT: Cannot configure categories from layout page.

### Other themes
They might have minor problems like mobile SEO from Google Search Console. However it is not really a problem to use them. Read under 'Mobile SEO Problem' and watch the video.

### Recent Blogger Theme Editor issues with Firefox or other web browsers
Please use Google Chrome as a web browser when you edit blogger theme if you have a problem. Blogger's theme edit page is unstable at the moment.

### Mobile SEO Problem
It is found that some of mobile version of themes are not SEO for google search. The themes are working fine in the test. However, There is some issues with OP Blogger Theme to be rendered properly in Googlebot smartphone. It is advised not to use some of op blogger themes if you are concerned about mobile SEO problem. You can still use recommended themes above.

Related video: [https://www.youtube.com/watch?v=vugCZMGY3L8&feature=youtu.be&t=49](https://www.youtube.com/watch?v=vugCZMGY3L8&feature=youtu.be&t=49)

## Description:
OP Blogger Themes are for blogger theme development.
Main purpose of this project is to have clean base blogger theme for people to develop theme easily.
There is no problem using the OP Blogger Themes without extra theme development.
Each directories contains a different blogger theme.

## Features:
1. Responsive Web design
2. Flexible control of minor theme designs
3. Blogger CSS variables
4. Open graph meta tags (Requires some modification)
5. Resizing iframe media(Youtube) for responsive web design
6. Better Categories
7. Pretty google search

## Setting up:

1. In blogger setting:
  * Blog descriptions
  * Enable Blogger meta tag
  * HTTPS redirection-Yes
  * Same time stamps
  * Disable Mobile version in theme (OP blogger theme supports responsive web design)

2. In blogger theme HTML edit:

  * Setting up open graph meta tags & other meta tags in head tag, that are commented.
    * Just need to put src link in the commented meta tags in head tag.
    * For locale, eg.) ko_KR, en_US, en_NZ
    * Other meta tags are also easy to setup.
  * Setting up default post thumbnails' image and default popular posts thumbnails' image
    * It needs default image to display a thumbnail for the case of no image in the post. Recommended size is around 250px x 250px. There are tags that are commented. Put src link into the empty img attributes. Popular post uses 72px x 72px of image size.
  * Setting URL for home in PageList1 widget
    * Default is blogger.com, it does not make any problem and it will work properly even though it is not edited. However it seems it supposed to be the current blog's home url.

## Problem & Solve

Q: Image doesn't fit into the container.

A: It is caused by the style that is generated automatically from the post editor. Edit post and remove ' style="margin-left: 1em; margin-right: 1em;" ' from the photo. Firefox/Chrome's replace extensions are recommended.


## License:
MIT

## Donation
* [Click here for donation page](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=R5EKF6TRDDXE8&currency_code=USD&source=url)

It would be nice if you can make donation for this kind of project.

## Author:
* Name: Chanil Park
* E-mail: falsesage1004@gmail.com
* Blog: [https://www.falsesage.com/](https://www.falsesage.com/)
* Youtube: [https://www.youtube.com/channel/UCOWFk2-Y4yuwVxK0yo6ABmw](https://www.youtube.com/channel/UCOWFk2-Y4yuwVxK0yo6ABmw)
