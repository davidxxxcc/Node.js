# Node.js

Node.js is a** JavaScript runtime** execute in a **Chrome V8 engine**.

Chrome V8 engine is a** open source JavaScript engine** written in C++ that execute in a JavaScript code and compile into machine code. It's used inside Node.js and Chrome browser.

Node.js uses an **event-driven**, **non-blocking I/O** model that makes it lightweight and effiecient.

Non-blocking I/O:

* Blocking: while we are fetching from the database which it's I/O operation, our application cannot do anything else. This means our machine sit around wait and even cannot do something simple like add number or printing.
* Non-blocking I/O: we are not waiting for a I/O operation, we simpy kick off a event loop with only single thread.



