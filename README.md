# flexstyl
Flex helper for stylus

## installation
#### cdn - [flex.styl](https://npmcdn.com/flexstyl/flex.styl)
#### npm
```sh
npm i flexstyl # --save
```
## @import
```stylus
@import 'path_to_flex.styl'
// or
@import '../node_modules/flexstyl/flex'
// or
@import '~flexstyl/flex' //webpack
// just import flex.styl regardless whence
```

## examples
```stylus
// example #1
flex styl // display flex
align end // align-items flex-end
justify between  // justify-content space-between

wrap reverse // flex-wrap reverse

// example #2
flex styl
flex center
// display flex
// align-items center
// justify-content center

// example #3
wrap 1
wrap wrap
wrap true
// flex-wrap wrap

// example #4
wrap 0
wrap nowrap
wrap false
//flex-wrap nowrap
```
