# Use images in markdown on Github

## Variant 1: Relative files can be used only on github self

`![Icon 1](./PATH/TO/FILE.svg)`

![Icon 1](./guides/svg/GUIDE_02_example_1.svg)

## Variant 2:** Same as variant 1, but using a arrow tag

`<img src="./PATH/TO/FILE.svg">`

<img src="./guides/svg/GUIDE_02_example_1.svg">

Note: There can be errors when using this with other services like Bitbucket.

## Variant 3: raw.githubusercontent files

Raw.github.com files can only used in combination with `?sanitize=true`

`![Icon 3](https://raw.githubusercontent.com/USER/REPO/BRANCH/DIRECTORY/FILE.svg?sanitize=true)`

![GUIDE_02_example_1.svg](https://raw.githubusercontent.com/Merukeru/imgs/master/guides/svg/GUIDE_02_example_1.svg?sanitize=true)

## Variant 4: raw.githubusercontent files via a arrow tag

`<img src="https://raw.githubusercontent.com/USER/REPO/BRANCH/DIRECTORY/FILE.svg?sanitize=true">`

<img src="https://raw.githubusercontent.com/USER/REPO/BRANCH/DIRECTORY/FILE.svg?sanitize=true">

## Variant 5: SVG files hosted on github.io

`![Icon 5](https://USER.github.io/DIRECTORY/FILE.svg)`

![Icon 5](https://merukeru.github.io/imgs/master/guides/svg/GUIDE_02_example_1.svg)

## Variant 6: SVG files hosted on github.io with arrow tag

`<img src="https://USER.github.io/DIRECTORY/FILE.svg">`

<img src="https://merukeru.github.io/imgs/master/guides/svg/GUIDE_02_example_1.svg">

## Variant 7: SVG files on rawgithub.io can be also be used

`![Icon 7](https://rawgithub.io/USER/DIRECTORY/FILE.svg)`

![Icon 7](https://rawgithub.io/merukeru/imgs/master/guides/svg/GUIDE_02_example_1.svg)

## Variant 8:  SVG files on rawgithub.io with arrow tag

`<img src="https://rawgithub.io/USER/DIRECTORY/FILE.svg">`

<img src="https://rawgithub.io/merukeru/imgs/master/guides/svg/GUIDE_02_example_1.svg">
