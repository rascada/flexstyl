# flexstyl
Flex helper for stylus

# moved! - [flexstyl](https://github.com/simple-flex/flexstyl)

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
flex styl // display: flex;
align end // align-items: flex-end;
justify between  // justify-content: space-between;

wrap reverse // flex-wrap: reverse;

// example #2
flex styl
flex center
// display: flex;
// align-items: center;
// justify-content: center;

// example #3
flex line // display: inline-flex;
justify start // justify-content: flex-start;
align baseline // align-items: baseline;
flex grow // flex-grow: 1;
flex noshrink // flex-shrink: 0;
flex column // flex-direction: column;
wrap 1/wrap/true // flex-wrap: wrap;

// example #4
flex row // flex-direction: column;
justify around // justify-content: space-around;
flex nogrow // flex-grow: 0;
flex shrink // flex-shrink: 1;
wrap 0/nowrap/false //flex-wrap: nowrap;
```
