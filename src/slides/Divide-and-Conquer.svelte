<script>
 import Slide from '../lib/Slide.svelte';
 import Image from '../lib/Image.svelte';
</script>

<Slide>
<Slide>
  <h2>#4: Divide and Conquer</h2>
  <Image src="assets/divideandconquer.png" alt="Divide and Conquer" />
    <ul>
      <li>1st rule - actually involves finding the problem</li>
      <li>Only rule</li>
      <li>At the heart of debugging</li>
      <li>Naturally, many people do & don't understand</li>
    </ul>
</Slide>
<Slide>
  <h3>Narrow the search with successive approximation</h3>
    <p>Common technique used in any efficient target search</p>
    <p>want to find something within a range of possibilities</p>
</Slide>
<Slide>
  <h3>Get the range</h3>
    <p>135</p>
    <p>1-100</p>
    <p class="text-yellow-500">Widen the range</p>
</Slide>
<Slide>
  <h3>Determine which side of the bug you are on</h3>
    <p>Good &rarr; Bad</p>
    <p>You have to know</p>
    <ul>
      <li>your search range</li>
      <li>at one end things are good and at the other, things are bad</li>
      </ul>
      <aside class="notes">Things start out good, but somethwere along the way they become bad</aside>
</Slide>
<Slide>
  <h3>Use easy-to-spot test patterns</h3>
    <p>What do you do when</p>
    <ul>
      <li>effect of the bug is more <span class="text-yellow-500">subtle</span></li>
      <li>data is already so <span class="text-yellow-500">random looking</span></li>
      </ul>
      <p>One way to make a subtle effect more obvious &rarr; use a really <span class="text-yellow-500">easy-to-recognize input or test pattern</span></p>
    <aside class="notes">
      One way to make a subtle effect more obvious is to use a really easy-to-recognize input or test patterns
    </aside>
</Slide>
<Slide>
  <h3>Fix the bugs you know about</h3>
    <ul>
      <li>Hard to believe - More than one bug in a system</li>
      <li>Hard to isolate</li>
      <li>Several simultaneous problems - fix it right away</li>
      <li>Fix something you know wrong &rarr; clean look at the other issues</li>
    </ul>
      <aside class="notes">
      Sometimes, as hard as it might be to believe, there's more than one bug in a system
      This makes it harder to isolate each bug using "Divide and Conquer"
      So when you do figure out one of several simultaneous problems, fix it right away,
      before you look for the others.
      If you fix something thatt  you know is wrong, you get a clean look at the other issues
    </aside>
</Slide>
<Slide>
  <h3>Fix the noise first</h3>
    <ul>
      <li class="fragment">Other problems - often very unpredictable - go away when fix the noise</li>
      <li class="fragment">if noise is the issue</li>
      <li class="fragment">Weigh the difficulty of fixing the problem against the likelihood</li>
      <li class="fragment">Easy to become perfectionist</li>
    </ul>
      <p class="text-yellow-500 fragment">Don't get carried away</p>
      <aside class="notes">
    </aside>
</Slide>
</Slide>
