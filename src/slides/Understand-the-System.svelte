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
    <h2>Know what's reasonable</h2>
    <ul>
      <li>Know how the system would normally work</li>
      <li>Knowledge of what's normal</li>
      <li>Lack of fundamental understanding</li>
    </ul>
    <aside class="notes">
      When you are looking around in a system, you have to know how the system would normally work
      Knowledge of what's normal helps you notice things thar aren't
      Lack of fundamental understanding explains why so many people have trouble figuring out what's wrong
    </aside>
  </Slide>
  <Slide>
    <h2>Know the road map</h2>
    <p>Constituent elements</p>
    <ul>
      <li>Lay of the land</li>
      <li>Moving parts</li>
      <li>Parts of the system - Black boxes</li>
    </ul>
    <aside class="notes">
      Knowledge of the constituent elements of a system can also give us important insights into the structure of that system
      When you are trying to navigate to where a bug is hiding, you have to know the lay of the land
      When there are parts of the system that are "black boxes", meaning that you don't know what's 
      inside them, knowing how they're supposed to interact with other parts allows you to at least
      locate the problem as being inside the box or outside the box.
    </aside>
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
    <div class="flex gap-2">
      <section>
        <Image height="200" src="assets/einstein.avif" alt="Understand the system" />
        <blockquote>Never memorize something that you can look up</blockquote>
      </section>
      <section>
    <ul>
      <li class="fragment">Don't guess, Look it up</li>
      <li class="fragment">Detailed info has been written down somewhere</li>
      <li class="fragment">Don't trust your memory</li>
    </ul>
          </section>
    <aside class="notes">
      Don't waste your debugging time looking at the wrong stuff
    </aside>
  </Slide>
</Slide>
