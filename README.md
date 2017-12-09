# react-autobind
autobind utility for React.

## Usage
```
import autobind from 'autobind';

class Hello extends React.Component {
  constructor(props) {
    super(props);
    
    // autobind here.
    autobind(this);
  }
}
```
