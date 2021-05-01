<h1 style="text-align: center;"><strong>How to explain object-oriented programming concepts to a 6-year-old</strong></h1>
<figure class="post-full-image"><img srcset="https://cdn-media-1.freecodecamp.org/images/1*EirXoYV7GgRi4frvcW-b0A.jpeg 300w,
                            https://cdn-media-1.freecodecamp.org/images/1*EirXoYV7GgRi4frvcW-b0A.jpeg 600w,
                            https://cdn-media-1.freecodecamp.org/images/1*EirXoYV7GgRi4frvcW-b0A.jpeg 1000w,
                            https://cdn-media-1.freecodecamp.org/images/1*EirXoYV7GgRi4frvcW-b0A.jpeg 2000w" sizes="(max-width: 800px) 400px,
                            (max-width: 1170px) 700px,
                            1400px" src="https://cdn-media-1.freecodecamp.org/images/1*EirXoYV7GgRi4frvcW-b0A.jpeg" alt="How to explain object-oriented programming concepts to a 6-year-old" onerror="this.style.display='none'" /></figure>
<section class="post-full-content">
<div class="post-content medium-migrated-article">
<p>Have you noticed how the same cliche questions always get asked at job interviews &mdash; over and over again?</p>
<p>I&rsquo;m sure you know what I mean.</p>
<p>For example:</p>
<blockquote>Where do you see yourself in five years?</blockquote>
<p>or, even worse:</p>
<blockquote>What do you consider to be your greatest weakness?</blockquote>
<p>Ugh&hellip;give me a break. I consider answering this question a great weakness! Anyway, not my point.</p>
<p>As trivial as questions like these may be, they are important because they give clues about you. Your current state of mind, your attitude, your perspective.</p>
<p>When answering, you should be careful, as you may reveal something you later regret.</p>
<p>Today I want to talk about a similar type of question in the programming world:</p>
<blockquote>What are the main principles of Object-Oriented Programming?</blockquote>
<p>I&rsquo;ve been on both sides of this question. It&rsquo;s one of those topics that gets asked so often that you can&rsquo;t allow yourself to not know.</p>
<p>Junior and entry-level developers usually have to answer it. Because it&rsquo;s an easy way for the interviewer to tell three things:</p>
<ol>
<li><strong>Did the candidate prepare for this interview?</strong><br />Bonus points if you hear an answer immediately &mdash; it shows a serious approach.</li>
<li><strong>Is the candidate past the tutorial phase?</strong><br />Understanding the principles of Object-Oriented Programming (OOP) shows you&rsquo;ve gone beyond copy and pasting from tutorials &mdash; you already see things from a higher perspective.</li>
<li><strong>Is the candidate&rsquo;s understanding deep or shallow?</strong><br />The level of competence on this question often equals the level of competence on<span>&nbsp;</span><strong>most other subjects</strong>. Trust me.</li>
</ol>
<p>The four principles of object-oriented programming are<span>&nbsp;</span><strong>encapsulation</strong>,<span>&nbsp;</span><strong>abstraction</strong>,<span>&nbsp;</span><strong>inheritance</strong>,<strong><span>&nbsp;</span></strong>and<span>&nbsp;</span><strong>polymorphism</strong>.</p>
<p>These words may sound scary for a junior developer. And the complex, excessively long explanations in Wikipedia sometimes double the confusion.</p>
<p>That&rsquo;s why I want to give a simple, short, and clear explanation for each of these concepts. It may sound like something you explain to a child, but I would actually love to hear these answers when I conduct an interview.</p>
<h3 id="encapsulation">Encapsulation</h3>
<p>Say we have a program. It has a few logically different objects which communicate with each other &mdash; according to the rules defined in the program.</p>
<p>Encapsulation is achieved when each object keeps its state<span>&nbsp;</span><strong>private</strong>, inside a class. Other objects don&rsquo;t have direct access to this state. Instead, they can only call a list of public functions &mdash; called methods.</p>
<p>So, the object manages its own state via methods &mdash; and no other class can touch it unless explicitly allowed. If you want to communicate with the object, you should use the methods provided. But (by default), you can&rsquo;t change the state.</p>
<p>Let&rsquo;s say we&rsquo;re building a tiny Sims game. There are people and there is a cat. They communicate with each other. We want to apply encapsulation, so we encapsulate all &ldquo;cat&rdquo; logic into a<span>&nbsp;</span><code>Cat</code><em><span>&nbsp;</span></em>class. It may look like this:</p>
<figure class="kg-card kg-image-card kg-card-hascaption"><img src="https://cdn-media-1.freecodecamp.org/images/M4t8zW9U71xeKSlzT2o8WO47mdzrWkNa4rWv" class="kg-image" alt="" /></figure>
</div>
<p><strong>Structured programming</strong><span>&nbsp;</span>is a programming paradigm aimed at improving the clarity, quality, and development time of a computer program by making extensive use of the structured control flow constructs of selection (if/then/else) and repetition (while and for), block structures, and subroutines in contrast to using simple tests and jumps such as the go to statement, which can lead to &ldquo;<strong>spaghetti code</strong>&rdquo; that is potentially difficult to follow and maintain.<a class="footnote" title="Wikipedia: Structured programming" id="return-footnote-196-1" href="https://press.rebus.community/programmingfundamentals/chapter/structured-programming/#footnote-196-1" aria-label="Footnote 1"><sup class="footnote">[1]</sup></a></p>
<h2>Discussion</h2>
<p>One of the most important concepts of programming is the ability to control a program so that different lines of code are executed or that some lines of code are executed many times. The mechanisms that allow us to control the flow of execution are called&nbsp;<strong>control structures</strong>. Flowcharting is a method of documenting (charting) the flow (or paths) that a program would execute. There are three main categories of control structures:</p>
<ul>
<li><strong>Sequence</strong>&nbsp;&ndash; Very boring. Simply do one instruction then the next and the next. Just do them in a given sequence or in the order listed. Most lines of code are this.</li>
</ul>
<ul>
<li><strong>Selection</strong>&nbsp;&ndash; This is where you select or choose between two or more flows. The choice is decided by asking some sort of question. The answer determines the path (or which lines of code) will be executed.</li>
</ul>
<ul>
<li><strong>Iteration</strong>&nbsp;&ndash; Also known as repetition, it allows some code (one to many lines) to be executed (or repeated) several times. The code might not be executed at all (repeat it zero times), executed a fixed number of times or executed indefinitely until some condition has been met. Also known as looping because the flowcharting shows the flow looping back to repeat the task.</li>
</ul>
<p>A fourth category describes unstructured code.</p>
<ul>
<li><strong>Branching</strong>&nbsp;&ndash; An uncontrolled structure that allows the flow of execution to jump to a different part of the program. This category is rarely used in modular structured programming.</li>
</ul>
<p>All high-level programming languages have control structures. All languages have the first three categories of control structures (sequence, selection, and iteration). Most have the&nbsp;if then else&nbsp;structure (which belongs to the selection category) and the&nbsp;while structure (which belongs to the iteration category). After these two basic structures, there are usually language variations.</p>
<p>The concept of&nbsp;<strong>structured programming</strong>&nbsp;started in the late 1960&rsquo;s with an article by Edsger Dijkstra. He proposed a &ldquo;go to less&rdquo; method of planning programming logic that eliminated the need for the branching category of control structures. The topic was debated for about 20 years. But ultimately &ndash; &ldquo;By the end of the 20th century nearly all computer scientists were convinced that it is useful to learn and apply the concepts of structured programming.&rdquo;<a class="footnote" title="Wikipedia: Structured programming" id="return-footnote-196-2" href="https://press.rebus.community/programmingfundamentals/chapter/structured-programming/#footnote-196-2" aria-label="Footnote 2"><sup class="footnote">[2]</sup></a></p>
<h2>Key Terms</h2>
<dl>
<dt>branching</dt>
<dd>An uncontrolled structure that allows the flow of execution to jump to a different part of the program.</dd>
</dl>
<dl>
<dt>control structures</dt>
<dd>Mechanisms that allow us to control the flow of execution within a program.</dd>
</dl>
<dl>
<dt>iteration</dt>
<dd>A control structure that allows some lines of code to be executed many times.</dd>
</dl>
<dl>
<dt>selection</dt>
<dd>A control structure where the program chooses between two or more options.</dd>
</dl>
<dl>
<dt>sequence</dt>
<dd>A control structure where the program executes the items in the order listed.</dd>
</dl>
<dl>
<dt>spaghetti code</dt>
<dd>A pejorative phrase for unstructured and difficult to maintain source code.<a class="footnote" title="Wikipedia: Spaghetti code" id="return-footnote-196-3" href="https://press.rebus.community/programmingfundamentals/chapter/structured-programming/#footnote-196-3" aria-label="Footnote 3"><sup class="footnote">[3]</sup></a></dd>
</dl>
<dl>
<dt>structured programming</dt>
<dd>A method of planning programs that avoids the branching category of control structures.</dd>
</dl>
<li><a href="accesibility_standars.html">Accesibility Standars</a></li>
<li><a href="internet_security.html">Internet Security</a></li>
<li><a href="digital_signature.html">Digital Signature</a></li>
