# Uncommon HTML Bug: Event Listener Leak

This repository demonstrates an uncommon bug in HTML related to event listeners.  When an element is hidden using JavaScript, but the event listener attached to it remains, it can lead to unexpected behavior or performance issues, especially if the element is shown again later.

The bug is reproduced in `bug.html`, and the solution is provided in `bugSolution.html`.