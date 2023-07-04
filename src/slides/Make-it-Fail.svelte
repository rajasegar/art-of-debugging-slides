<script>
 import Slide from '../lib/Slide.svelte';
 import Image from '../lib/Image.svelte';
</script>

<Slide>
<Slide>
    <h1>#2</h1>
  <h2>Make it Fail</h2>
  <Image src="assets/make-it-fail.jpg" alt="Make it Fail" />
  <ul>
    <li>occur reliably</li>
    <li>Impossible to diagnose</li>
  </ul>
  <p>Challenging task => Making an intermitted defect occur predictably</p>
  <aside class="notes">
      If a defect doesn’t occur reliably, it’s almost impossible to diagnose. Making an intermittent defect occur predictably is one of the most challenging tasks in debugging.
  </aside>
</Slide>
<Slide>
  <h3>Do it again</h3>
  <p> Attitude: One failure is not enough</p>
  <aside class="notes">
    Mainly , you just have to have the attitude that one failure is not enough
  </aside>
</Slide>

<Slide>
  <h3>Start at the beginning</h3>
  <p>Bugs can depend on a complex state of application</p>
  <aside class="notes">
    Because bugs can depend on a complex state of application,
    you have to be careful to note the state of the application going into your sequence
    Try to start the sequence from a known state
  </aside>
</Slide>
<Slide>
  <h3>Stimulate the failure</h3>
</Slide>
<Slide>
  <h3>But don't simulate the failure</h3>
</Slide>
<Slide>
  <h3>Find the uncontrolled condition that makes it intermittent </h3>
</Slide>
<Slide>
  <h3>Record everything and find the signature of intermittent bugs</h3>
</Slide>
<Slide>
  <h3>Don't trust statistics too much</h3>
</Slide>
<Slide>
  <h3>Know that "that" can happen</h3>
</Slide>
<Slide>
  <h3>Never throw away a debugging tool</h3>
</Slide>
</Slide>
