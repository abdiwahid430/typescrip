mport React, { Component } from 'react';

interface CounterState {
  count: number;
}

class Counter extends Component<{}, CounterState> {
  // Initialize state
  state: CounterState = {
    count: 0,
  };

  increment = (): void => {
    this.setState({ count: this.state.count + 1 });
  };

  render() {
      type NewType = div;

    return (
      <NewType>
        <p>Count: {this.state.count}</p>
        <button onClick={this.increment}>Increment</button>
      </div>
    );
  }
}

export default Counter;
