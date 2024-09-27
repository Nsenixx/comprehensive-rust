# `no_std`

<table>
<tr>
<th>
  <div class="table">
    <div class="tr">
      <div class="th">
        <p><code>core</code></p>
      </div>
    </div>
  </div>
</th>
<th>
  <div class="table">
    <div class="tr">
      <div class="th">
        <p><code>alloc</code></p>
      </div>
    </div>
  </div>
</th>
<th>
  <div class="table">
    <div class="tr">
      <div class="th">
        <p><code>std</code></p>
      </div>
    </div>
  </div>
</th>
</tr>
<tr valign="top">
<td>
  <div class="tr">
    <div class="td">
      <ul>
        <li>Slices, <code>&amp;str</code>, <code>CStr</code></li>
        <li><code>NonZeroU8</code>...</li>
        <li><code>Option</code>, <code>Result</code></li>
        <li><code>Display</code>, <code>Debug</code>, <code>write!</code>...</li>
        <li><code>Iterator</code></li>
        <li><code>panic!</code>, <code>assert_eq!</code>...</li>
        <li><code>NonNull</code> and all the usual pointer-related functions</li>
        <li><code>Future</code> and <code>async</code>/<code>await</code></li>
        <li><code>fence</code>, <code>AtomicBool</code>, <code>AtomicPtr</code>, <code>AtomicU32</code>...</li>
        <li><code>Duration</code></li>
      </ul>
    </div>
  </div>
</td>
<td>
  <div class="tr">
    <div class="td">
      <ul>
        <li><code>Box</code>, <code>Cow</code>, <code>Arc</code>, <code>Rc</code></li>
        <li><code>Vec</code>, <code>BinaryHeap</code>, <code>BtreeMap</code>, <code>LinkedList</code>, <code>VecDeque</code></li>
        <li><code>String</code>, <code>CString</code>, <code>format!</code></li>
      </ul>
    </div>
  </div>
</td>
<td>
  <div class="tr">
    <div class="td">
      <ul>
        <li><code>Error</code></li>
        <li><code>HashMap</code></li>
        <li><code>Mutex</code>, <code>Condvar</code>, <code>Barrier</code>, <code>Once</code>, <code>RwLock</code>, <code>mpsc</code></li>
        <li><code>File</code> and the rest of <code>fs</code></li>
        <li><code>println!</code>, <code>Read</code>, <code>Write</code>, <code>Stdin</code>, <code>Stdout</code> and the rest of <code>io</code></li>
        <li><code>Path</code>, <code>OsString</code></li>
        <li><code>net</code></li>
        <li><code>Command</code>, <code>Child</code>, <code>ExitCode</code></li>
        <li><code>spawn</code>, <code>sleep</code> and the rest of <code>thread</code></li>
        <li><code>SystemTime</code>, <code>Instant</code></li>
      </ul>
    </div>
  </div>
</td>
</tr>
</table>

<details open="true">

- `HashMap` depends on RNG.
- `std` re-exports the contents of both `core` and `alloc`.

</details>
