# SSP
# Server Side Programming

## What I did

- **1.6:** Built the feedback app with three buttons and a separate `useState` for each counter.
- **1.7:** Added the total, the average score (good = 1, neutral = 0, bad = -1) and the percentage of positive feedback.
- **1.8:** Extracted a `Statistics` component and kept the state in `App`.
- **1.9:** Showed the statistics only after feedback was given, otherwise "No feedback given".
- **1.10:** Extracted reusable `Button` and `StatisticLine` components.
- **1.11:** Displayed the statistics in an HTML table and fixed all console warnings.

## What I learned

- Using multiple `useState` hooks and never mutating state directly.
- Lifting state up and passing data and event handlers to child components via props.
- Conditional rendering based on state.
- Computing derived values during rendering instead of storing them in state.
- Never defining components inside other components.
- Debugging with the browser console and valid HTML structure (`<tbody>` in tables).