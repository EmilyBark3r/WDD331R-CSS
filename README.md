# Style Stage Source Sass

> A minimal starter for Style Stage submissions that includes the source Sass used to create the base Style Stage theme, and the source HTML.

[Read the full guidelines](https://stylestage.dev/guidelines/) to ensure your final styles will be ready for inclusion in the showcase!

## To Use

1. Fork or select "Use this Template"
2. Once cloned to your computer, run `npm i` to install dependencies needed to compile the Sass
3. Run `npm start` to launch a hot-reload server that watches for Sass changes.

The final stylesheet will be placed in `public/style.css`.

You may alter anything and everything, but keep in mind that the final stylesheet should be unminified and ideally non-prefixed. All Style Stage submissions are parsed with `autoprefixer` during the publish build process, and unminified stylesheets are easier for visitors to learn from.

> If you change the output stylesheet name, be sure to update the link to it in `index.html`

### Publish to Github Pages
This starter uses github actions to auto deploy `public` directory to `gh-pages` branch whenever there is a push to `main` branch.
1. Go to repo settings, under Github Pages, select `gh-pages` as source.
2. Go to https://username.github.io/stylestage-sass to see your published site.

## Submitting Your Stylesheet

Once you've created your stylesheet with this starter, publish this as a public repo and then you can use the GitHub link to the "raw" version of the `public/style.css` file for your final submission.

If you choose to publish to github pages, you can use:
https://username.github.io/stylestage-sass/style.css

You will need to fork [the main Style Stage repo](https://github.com/5t3ph/stylestage) to add your stylesheet, as [explained in the FAQ](https://stylestage.dev/guidelines/#how-do-i-create-a-pull-request-pr).


<!-- COLORS
(white)Ghost White: #E8E9F3
(orange)Pumpkin: #FF6D00
(black)Night: #09090E
(green)Apple Green: #99AA38
(purple)Russian Violet: #240046
(brown)Capnut mortuum: #5A352A
(black)Licorice: #1F1300
(red)Bard Red: #720E07
(white)Mint Cream: #F3F7F0
(white)Anti-flash White: #EBEBEB
https://coolors.co/palette/da2c38-226f54-87c38f-f4f0bb-43291f
https://coolors.co/palette/5c0000-751717-ba0c0c-ff0000-ffebeb-ecffeb-27a300-2a850e-2d661b-005c00
FONTS 
https://fonts.google.com/specimen/Creepster
https://fonts.google.com/specimen/Henny+Penny
https://fonts.google.com/specimen/Irish+Grover
https://fonts.google.com/specimen/Mountains+of+Christmas
https://fonts.google.com/specimen/Jolly+Lodger
https://fonts.google.com/specimen/Nosifer
https://fonts.google.com/specimen/Rubik+Wet+Paint
https://fonts.google.com/specimen/Butcherman
https://fonts.google.com/specimen/Bellota?query=Bell
https://fonts.google.com/specimen/Emilys+Candy?query=candy
https://fonts.google.com/specimen/Young+Serif?sort=date
https://fonts.google.com/specimen/Aboreto?sort=alpha
https://fonts.google.com/specimen/Aclonica?sort=alpha
https://fonts.google.com/specimen/Aladin?sort=alpha
IDEA
Header, nav anything above the Main will be Christmas centered with images, lights, fonts, colors, and then in the Main it transitions to Halloween slowly and the after the Main will be only Halloween with colors, fonts, and images of icons or characters representing the theme of Halloween.
WIREFRAME LINK FOR LARGE VIEW: https://wireframe.cc/Thfn5x
WIREFRAME LINK FOR SMALL VIEW: https://wireframe.cc/i38wIk
 -->