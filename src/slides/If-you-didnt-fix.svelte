<script>
 import Slide from '../lib/Slide.svelte';
 import Image from '../lib/Image.svelte';
</script>

<Slide>
<Slide>
  <h2>#9: If you didn't fix, it ain't fixed</h2>
  <Image src="assets/i-didnt-do-anything-hayden.gif" alt="If you didn't" />
  <aside class="notes">
      Check the program yourself, have someone else check it for you,
      or walk through it with someone else.
      Run the same triangulation test cases you used to diagnose the problem
      to make sure that all aspects of the problem have been resolved.
      If you’ve solved only part of the problem, you’ll find out that you still have work to do.
      Rerun the whole program to check for side effects of your changes.
      The easiest and most effective way to check for side effects is to run the test suite.
  </aside>
</Slide>
<Slide>
  <h3>Check that it's really fixed</h3>
  <ul>
  <li>Don't assume that the fix works</li>
  <li>Test it!</li>
  <li>You can't be sure until you test it</li>
  </ul>
</Slide>
<Slide>
  <h3>Check that it's really your fix that fixed it</h3>
  <p>Fixed &rarr; Broken &rarr; Fixed</p>
</Slide>
<Slide>
  <h3>Know that it never just goes away by itself</h3>
  <p>It never just goes away by itself</p>
</Slide>
<Slide>
  <h3>Fix the cause</h3>
  <p>Don't assume that it broke for no reason</p>
</Slide>
<Slide>
  <h3>Fix the process</h3>
  <p>Hard to spot &rarr; Line between fixing a system and the process</p>
  <p>Go after the underlying conditions that created the failure</p>
</Slide>
</Slide>
