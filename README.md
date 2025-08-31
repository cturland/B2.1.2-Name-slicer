<h2>1) Starter — Name slicer (indexes &amp; slices)</h2>
<p><strong>Goal:</strong> Practise simple slicing and reversing.</p>

<h3>Task</h3>
<ol>
  <li>Ask the user for a single word (e.g., a name).</li>
  <li>Print:
    <ol type="a">
      <li>The <strong>first 3</strong> letters</li>
      <li>The <strong>last 2</strong> letters</li>
      <li>The word <strong>reversed</strong></li>
    </ol>
  </li>
</ol>

<h3>Rules / edge cases</h3>
<ul>
  <li>If the word is shorter than 3 characters, print the whole word for step 1.</li>
  <li>If the word is shorter than 2 characters, print the whole word for step 2.</li>
  <li>Keep the original capitalisation.</li>
</ul>

<h3>Example</h3>
<pre><code>Input:  Elephant
Output:
Ele
nt
tnahpelE
</code></pre>

<details>
  <summary><strong>Hints</strong></summary>
  <ul>
    <li><code>s[:3]</code> → first 3</li>
    <li><code>s[-2:]</code> → last 2</li>
    <li><code>s[::-1]</code> → reverse</li>
  </ul>
</details>
