

### RefFinder



Libraries are widely adopted in developing software projects. Library APIs are often missing during library evolution as library developers may deprecate, remove or refactor APIs. As a result, client developers have to manually find replacement APIs for missing APIs when updating library versions in their projects, which is a difficult and expensive software maintenance task. One of the key limitations of the existing automated approaches is that they usually consider the library itself as the single source to find replacement APIs, which heavily limits their accuracy.



In this paper, we first present an empirical study to understand characteristics about missing APIs and their replacements. Specifically, we quantify the prevalence of missing APIs, and summarize the knowledge sources where the replacements are found, and the code change and mapping cardinality between missing APIs and their replacements. Then, inspired by the insights from our study, we propose a heuristic-based approach, REPFINDER, to automatically find replacements for missing APIs in library update. We design and combine a set of heuristics to hierarchically search three sources (deprecation message, own library, and external library) for finding replacements. Our evaluation has demonstrated that REPFINDER can find replacement APIs effectively and efficiently, and significantly outperform the state-of-the-art approaches.



The paper has been submitted to ASE 2021. See our data and code.




