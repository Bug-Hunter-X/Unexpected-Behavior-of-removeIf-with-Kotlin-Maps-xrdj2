# Unexpected Behavior of removeIf with Kotlin Maps

This repository demonstrates a subtle difference in the behavior of the `removeIf` function when used with `MutableList`, `MutableSet`, and `MutableMap` in Kotlin. While seemingly straightforward, the way `removeIf` interacts with Maps can lead to unexpected results if not understood clearly.

The `bug.kt` file shows the unexpected behavior. The `bugSolution.kt` file offers a clearer approach to remove items based on key values.

This example highlights the importance of understanding the specific operations of collection methods in different contexts to avoid potential errors.