---
minutes: 15
---

# Exercise: Collatz Sequence

<p>The <a href="https://en.wikipedia.org/wiki/Collatz_conjecture">Collatz Sequence</a> is defined as follows, for an arbitrary n<sub>1</sub> greater than zero:</p>
<ul>
<li><p>If n<sub>i</sub> is 1, then the sequence terminates at n<sub>i</sub>.</p></li>
<li><p>If n<sub>i</sub> is even, then n<sub>i+1</sub> = n<sub>i</sub> / 2.</p></li>
<li><p>If n<sub>i</sub> is odd, then n<sub>i+1</sub> = 3 * n<sub>i</sub> + 1.</p></li>
</ul>
<p>For example, beginning with n<sub>1</sub> = 3:</p>
<ul>
<li><p>3 is odd, so n<sub>2</sub> = 3 * 3 + 1 = 10;</p></li>
<li><p>10 is even, so n<sub>3</sub> = 10 / 2 = 5;</p></li>
<li><p>5 is odd, so n<sub>4</sub> = 3 * 5 + 1 = 16;</p></li>
<li><p>16 is even, so n<sub>5</sub> = 16 / 2 = 8;</p></li>
<li><p>8 is even, so n<sub>6</sub> = 8 / 2 = 4;</p></li>
<li><p>4 is even, so n<sub>7</sub> = 4 / 2 = 2;</p></li>
<li><p>2 is even, so n<sub>8</sub> = 1; and</p></li>
<li><p>the sequence terminates.</p></li>
</ul>

Write a function to calculate the length of the collatz sequence for a given
initial `n`.

```rust,editable,should_panic
{{#include exercise.rs:collatz_length}}
  todo!("Implement this")
}

{{#include exercise.rs:tests}}

{{#include exercise.rs:main}}
```
