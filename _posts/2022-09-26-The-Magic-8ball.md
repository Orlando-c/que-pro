---
keywords: fastai
title: Title
nb_path: _notebooks/2022-09-26-The-Magic-8ball.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-09-26-The-Magic-8ball.ipynb
-->

<div class="container" id="notebook-container">
        
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="err">$</span><span class="p">(</span><span class="n">document</span><span class="p">)</span><span class="o">.</span><span class="n">ready</span><span class="p">(</span><span class="n">function</span><span class="p">()</span> <span class="p">{</span>

<span class="n">var</span> <span class="n">magic8ball</span> <span class="o">=</span> <span class="p">{};</span>
<span class="n">magic8ball</span><span class="o">.</span><span class="n">listOfAnswers</span> <span class="o">=</span> <span class="p">[</span><span class="s2">&quot;No&quot;</span><span class="p">,</span> <span class="s2">&quot;Yes&quot;</span><span class="p">,</span> <span class="s2">&quot;I don&#39;t think so...&quot;</span><span class="p">,</span> <span class="s2">&quot;Theres a chance&quot;</span><span class="p">,</span> <span class="s2">&quot;Maybe &quot;</span><span class="p">,</span> <span class="s2">&quot;Of course!&quot;</span><span class="p">,</span> <span class="s2">&quot;Indubitably&quot;</span><span class="p">,</span> <span class="s2">&quot;In your dreams.&quot;</span><span class="p">];</span>

<span class="n">var</span> <span class="n">question</span> <span class="o">=</span> <span class="n">window</span><span class="o">.</span><span class="n">prompt</span><span class="p">(</span><span class="s2">&quot;What is your question?&quot;</span><span class="p">);</span>
<span class="n">document</span><span class="o">.</span><span class="n">write</span><span class="p">(</span><span class="s2">&quot;You wrote&quot;</span> <span class="o">+</span> <span class="n">question</span><span class="p">);</span>

<span class="n">var</span> <span class="n">randomNumber</span> <span class="o">=</span> <span class="n">Math</span><span class="o">.</span><span class="n">random</span><span class="p">();</span>

<span class="n">var</span> <span class="n">randomNumberForListOfAnswers</span> <span class="o">=</span> <span class="n">randomNumber</span> <span class="o">*</span> <span class="n">this</span><span class="o">.</span><span class="n">listOfAnswers</span><span class="o">.</span><span class="n">length</span><span class="p">;</span>

<span class="n">var</span> <span class="n">randomIndex</span> <span class="o">=</span> <span class="n">Math</span><span class="o">.</span><span class="n">floor</span><span class="p">(</span><span class="n">randomNumberForListOfAnswers</span><span class="p">);</span>

<span class="n">var</span> <span class="n">answer</span> <span class="o">=</span> <span class="n">this</span><span class="o">.</span><span class="n">listOfAnswers</span><span class="p">[</span><span class="n">randomIndex</span><span class="p">];</span>

<span class="err">$</span><span class="p">(</span><span class="s2">&quot;#answer&quot;</span><span class="p">)</span><span class="o">.</span><span class="n">text</span><span class="p">(</span><span class="n">answer</span><span class="p">);</span>

<span class="p">});</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

</div>
 
