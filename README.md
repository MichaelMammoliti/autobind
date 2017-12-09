# autobind
This utility binds a context to all class' methods.

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
