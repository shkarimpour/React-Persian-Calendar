# React Persian Calender
this is a simple yet practical persian calender for react.

## Important note
this component is dependant on ["moment-jalaali"](https://github.com/jalaali/moment-jalaali) package so make sure you install momentJs first

## Install 
`npm install --save react-persian-calender`

## Use
`import Calender from 'react-persian-calender'`
`
render() {
  <Calender onChange={handeler}>
}
`

## Props
the only prop right now is `onChange` which accepts a function.

you can use your own styles just override the current styles 
using css.
