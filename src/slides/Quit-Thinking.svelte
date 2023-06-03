<script>
 import Slide from '../lib/Slide.svelte';
 import Image from '../lib/Image.svelte';
</script>

<Slide>
<Slide>
    <h1>#3</h1>
  <h2>Quit Thinking and Look</h2>
  <Image src="assets/quit-thinking.jpg" alt="Quit thinking" />
  <ul>
    <li>Looking is hard</li>
  </ul>
  <aside class="notes">
    It is a capital mistake to theorize before one has data.
    All engineers are thinkers.
    Engineers like to think
    It's fun thing to do and sure it beats physical labor
    that's why we became engineers in the first place

    Looking is hard.
    Looking is often, if not always, more complicated than we would like

  </aside>

</Slide>
<Slide>
  <h3>See the failure</h3>
  <ul>
    <li>Look closely to see enough detail</li>
    <li>Easily misinterpreted</li>
  </ul>
  <aside class="notes">
    You have to look closely to see the failure in enough detail to debug
    Many problems are easily misinterpreted if you can't see all the way
    to what's actually happening.
  </aside>

</Slide>

<Slide>
  <h3>See the details</h3>
  <Image src="assets/Looking+under+the+lamppost.avif" alt="Quit thinking" />
  <ul>
    <li>Each time you learn more</li>
    <li class="fragment">Decide where to look even deeper</li>
    <li class="fragment">When should I stop?</li>
  </ul>
  <aside class="notes">
    There's something called "The Streetlight effect"
    it's a metaphor for knowledge and ignorance
More typically, each time you look into the system to see the failure,
    you learn more about what's failing.
    This will help  you decide where to look even deeper to get more detail
    Eventually you get enough detail that it makes sense to look at the design and
    figure out what the cause of the problem is
    How deep should you go before you stop looking and start thinking again?
    Keep looking until the failure you can see has a limited number of possible causes to examine
  </aside>
</Slide>
<Slide>
  <h3>Build instrumentation in</h3>
  <Image src="assets/log-well-live-well.webp" alt="Log well live well" />

</Slide>
<Slide>
  <h3>Add instrumentation on</h3>
</Slide>
<Slide>
  <h3>Don't be afraid to dive in</h3>
</Slide>
<Slide>
  <h3>Watch out for Heisenberg</h3>
</Slide>
<Slide>
  <h3>Guess only to focus the search</h3>
</Slide>
</Slide>
