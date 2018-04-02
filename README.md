# react-material-timeline

`react-material-timeline` is a vertical (right now!) timeline component which can be summarized with a simple equation:
```
react-material-timeline = react + material-ui + some code
```
If you are looking for elegant, simple library to show time based event, this is the perfect candidate!

## Features
* easy to integrate with `material-ui`
* compatible with `material-ui` theme
* lightweight and simple
* optional Typescript mappings



## Instalation
### Prerequisites
`react-material-timeline` uses `material-ui` (v1.0) library.
It means you should have configured `material-ui` before you start.
For more information look here: https://material-ui-next.com/getting-started/installation/

### Install package
The install process is as easy as always:
```
yarn add -s react-material-timeline`
```
or
```
npm install -s react-material-timeline
```

## Usage
1. Import.
2. Prepare `events`
3. Feed `Timeline`
4. Have fun.

```
import Timeline from 'react-material-timeline';
import { Avatar, Icon } from 'material-ui';

const icon =

const events = [
  {
    time: new Date(),
    title: 'Event 1',
    description: [ 'Some description for event 1' ],
    icon: <Avatar><Icon>work</Icon></Avatar>,
  },
  {
    time: new Date(),
    title: 'Event 2',
    description: [ 'Some description for event 2' ],
    icon: <Avatar><Icon>home</Icon></Avatar>,
  }
];

class AwesomeTimeline extends Component {
  render() {
    return <Timeline events={events}/>;
  }
}
```

## Contributions && Feature requests
If you have any ideas how to make this library better or you found a bug feel free to open new issue.
This project is our hobby and we'd like to invite you to have fun enhancing it with us!


To run a web server type `yarn start`
