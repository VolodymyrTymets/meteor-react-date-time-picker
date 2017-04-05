# alonoslav:meteor-react-date-time-picker

This MeteorJS package provide React DateTimePicker component for your applications.

More about bootstrap datetimepicker used for this package you can read [here](https://github.com/smalot/bootstrap-datetimepicker).

### Changes in 0.1.0
`DateTimePicker` component now export as constant, not as default

### Peer dependencies
* react
* react-dom

### Basic example

```jsx harmony
import { DateTimePicker } from 'meteor/alonoslav:meteor-react-date-time-picker';

const onDateChanged = (date) => console.log('DATE', date);

 <DateTimePicker
    id="test-datetimepicker"
    classNames="form-control"
    onDateChanged={onDateChanged}
    type="datepicker"
/>
```

### Props

| Name |Description|
| ---- | --------- |
| id (required) | ID of datetimepicker input field |
| classNames | classes for input field |
| options | Datetimepicker options |
| type | Possible values: *datePicker, dateTimePicker, timePicker* |
| onDateChanged | Callback for handling date changing |
