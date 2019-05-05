---
title: Visualization approaches for understanding uncertainty in flow diagrams
author: Zana Vosough, Dietrich Kammer, Mandy Keck, Rainer Groh
link: http://doi.org/10.1016/j.cola.2019.03.002
year: 2019
venue: Journal of Computer Languages
bibtex: >-
    @article{VOSOUGH201944,
    title = "Visualization approaches for understanding uncertainty in flow diagrams",
    journal = "Journal of Computer Languages",
    volume = "52",
    pages = "44 - 54",
    year = "2019",
    issn = "2590-1184",
    doi = "https://doi.org/10.1016/j.cola.2019.03.002",
    url = "http://www.sciencedirect.com/science/article/pii/S1045926X18300168",
    author = "Zana Vosough and Dietrich Kammer and Mandy Keck and Rainer Groh",
    keywords = "Uncertainty visualization, Flow diagrams, Sankey diagrams, Parallel sets, Product costing, Business intelligence"}
---
Business Intelligence applications often handle data sets that contain uncertain values. In this contribution, we focus on product costing, which deals with the average costs of product components – that vary significantly based on many factors such as inflation, exchange rates, and commodity prices. After experts estimate the uncertainty information for single items, decision makers need to quickly ascertain the cost uncertainties within the hierarchical data structure of the complete product.

We propose that only a holistic visualization containing both data and uncertainty can provide this kind of quick overview. Such a visualization must be able to visualize tree data structures associated with value attributes. After conducting interviews with product costing experts, we focused on Flow diagrams, which fulfill this basic requirement. However, they need to be extended in order to directly incorporate uncertainty information.

We investigated three visualization techniques applicable to the ribbons of Flow diagrams to convey uncertainty information: Color-code, Gradient, and Margin. Moreover, we designed five visual approaches to show the uncertainty on nodes of Flow diagrams that we evaluated with visualization experts. The approaches add different geometries to the nodes such as triangles, blocks, or forks. The preferred solutions for the nodes was adding forks or filled blocks. With regards to the ribbons, we contribute a user study involving the solution of different product costing tasks using the three different visualizations. Although Gradient was considered an intuitive choice to show uncertainty, it yielded the highest error rates. In contrast, Color-code and Margin were superior depending on the performed task. Based on these findings and the subjective feedback, we designed an integrated approach that combines elements from all three distinct techniques and applied it to Sankey diagrams and Parallel sets.