# Rust Undefined Behavior Example

This repository demonstrates a common source of undefined behavior in Rust: manipulating a vector through a raw pointer after the vector's internal structure is changed.  The original code exhibits this issue.  A solution is provided that safely avoids undefined behavior.

The example highlights the importance of understanding Rust's ownership and borrowing system to prevent subtle and difficult-to-debug issues.