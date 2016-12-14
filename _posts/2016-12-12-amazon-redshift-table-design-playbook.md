---
title: Redshift playbook featured in Hadoop Weekly
layout: post
permalink: redshift-advanced-table-design-playbook/
date: '2016-12-12 10:19:35'
---

Recently I published a 5 part content series to the AWS Big Data Blog titled: [Amazon Redshift Engineering's Advanced Table Design Playbook](https://aws.amazon.com/blogs/big-data/amazon-redshift-engineerings-advanced-table-design-playbook-preamble-prerequisites-and-prioritization/). In this series I discuss an in-depth methodology to approach table and column properties such as distribution keys, sort keys, compression encodings, etc. 

My goal for the article was to simplify the process in determining which properties are ideal for a given table/column based on the actual workload. Rather than providing blanket guidance which only helps for the most straight-forward, common, use cases - I attempted to achieve this by providing flow charts that can be followed on a table-by-table or column-by-column basis.  

A sample of these flow charts are below, links to my articles which help to explain the questions follow:
## Flow charts:
### Is a column an appropriate distribution key?
<img src="/images/o_redshift_table_design_1.gif" alt="">

### What DISTSTYLE should my table be?
<img src="/images/o_redshift_table_design_2.gif" alt="">

### Will sorting this table benefit my workload?
<img src="/images/o_redshift_tables_3_1.gif" alt="">

### What sort style should this table use?
<img src="/images/o_redshift_tables_3_2.gif" alt="">

### Will compressing this column benefit my workload?
<img src="/images/o_redshift_tables_4_1.gif" alt="">

## Articles:
[Part 1: Preamble, Prerequisites, and Prioritization](https://aws.amazon.com/blogs/big-data/amazon-redshift-engineerings-advanced-table-design-playbook-preamble-prerequisites-and-prioritization/)

[Part 2: Distribution Styles and Distribution Keys](https://aws.amazon.com/blogs/big-data/amazon-redshift-engineerings-advanced-table-design-playbook-distribution-styles-and-distribution-keys/)

[Part 3: Compound and Interleaved Sort Keys](https://aws.amazon.com/blogs/big-data/amazon-redshift-engineerings-advanced-table-design-playbook-compound-and-interleaved-sort-keys/)

[Part 4: Compression Encodings](https://aws.amazon.com/blogs/big-data/amazon-redshift-engineerings-advanced-table-design-playbook-compression-encodings/)

[Part 5: Table Data Durability](https://aws.amazon.com/blogs/big-data/amazon-redshift-engineerings-advanced-table-design-playbook-table-data-durability/)


## Feedback

Although not specifically related to the Apache Hadoop™ ecosystem. They referenced this Redshift specific series in [Hadoop Weekly #196](https://www.hadoopweekly.com/Hadoop-Weekly-196.html). 

As always, let me know if you have any comments or feedback. 