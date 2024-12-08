<script lang="ts">
    import type { PageData } from './$types';

    let { data }: { data: PageData } = $props();
</script>

<h1>Technical aspects of Vincoin</h1>

<div>
    <img src="/images/vincoin4.png" width="100" alt="coins" />
    <img src="/images/vincoin5.png" width="100" alt="coins" />
</div>

<p>Learn more about architectural basics before diving into more complex aspects of Vincoin</p>

<h2>Post quantum cryptography</h2>
<p>Compared to all the cryptography contained in Bitcoin, Vincoin took radically different approach.</p>
<p>Yes, it's born in 2018 so it had plenty of time to observe <a href="https://www.nist.gov/">NIST</a> efforts in formulating quantum resistant algorithms, which explains VINCOIN tendention to use only quantum resistant algorithms and nothing more.</p>
<p>With that huge difference in architecture, naturally many technical aspect of Vincoin are different from the beginning.</p>


<h2>Data processing (aka mining)</h2>
<h2>Data storage (aka blockchain)</h2>
<h2>System-user interaction (aka wallet)</h2>
<h2>Data integrity</h2>
<p>Above all, VINCOIN does apply some of the ZKP scheme, allowing it's users even more possibilities and use cases.</p>

<h2>Open sourced</h2>
<p><code>Vincoin</code> is completely open sourced, released under MIT license.</p>
<p>Feel free to browse our <a href="https://github.com/vexy/vincoin">Github repo</a> (<i>stick to the development branch</i>). Contributions are more than welcome 🙌</p>
<p><b>Please note:</b><i>VINCOIN is in (very!) early stages of it's development, so expect <b>a lot</b> of changes and adjustments</i></p>

<style>
    div {
        display: flex;
        justify-content: center;
        gap: 1rem;
    }
</style>