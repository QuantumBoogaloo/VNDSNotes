# Commands

## Skip

`#`

## End Script

`endscript`

## Load Background

`bgload <path:string> [fadeTime:int]`

## Set Image

`setimg <path:string> <x:int> <y:int>`

## Choice

`choice <choice:string>{'|'<choice:string>}`

## Jump

`jump <path:string> [label:string]`

## Delay

`delay <milliseconds:int>`

## Random

`random <variable:string> <low:int> <high:int>`

## Label

`label <label:string>`

## Go To

`goto <label:string>`

## Clear Text

`cleartext`

## If

`if <left:string> <operation:string> <right:string>`

`operation` should be one of:
* `==`
* `!=`
* `<`
* `>`
* `<=`
* `>=`

## Fi

`fi`

## Await Input

`text !` - Wait for input

## Text

`text ~` - Append blank line and don't wait for input.
`text @<text:line>` - Append text and don't wait for input.
`text <text:line>` - Append text and wait for input.

## Set Local Variables

`setvar <variable:string> <left:string> <operation:string> <right:string>`

`operation` should be one of:
* `=`
* `+`
* `-`

## Clear Local Variables

`setvar <ignored:string> ~`

## Set Global Variables

`gsetvar <variable:string> <left:string> <operation:string> <right:string>`

`operation` should be one of:
* `=`
* `+`
* `-`

## Clear Global Variables

`gsetvar <ignored:string> ~`

## Play Music

`music <path:string>`

## Stop Music

`music ~`

## Play Sound

`sound <path:string> [repeats:int]`

## Stop Sound

`sound ~`




