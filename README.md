# Bootstrap 4 extra utility classes.
Utilities allows you to rapidly create layouts & designs. Bootstrap adopted utilities since version 4 but are missing alot of essentials to really use bootstrap as a utility first framework.

This library utilizes the bootstrap variables so the utilities are generated with your project specific settings in mind. For example all responsive classes are generated based on your media-breakpoint variables.

## Installation
Install package `yarn add bootstrap-extra-utilities` or `npm i --save bootstrap-extra-utilities`

Include it right after your Bootstrap import so it reads your custom variables `@import "~bootstrap-extra-utilities/src/bootstrap-extra-utilities"`

## Included utilities (w.i.p.)
* overflow (auto|visible|scroll|auto-(x&y)|hidden-(x&y)|visible-(x&y)|scroll-(x&y))
* z-index (0,10,20,30,40,50,auto)

## Do you need Bootstrap?
If you are looking to solely use utilities to build your interfaces I highly recommend you to use [tailwindcss](https://tailwindcss.com/docs/) instead.