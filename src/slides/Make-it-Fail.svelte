<script>
 import Slide from '../lib/Slide.svelte';
 import Image from '../lib/Image.svelte';
</script>

<Slide>
  <Slide>
    <h2>#2: Make it Fail</h2>
    <div class="flex gap-4">
      <section>
        <Image src="assets/make-it-fail.jpg" alt="Make it Fail" />
      </section>
      <section class="text-left">
        <ul>
          <li>occur reliably</li>
          <li>Impossible to diagnose</li>
        </ul>
      </section>
    </div>
        <p>Challenging task &rarr; Making an intermittent defect occur predictably</p>
    <aside class="notes">
      If a defect doesn’t occur reliably, it’s almost impossible to diagnose. Making an intermittent defect occur predictably is one of the most challenging tasks in debugging.
    </aside>
  </Slide>
  <Slide>
    <h3>Do it again</h3>
    <p> <span class="font-bold text-yellow-500">Attitude:</span> One failure is not enough</p>
    <aside class="notes">
      Mainly , you just have to have the attitude that one failure is not enough
    </aside>
  </Slide>

  <Slide>
    <h3>Start at the beginning</h3>
    <p>Bugs can depend on a complex state of the application</p>
    <aside class="notes">
      Because bugs can depend on a complex state of the application,
      you have to be careful to note the state of the machine going into your sequence
      Try to start the sequence from a known state
    </aside>
  </Slide>
  <Slide>
    <h3>Stimulate the failure</h3>
    <ul>
      <li>Failure sequence requires a lot of manual steps &rarr; Automate the process</li>
    </ul>
  </Slide>
  <Slide>
    <h3>But don't simulate the failure</h3>
    <p class="text-yellow-500">Stimulating vs Simulating</p>
    <p>Simulating the conditions  &rarr; OK</p>
    <p>Try to avoid simulating the failure mechanism</p>
  </Slide>
  <Slide>
    <h3>Find the uncontrolled condition that makes it intermittent </h3>
  </Slide>
    <Slide>
    <h3>3 reasons to make it fail:</h3>
    <p>So you can</p>
    <ol>
      <li>Look at it</li>
      <li>Get a clue about the cause</li>
      <li>Tell when it's fixed</li>
    </ol>
  </Slide>
  <Slide>
    <h3>Record everything and find the signature of intermittent bugs</h3>
    <ul>
      <li>Look at it each time it fails</li>
      <li>Ignore other times</li>
      <li>Capture info on every run</li>
      <li>Compare a bad run with a good one</li>
    </ul>
      <aside class="notes">
      You have to able to look at the failure
      If it doesn't happen every time, you have to look at it each time if fails,
      while ignoring the many time it doesn't fail
      The key is to capture info on every run so you can look at if after you know that it is failed.
      By looking at captured information, you can easily compare a bad run with a good one
    </aside>
  </Slide>
  <Slide>
    <h3>Don't trust statistics too much</h3>
    <ul>
      <li>Coincidences</li>
      <li>Direct Effect</li>
      <li>Random factors</li>
      <li>Chances of figuring out &rarr; pretty slim</li>
    </ul>
    <aside class="notes">
      A lot of time,s coincidences will make you think that one condition makes
      the problem more likely to happen than some other condition
      Don't waste a lot of time barking up the wrong tree.
      But if they don't have a direct effect, the connection will be hidden by
      other random factors, and your chances of figuring it out by looking at
      those differences are pretty slim

    </aside>
  </Slide>
  <Slide>
    <h3>Know that "that" can happen</h3>
    <aside class="notes">
      Don't waste a single neuron on the train of thought that begins "but that can't happen" becuase 
      quite clearly it can and has
    </aside>
  </Slide>
  <Slide>
    <h3>Never throw away a debugging tool</h3>
    <ul>
      <li>Reused in other debugging situations</li>
      <li class="fragment">Good engg techniques</li>
      <li class="fragment">Documentation</li>
    </ul>
    <aside class="notes">
      Sometimes a test tool can be reused in other debugging situations.
      Think about this when you design it, and make it maintainable and upgradeable
      This means using good engg techniques, documentation, etc.
      A tool can be useful in ways that you never would have imagined.

    </aside>
  </Slide>
</Slide>
