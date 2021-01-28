# gaydients
gaydients is a collection of lgbtqiap+ gradients made with css. they help make the web gay. free and always will be.

## installation

install with npm:

```shell
npm install gaydients --save
```

install with yarn:

```shell
yarn add gaydients
```

## getting started
there's a few ways to use gaydients, depending on your use case.

if you're using any of the css-in-js flavors, the best way is to just import the styles as an object:

```shell
import gaydients from 'gaydients/gaydients.scss';
```

this gives you access to each of values ready for you to use:
```shell
{
  rainbowFlag: ...,
  rainbowGradient: ...,
  transFlag: ...,
  transGradient: ...,
  enbyFlag: ...,
  enbyGradient: ...,
  genderqueerFlag: ...,
  genderqueerGradient: ...,
  aceFlag: ...,
  aceGradient: ...,
  pansexualFlag: ...,
  pansexualGradient: ...,
  aroFlag: ...,
  aroGradient: ...,
  agenderFlag: ...,
  agenderGradient: ...,
  intersexFlag: ...,
  intersexGradient: ...,
  bisexualFlag: ...,
  bisexualGradient: ...,
}
```

you can also just import the ones you need:
```shell
import {transFlag, enbyFlag} from 'gaydients/gaydients.scss';
```

## classes
there's also convenient classes you can use for default flags and gradients.

just import the sass:
```shell
@import "~gaydients/gaydients.scss";
```


| class name | description |
| ------ | ------ |
| .gaydient-rainbow-flag | rainbow flag background |
| .gaydient-rainbow-gradient | rainbow gradient background |
| .gaydient-trans-flag | trans flag background |
| .gaydient-trans-gradient | trans gradient background |
| .gaydient-enby-flag | enby flag background |
| .gaydient-enby-gradient | enby gradient background |
| .gaydient-genderqueer-flag | genderqueer flag background |
| .gaydient-genderqueer-gradient | genderqueer gradient background |
| .gaydient-ace-flag | ace flag background |
| .gaydient-ace-gradient | ace gradient background |
| .gaydient-rainbow-flag | pansexual flag background |
| .gaydient-pansexual-gradient | pansexual gradient background |
| .gaydient-aro-flag | aro flag background |
| .gaydient-aro-gradient | aro gradient background |
| .gaydient-agender-flag | agender flag background |
| .gaydient-agender-gradient | agender gradient background |
| .gaydient-intersex-flag | intersex flag background |
| .gaydient-intersex-gradient | intersex gradient background |
| .gaydient-bisexual-flag | bisexual flag background |
| .gaydient-bisexual-gradient | bisexual gradient background |

you can also set change the `.gaydient` class prefix by setting `$gaydients-class-prefix` to whatever you want.


## documentation
below are the available functions to build out flags.

### gaydient-rainbow
function used to generate rainbow flag

| parameter | default value | description | type |
| ------ | ------ | ------ | ------ |
| $red | #ff0018 | red portion | hex |
| $orange | #ffa52c | orange portion | hex |
| $yellow | #ffff41 | yellow portion | hex |
| $green  | #008018 | green portion | hex |
| $blue | #0000f9 | blue portion | hex |
| $purple | #86007d | purple portion | hex |
| $opacity | 1 | the opacity of each color | number between 0 and 1 (inclusive) |
| $degrees | 180deg | degrees at which gradient is rendered | degrees |
| $chunk | 1 | how solid each color portion is | number between 0 and 1 (inclusive) |

### gaydient-trans
function used to generate trans flag

| parameter | default value | description | type |
| ------ | ------ | ------ | ------ |
| $blue | #55cdfc | blue portion | hex |
| $pink | #f7a8b8 | pink portion | hex |
| $white | #fff | white portion | hex |
| $opacity | 1 | the opacity of each color | number between 0 and 1 (inclusive) |
| $degrees | 180deg | degrees at which gradient is rendered | degrees |
| $chunk | 1 | how solid each color portion is | number between 0 and 1 (inclusive) |

### gaydient-enby
function used to generate non-binary flag

| parameter | default value | description | type |
| ------ | ------ | ------ | ------ |
| $yellow | #fff433 | yellow portion | hex |
| $white | #fff | white portion | hex |
| $purple | #9b59d0 | purple portion | hex |
| $black | #000 | black portion | hex |
| $opacity | 1 | the opacity of each color | number between 0 and 1 (inclusive) |
| $degrees | 180deg | degrees at which gradient is rendered | degrees |
| $chunk | 1 | how solid each color portion is | number between 0 and 1 (inclusive) |

