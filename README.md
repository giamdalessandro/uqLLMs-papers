# Awesome LLM Internals for Hallucination & Uncertainty
This is a self-curated list of papers exploring how we can peek inside LLMs to catch them in the act: using internal signals like hidden states and attention maps to detect hallucinations and quantify uncertainty.
The goal is not to be exhaustive, but to collect work that shares a common thread — that the model often knows more than it lets on, and that the evidence is buried somewhere in its activations.
Papers are loosely grouped by topic. Suggestions and PRs welcome.

## Hallucinations
<table> 
    <thead> <tr> <th>Title</th> <th>Authors</th> <th>Year</th> <th>Focus</th> <th>Links</th> </tr> </thead> 
    <!-- <tbody> 
        <tr><td>
            <em>Why Language Models Hallucinate</em></td> <td>Kalai et al.</td> <td>2025</td> <td> <details> <summary>Show summary</summary> A few lines describing the core ideas. </details> </td> <td> 
            <a href="https://arxiv.org/pdf/2509.04664">PDF</a> · 
            <a href="#">Code</a>
        </td></tr> 
    </tbody> -->
    <tbody> 
        <tr><td>
            <em>Hallucination Detection in LLMs Using Spectral Features of Attention Maps</em></td> <td>Binkowski et al.</td> <td>Oct 2025</td> <td>attenion maps</td> <td> 
            <a href="http://arxiv.org/abs/2502.17598">PDF</a> · 
            <a href="https://github.com/graphml-lab-pwr/lapeigvals">Code</a>
        </td></tr>
        <tr><td>
            <em>LLMs Know More Than They Show: On the Intrinsic Representation of LLM Hallucinations</em></td> <td>Orgad et al.</td> <td>May 2025</td> <td>hidden states</td> <td> <a href="https://arxiv.org/abs/2407.07071">PDF</a> · <a href="https://github.com/technion-cs-nlp/LLMsKnow">Code</a> 
        </td></tr>
        <tr><td>
            <em>INSIDE: LLMs' Internal States Retain the Power of Hallucination Detection</em></td> <td>Chen et al.</td> <td>Oct 2024</td> <td>hidden states</td> <td> <a href="http://arxiv.org/abs/2402.03744">PDF</a> · <a href="#">Code</a> 
        </td></tr>
        <tr><td>
            <em>LLM-Check: Investigating Detection of Hallucinations in Large Language Models</em></td> <td>Sriramanan et al.</td> <td>Oct 2024</td> <td>attention maps, hidden states</td> <td> <a href="https://papers.nips.cc/paper_files/paper/2024/hash/3c1e1fdf305195cd620c118aaa9717ad-Abstract-Conference.html">PDF</a> · <a href="https://github.com/GaurangSriramanan/LLM_Check_Hallucination_Detection">Code</a> 
        </td></tr>
        <tr><td>
            <em>Lookback Lens: Detecting and Mitigating Contextual Hallucinations in Large Language Models Using Only Attention Maps</em></td> <td>Chuang et al.</td> <td>Oct 2024</td> <td>attention maps</td> <td> <a href="https://arxiv.org/abs/2407.07071">PDF</a> · <a href="https://github.com/voidism/Lookback-Lens">Code</a> 
        </td></tr>
        <tr><td>
            <em>Semantic Entropy Probes: Robust and Cheap Hallucination Detection in LLMs</em></td> <td>Chen et al.</td> <td>Jun 2024</td> <td>hidden states</td> <td> <a href="http://arxiv.org/abs/2406.15927">PDF</a> · <a href="#">Code</a> 
        </td></tr>
    </tbody>
</table>


## Uncertainty
<table> 
    <thead> <tr><th>Title</th> <th>Authors</th> <th>Year</th> <th>Focus</th> <th>Links</th> </tr> </thead> 
    <tbody> 
        <tr><td>
            <em>Can Linear Probes Measure LLM Uncertainty?</em></td> <td>Dakhmouche et al.</td> <td>Nov 2025</td> <td>hidden states</td> <td> 
            <a href="http://arxiv.org/abs/2510.04108">PDF</a> · 
            <!-- <a href="#">Code</a>  -->
        </td></tr> 
        <tr><td>
            <em>Uncertainty-Aware Attention Heads: Efficient Unsupervised Uncertainty Quantification for LLMs</em></td> <td>Vazhentsev et al.</td> <td>May 2025</td> <td>attention maps</td> <td> 
            <a href="https://arxiv.org/pdf/2505.20045">PDF</a> · 
            <!-- <a href="#">Code</a> -->
        </td></tr>  
        <tr><td> 
            <em>Uncertainty Estimation and Quantification for LLMs: A Simple Supervised Approach</em></td> <td>Liu et al.</td> <td>2024</td> <td>hidden states</td> <td> 
            <a href="https://arxiv.org/pdf/2404.15993">PDF</a> · 
            <!-- <a href="#">Code</a>  -->
        </td></tr>
        <tr><td>
            <em>Enhancing Uncertainty-Based Hallucination Detection with Stronger Focus</em></td> <td>Zhang et al.</td> <td>Nov 2023</td> <td>attention maps</td> <td> <a href="http://arxiv.org/abs/2311.13230">PDF</a> · 
            <!-- <a href="#">Code</a>  -->
        </td></tr> 
        <tr><td>
            <em>Conformal Prediction with Large Language Models for Multi-Choice Question Answering</em></td> <td>Kumar et al.</td> <td>Jul 2023</td> <td> </td> <td> 
            <a href="https://arxiv.org/pdf/2305.18404">PDF</a> · 
            <!-- <a href="#">Code</a>  -->
        </td></tr>
    </tbody> 
