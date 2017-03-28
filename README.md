# bootstrap-clockpicker

Fixes several issues and adds more options to the Bootstrap version of [https://github.com/weareoutman/clockpicker](https://github.com/weareoutman/clockpicker)

## Issues Fixed:
- input element value is correctly being set after selecting time
- am/pm is correctly being fetched from input value upon showing of the clock
- am/pm buttons, when clicked, toggle a selected class called "clockpicker-button-on" (set style properties in your own CSS)

## Added Options:
- leadingZeroHours: whether to add a preceding zero to the hour when it is less than 10 - also applies to parsing pre-filled input value
- upperCaseAmPm: whether to make the am/pm uppercase - also applies to parsing pre-filled input value
- leadingSpaceAmApm: whether to insert a space between the time and the am/pm - also applies to parsing pre-filled input value

## Use Example:
```
$('.clockpicker').clockpicker({
   donetext: 'Done',
   twelvehour: true,
   autoclose: false,
   leadingZeroHours: false,
   upperCaseAmPm: true,
   leadingSpaceAmPm: true
});
```

For the rest of the documentation, refer to original project: [https://github.com/weareoutman/clockpicker](https://github.com/weareoutman/clockpicker)
