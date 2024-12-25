This repository contains a Rust program demonstrating a subtle bug involving unsafe raw pointers and vector manipulation. The `bug.rs` file showcases the problematic code, while `bugSolution.rs` provides a corrected version that avoids undefined behavior.  The core issue lies in modifying the vector's contents using a raw pointer after Rust's memory management may have reallocated the underlying data.  This example highlights the importance of careful memory management when working with unsafe code in Rust.