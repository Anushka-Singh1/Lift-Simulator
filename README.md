# Lift-Simulator
The Lift Simulator project aims to demonstrate the efficient management of lifts within a building. It allows users to dynamically add new floors and lifts to the simulation, observe the lift doors' opening and closing, and witness the lifts moving to handle floor requests.

![lift](https://github.com/Anushka-Singh1/Lift-Simulator/assets/98011558/fbc7a502-5f4a-4423-8384-7083a388ec60)
# How to Use
<b>1.</b> Open the "index.html" file in a web browser.

<b>2.</b> The simulator interface will be displayed with a header, "Please stand clear of the doors!" and two buttons, "Add Floor" and "Add Lift."

<b>3.</b> Click on the "Add Floor" button to add a new floor to the building simulation.

<b>4.</b> Click on the "Add Lift" button to add a new lift to the simulation.

<b>5.</b> Each floor will have two buttons to call the lift – "Up" and "Down." Click on these buttons to request the lift to go up or down.

<b>6.</b> The lifts will automatically respond to the floor requests and move accordingly.

<b>7.</b> The lift doors will open, and after a few seconds, they will close automatically.

# Queue Application
The core functionality of this Lift Simulator is implemented using a <b>Queue data structure</b>. The Queue class handles the requests made by floors to call the lift and manages the order in which lifts handle these requests.

The Queue class has the following methods:

<b>1.</b> enqueue(element): Adds an element (floor request) to the end of the queue.

<b>2.</b> dequeue(): Removes and returns the front element (floor request) from the queue.

<b>3.</b> peek(): Returns the front element (floor request) without removing it from the queue.

<b>4.</b> isEmpty(): Returns true if the queue is empty, otherwise false.

<b>5.</b> size(): Returns the number of elements in the queue.

<b>6.</b >clear(): Clears all elements from the queue.