</table>


## Surveys
<table> 
    <thead> <tr> <th>Title</th> <th>Authors</th> <th>Year</th> <th>TLDR</th> <th>Links</th> </tr> </thead>
    <tbody> 
        <tr><td>
            <em>Uncertainty Quantification for Hallucination Detection in Large Language Models: Foundations, Methodology, and Future Directions</em></td> <td>Kang et al.</td> <td>Oct 2025</td> <td> <details> <summary>Show summary</summary> A few lines describing the core ideas. </details> </td> <td> <a href="http://arxiv.org/abs/2510.12040">PDF</a> · 
            <!-- <a href="#">Code</a> -->
        </td></tr> 
        <tr><td>
            <em>A Survey on Uncertainty Quantification of Large Language Models: Taxonomy, Open Research Challenges, and Future Directions</em></td> <td>Shorinwa et al.</td> <td>Dec 2024</td> <td> <details> <summary>Show summary</summary> A few lines describing the core ideas. </details> </td> <td> 
            <a href="https://arxiv.org/pdf/2412.05563">PDF</a> · 
            <!-- <a href="#">Code</a>  -->
        </td></tr> 
        <tr><td>
            <em>Benchmarking LLMs via Uncertainty Quantification</em></td> <td>Ye et al.</td> <td>Oct 2024</td> <td><details> <summary>Show summary</summary> A few lines describing the core ideas. </details></td> <td> 
            <a href="https://arxiv.org/pdf/2401.12794">PDF</a> · 
            <!-- <a href="#">Code</a>  -->
        </td></tr> 
    </tbody> 
</table>


## Bonus
### Attention Sinks
<table> 
    <thead> <tr> <th>Title</th> <th>Authors</th> <th>Year</th> <th>TLDR</th> <th>Links</th> </tr> </thead>
    <tbody> 
        <tr><td>
            <em>What are you sinking? A geometric approach on attention sink</em></td> <td>Ruscio et al.</td> <td>2025</td> <td> <details> <summary>Show summary</summary> A few lines describing the core ideas. </details> </td> <td> <a href="https://arxiv.org/pdf/2508.02546">PDF</a> · 
            <!-- <a href="#">Code</a>  -->
        </td></tr> 
        <tr><td>
            <em>Why do LLMs attend to the first token?</em></td> <td>Barbero et al.</td> <td>2025</td> <td> <details> <summary>Show summary</summary> A few lines describing the core ideas. </details> </td> <td> <a href="https://arxiv.org/pdf/2504.02732">PDF</a> · 
            <!-- <a href="#">Code</a>  -->
        </td></tr> 
        <tr><td>
            <em>Efficient Streaming Language Models with Attention Sinks</em></td> <td>Xiao et al.</td> <td>2024</td> <td> <details> <summary>Show summary</summary> A few lines describing the core ideas. </details> </td> <td> <a href="https://arxiv.org/pdf/2309.17453">PDF</a> · <a href="https://github.com/mit-han-lab/streaming-llm">Code</a>
        </td></tr> 
    </tbody> 
</table> 

<!-- ## MCQA
<table> 
    <thead> <tr> <th>Title</th> <th>Authors</th> <th>Year</th> <th>TLDR</th> <th>Links</th> </tr> </thead> 
    <tbody> 
        <tr><td>
            <em>Right Answer, Wrong Score: Uncovering the Inconsistencies of LLM Evaluation in Multiple-Choice Question Answering</em></td> <td>Molfese et al.</td> <td>2025</td> <td> <details> <summary>Show summary</summary> A few lines describing the core ideas. </details> </td> <td> 
            <a href="https://arxiv.org/abs/2503.14996">PDF</a> · 
            <a href="#">Code</a>
        </td></tr> 
    </tbody>
</table> -->