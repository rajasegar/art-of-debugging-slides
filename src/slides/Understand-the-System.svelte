<script>
  import Slide from '../lib/Slide.svelte';
  import Image from '../lib/Image.svelte';
</script>

<Slide>
  <Slide>
    <h2>#1 Understand the system</h2>
    <div class="flex gap-4">
      <div>
        <Image src="assets/understand-the-system.jpg" alt="Understand the system" />
      </div>
      <div>
        <ul>
          <li class="fragment">Fix problems without really understanding</li>
          <li class="fragment">Make sure you understand the system to the core</li>
          <li class="fragment">Triangulate defect with both cases</li>
        </ul>
      </div>
    </div>
    <aside class="notes">
      The best way to make your life difficult and damage the quality of your program is to fix problems without really understanding them.
      Before you fix a problem, make sure you understand the system to the core.
      Triangulate the defect both with cases that should reproduce the error
      and with cases that shouldn’t reproduce the error.
      Keep at it until you understand the problem well enough to predict its occurrence correctly every time.
    </aside>
  </Slide>
  <Slide>
    <h2>Read the manual</h2>
    <ul>
      <li>Need a working knowledge</li>
      <li>How it's designed?</li>
      <li>Why it was designed that way</li>
    </ul>
    <aside class="notes">
      You need a working knowledge of what the system is supposed to do,
      how it's designed and in some cases, why it was designed that way.
      If you don't understand some part of the system , that always seems to
      be where the problem is.
    </aside>
  </Slide>

  <Slide>
    <h2>Read everything in depth</h2>
    <ul>
      <li>Programming guides & API documentation</li>
      <li>Dig in</li>
      <li>Application Notes</li>
      <li>Implementation guides</li>
      <li>Warnings about common mistakes are incredibly valuable</li>
    </ul>
  </Slide>
  <Slide>
    <h2>Know the fundamentals</h2>
  </Slide>
  <Slide>
    <h2>Know what's reasonable</h2>
  </Slide>
  <Slide>
    <h2>Know the road map</h2>
    <p>Constituent elements</p>
    <ul>
      <li>Moving parts</li>
      <li>Black boxes</li>
    </ul>
    <aside class="notes">Knowledge about the constituent elements of the system can bring in new insights</aside>
  </Slide>
  <Slide>
    <h2>Understand your tools</h2>
    <ul>
      <li>Debugging tools &rarr; Eyes and ears</li>
      <li>Right tool</li>
      <li>Use it correctly</li>
      <li>Interpret the results properly</li>
      <li>Limitations</li>
    </ul>
    <aside class="notes">
      Your debugging tools are your eyes and ears into the system:
      you have to be able to choose the right tool
      use the tool correctly
      and intepret the results you get properly
      You also have to know the limitations of your tools
    </aside>
  </Slide>
  <Slide>
    <h2>Look up the details</h2>
    <aside class="notes">
      Don't waste your debugging time looking at the wrong stuff
    </aside>
  </Slide>
</Slide>
