# Assignment14-Decision-Trees
ExcelR Data Science Assignment No 14

### Decision Trees:

* A decision tree is a non-parametric supervised learning algorithm, which is utilized for both classification and regression tasks. It has a hierarchical, tree structure, which consists of a root node, branches, internal nodes and leaf nodes.

#### Important Terminology related to Decision Trees:

1.	Root Node: Root node is from where the decision tree starts. It represents the entire dataset, which further gets divided into two or more homogeneous sets.

2.	Splitting: It is a process of dividing a node into two or more sub-nodes.

3.	Decision Node: When a sub-node splits into further sub-nodes, then it is called the decision node.

4.	Leaf / Terminal Node: Nodes do not split is called Leaf or Terminal node.

5.	Pruning: When we remove sub-nodes of a decision node, this process is called pruning. You can say the opposite process of splitting.

6.	Branch / Sub-Tree: A subsection of the entire tree is called branch or sub-tree.

7.	Parent and Child Node: A node, which is divided into sub-nodes is called a parent node of sub-nodes whereas sub-nodes are the child of a parent node.

### This assignment will study following Questions :

Problem Statement No 1 :

A cloth manufacturing company is interested to know about the segment or attributes causes high sale. 
Approach - A decision tree can be built with target variable Sale (we will first convert it in categorical variable) & all other variable will be independent in the analysis.  

Problem Statement No 2 :

Use decision trees to prepare a model on fraud data. Treating those who have taxable income <= 30000 as "Risky" and others are "Good"