### gaydient-genderqueer
function used to generate genderqueer flag

| parameter | default value | description | type |
| ------ | ------ | ------ | ------ |
| $lavender | #b77fdd | lavendar portion | hex |
| $white | #fff | white portion | hex |
| $green | #48821e | green portion | hex |
| $black | #000 | black portion | hex |
| $opacity | 1 | the opacity of each color | number between 0 and 1 (inclusive) |
| $degrees | 180deg | degrees at which gradient is rendered | degrees |
| $chunk | 1 | how solid each color portion is | number between 0 and 1 (inclusive) |

### gaydient-ace
function used to generate ace flag

| parameter | default value | description | type |
| ------ | ------ | ------ | ------ |
| $black | #000 | black portion | hex |
| $grey | #a4a4a4 | grey portion | hex |
| $white | #fff | white portion | hex |
| $purple | #810081 | purple portion | hex |
| $opacity | 1 | the opacity of each color | number between 0 and 1 (inclusive) |
| $degrees | 180deg | degrees at which gradient is rendered | degrees |
| $chunk | 1 | how solid each color portion is | number between 0 and 1 (inclusive) |

### gaydient-pansexual
function used to generate pansexual flag

| parameter | default value | description | type |
| ------ | ------ | ------ | ------ |
| $pink | #ff1b8d | pink portion | hex |
| $yellow | #ffda00 | yellow portion | hex |
| $blue | #1bb3ff | blue portion | hex |
| $opacity | 1 | the opacity of each color | number between 0 and 1 (inclusive) |
| $degrees | 180deg | degrees at which gradient is rendered | degrees |
| $chunk | 1 | how solid each color portion is | number between 0 and 1 (inclusive) |

### gaydient-aro
function used to generate aro flag

| parameter | default value | description | type |
| ------ | ------ | ------ | ------ |
| $green | #3aa63f | green portion | hex |
| $lightgreen | #a8d47a | light green portion | hex |
| $white | #ffffff | white portion | hex |
| $grey | #aaaaaa | grey portion | hex |
| $black | #000000 | black portion | hex |
| $opacity | 1 | the opacity of each color | number between 0 and 1 (inclusive) |
| $degrees | 180deg | degrees at which gradient is rendered | degrees |
| $chunk | 1 | how solid each color portion is | number between 0 and 1 (inclusive) |

### gaydient-agender
function used to generate agender flag

| parameter | default value | description | type |
| ------ | ------ | ------ | ------ |
| $black | #000000 | black portion | hex |
| $white | #a8d47a | white green portion | hex |
| $grey | #a4a4a4 | grey portion | hex |
| $purple | #810081 | purple portion | hex |
| $opacity | 1 | the opacity of each color | number between 0 and 1 (inclusive) |
| $degrees | 180deg | degrees at which gradient is rendered | degrees |
| $chunk | 1 | how solid each color portion is | number between 0 and 1 (inclusive) |

### gaydient-intersex
function used to generate intersex flag

| parameter | default value | description | type |
| ------ | ------ | ------ | ------ |
| $yellow | #ffda00 | yellow portion | hex |
| $purple | #7a00ac | purple green portion | hex |
| $opacity | 1 | the opacity of each color | number between 0 and 1 (inclusive) |
| $degrees | 180deg | degrees at which gradient is rendered | degrees |
| $chunk | 1 | how solid each color portion is | number between 0 and 1 (inclusive) |
| $flag | true | determines whether to render a flag or gradient | bool |

### gaydient-bisexual
function used to generate bisexual flag

| parameter | default value | description | type |
| ------ | ------ | ------ | ------ |
| $pink | #d60270 | pink portion | hex |
| $purple | #9b4f96 | purple green portion | hex |
| $blue | #0038a8 | blue portion | hex |
| $opacity | 1 | the opacity of each color | number between 0 and 1 (inclusive) |
| $degrees | 180deg | degrees at which gradient is rendered | degrees |
| $chunk | 1 | how solid each color portion is | number between 0 and 1 (inclusive) |

## notes
customizing the gradients for your exact specifications probably involves using both the sass to use the built-in functions and importing your custom values to js for best practices.

## license
this is licensed under [GNU GPLv3](LICENCE)
