## Phase 1

A StatefulWidget can store changing information while a StatelessWidget cannot. The favorite button needs state because its icon and color change when it is pressed. setState() rebuilds the button with the new appearance.

 ## Phase 2

The GlobalKey FormState lets the program access the form and run its validators. If the username is empty, Flutter displays the validator's error message. The controller is disposed of when the form is removed to prevent memory problems.