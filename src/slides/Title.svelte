<script>
    import { onMount } from 'svelte';
    import Slide from '../lib/Slide.svelte';
  import Image from '../lib/Image.svelte';
</script>

<Slide>
    <Slide>
        <h1>The <span class="text-yellow-500">Golden</span> Rules of Debugging</h1>
        <h4>Rajasegar</h4>
    </Slide>
    <Slide>
        <p><span class="text-7xl">"</span>Debugging is the process of identifying the root cause of an error and correcting it.</p>
        <p class="text-right">-- Steve McConnel, Code Complete</p>
    </Slide>
    <Slide>
        <h3>Actually, it's an</h3>
        <h1 class="text-yellow-500">opportunity</h1>
    </Slide>
    <Slide>
        <h3>An opportunity to learn about:</h3>
        <ul>
            <li>program you’re working on</li>
            <li>kinds of mistakes you make</li>
            <li>quality of your code from the readability perspective</li>
            <li>how you solve problems</li>
            <li>how you fix defects</li>
        </ul>
    </Slide>
    <Slide>
        <h3>The Debugging Mindset</h3>
        <ul>
            <li class="fragment">Adopt the right mindset</li>
            <li class="fragment">Turn off the defenses to protect your ego</li>
            <li class="fragment">Tune out any project pressures</li>
            <li class="fragment">Get comfortable</li>
        </ul>
    </Slide>
        <Slide>
        <h3>The First Rule of debugging</h3>
        <Image src="/assets/The-first-rule-of-Fight-Club-is.jpg" alt="the first rule"/>
        <h1>Don't Panic</h1>
    </Slide>
</Slide>
