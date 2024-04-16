<pre><span class="pl-ent">&lt;?php</span>

<span class="pl-k">namespace</span> <span class="pl-v">Wakkarkhan</span>;

<span class="pl-k">class</span> <span class="pl-v">About</span> <span class="pl-k">extends</span> <span class="pl-v">Me</span>
{
    <span class="pl-k">public</span> <span class="pl-k">function</span> <span class="pl-en">getBio</span>(): <span class="pl-smi">string</span>
    {
        <span class="pl-k">return</span> <span class="pl-s">'I m a software developer specializing in PHP and JavaScript.</span>
<span class="pl-s">                I develop modern technology web applications with popular frameworks like Laravel, Vue and React.</span>
<span class="pl-s">                SaaS,</span>
<span class="pl-s">                Multi-Tenancy,</span>
<span class="pl-s">                E-Commerce,</span>
<span class="pl-s">                RestFull API</span>
<span class="pl-s">                I develop advanced software with software architectures.</span>;
    } 

    <span class="pl-k">public</span> <span class="pl-k">function</span> <span class="pl-en">getMore</span>(): <span class="pl-smi">array</span>
    {
        <span class="pl-k">return</span> [
            <span class="pl-s">'work'</span> =&gt; [
                <span class="pl-s">'Software Developer - Codematics'</span>,
                <span class="pl-s">'Frontend Developer - Propertise'</span>,
            ]
        ];
    }

    <span class="pl-k">public</span> <span class="pl-k">function</span> <span class="pl-en">getCurrentState</span>(): <span class="pl-smi">array</span> 
    {
        <span class="pl-k">return</span> [
            <span class="pl-s">'working_on'</span> =&gt; [
                <span class="pl-s">'Propertise - Cloud-based property management software (SaaS)'</span>,
                <span class="pl-s">'Ecommerce - Livewire eccomerce application'</span>
            ],
            <span class="pl-s">'learning'</span> =&gt; [
                <span class="pl-s">'Advance Programing Techniques'</span>,
                <span class="pl-s">'Goo Lang'</span>
            ]
        ];
    }

    <span class="pl-k">public</span> <span class="pl-k">function</span> <span class="pl-en">getFutureGoal</span>(): <span class="pl-smi">string</span>
    {
        <span class="pl-k">return</span> <span class="pl-s">'To contribute to open source.'</span>;
    }
}</pre>
