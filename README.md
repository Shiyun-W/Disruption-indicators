# Knowledge-entity-based disruption indicators
This project is created for providing the main source codes of our latest research "Quantifying scientific breakthroughs by a novel disruption indicator based on knowledge entities" that submitted to JASIST (The Journal of the Association for Information Science and Technology).

# General Information
## Introduction
We propose a novel disruption indicator that differs from prior ones (Funk & Owen-Smith, 2017; Wu et al., 2019; Bornmann et al., 2020) by incorporating both citation patterns and knowledge elements. Specifically, the ego citation network of a focal paper comprising both its references and citations is constructed and employed as proxies for the evolutionary trajectory of the focal paper. Then, the change of knowledge elements created and inspired by the focal paper in its evolutionary trajectory compared to existing research streams can further be measured by comparing the knowledge elements between the focal paper and its citing papers and references.
To validate our disruption indicator in identifying scientific breakthroughs, we apply it to a large-scale PubMed dataset and measures the disruption score of each paper by using MeSH terms and the co-occurrence pairs of MeSH terms as knowledge elements. Since scientific breakthroughs can occur under a variety of circumstances, four test datasets including various types of scientific breakthroughs (The Science-Breakthrough of the Year given annually by Science Journal, key publications of Nobel prize and Lasker Award winners, Annual top 0.1% highly cited papers in PubMed, and Faculty Opinions papers) are compiled as standard scientific breakthroughs. We evaluated the ability of our indicator in distinguishing the standard scientific breakthroughs from non-breakthrough papers in the PubMed dataset and compared the performance of our indicator with several baseline disruption indicators.

## Content
### disruption indicators
This document includes the main source codes for five disruption indicators (three baseline indicators that proposed by previous studies and two new indicators that we proposed)

### Figures and tables
This document includes processing and plotting codes for the main figures and tables in our research.

# References
Funk, R. J., & Owen-Smith, J. (2017). A dynamic network measure of technological change. Management Science, 63(3), 791–817. https://doi.org/10.1287/mnsc.2015.2366\n
Wu, L., Wang, D., & Evans, J. A. (2019). Large teams develop and small teams disrupt science and technology. Nature, 566(7744), 378–382. https://doi.org/10.1038/s41586-019-0941-9\n
Bornmann, L., Devarakonda, S., Tekles, A., & Chacko, G. (2020). Are disruption index indicators convergently valid? The comparison of several indicator variants with assessments by peers. Quantitative Science Studies, 1(3), 1242–1259. https://doi.org/10.1162/qss_a_00068

# Contributors
Shiyun Wang, Yaxue Ma, Jin Mao, Yun Bai, Zhentao Liang, and Gang Li

# Contact
Email: 
wangsy2@whu.edu.cn
mayaxue@nju.edu.cn
danveno@163.com
