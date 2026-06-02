# Do We Always Need AI Frameworks? The Case For In House Production Code (UNFINISHED)
<p align="center">
  <strong>June 1, 2026</strong> &nbsp;|&nbsp; 
  <strong>Leila Wolfe</strong> &nbsp;|&nbsp; 
  <strong>4-minute read</strong>
</p>

Harness Engineering has been the focus of AI in 2026. How can we build a reliable and production grade framework around our LLM applications. Many have gravitated towards frameworks like LangChain, LangGraph, CrewAi and LlamaIndex. However, I argue that in many cases, it is more beneficial to use in house code. Tell a story here

 Many senior engineers are actively moving away from heavy abstraction layers (like LangChain or LlamaIndex) in favor of writing lightweight, native, in-house API integrations

## Pro Frameworks:
* Standardize workflows and tech stack across teams and developers
* Quick to start up/Plug and play - Great for prototyping
* Provide many useful features natively - saving development time
* Community backing (contributors)
* Specialized labor (can find people familiar with the tool and can onboard devs quickly)
* Junior to immediate experience developers could likely pick up
* Tooling credibility

## Cons Frameworks:
* Bloat (not all features are necessary)
* May need to use multiple frameworks to fit all requirements of your project
* May not be adaptable to your project
* Compatibility issues with other libraries and frameworks
* May end up coding workarounds that can be clunky
* Need multiple frameworks to address security issues, silent failures, and observability
* High maintainability - api breaks to keep up with updates
* Wait for developers to write features required or to fix bugs
* Framework abstractions can cause black box issues - like seeing exactly what prompts are sent and how many tokens are used

## Pro In-House Code
* Full control over code. Customizability as needed
* Less costly long-term
* Ensure production grade
* Ensure compatibility
* Ensure security
* Potential less corporate and legal pushback
* Deterministic Reliability

## Con In-House Code
* More time-consuming - longer development time
* More planning time required
* Experienced developer required. Senior, Lead, or Architect is required to design the architecture
* Will be big lift if a prototype or POC has not been coded first to prove value of the project. 
* Reinventing the wheel (complicated algorithms)

## When to use?


## References
1. Wang, Y., Xu, X., Chen, J., Bi, T., Gu, W., & Zheng, Z. (2025). An empirical study of agent developer practices in ai agent frameworks. arXiv preprint arXiv:2512.01939.
2. Goyal, D. and Gautam, A. (2025). Introduction to LangChain Framework. In Textual Intelligence (eds M. Malik, P. Sharma and S. Hooda). https://doi.org/10.1002/9781394287499.ch11
3. B. Tural, Z. Örpek and Z. Destan, "Future AI Tools: LLM and Frameworks," 2025 9th International Symposium on Multidisciplinary Studies and Innovative Technologies (ISMSIT), Ankara, Turkiye, 2025, pp. 1-6, doi: 10.1109/ISMSIT67332.2025.11267968.
