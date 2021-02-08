## Introduction

  In this experiment, ı implemented a program to solve a real wold machine learning problem with a real world data. In this experiment, ı got familiar Python data science libraries such as; Pandas, NumPy, and Matplotlib. At the end, ı builded 3 types of machine learning models.
  
### Aim of this project

  ♦️ To find the relation between ”TD” metrics with ”internal” and ”external” metrics by using statistical correlation analysis.

  ♦️ Making a TD estimation by using ML Regression models.
  
### What is Technical Debt?

  Technical debt (TD) is a metaphor used to describe the lack of software quality in the product. It provides a valuable indicator to track software product quality throughout development and maintenance. It defines the invariance of delayed technical development activities to receive short-term repayments. The consequences related to these skipped activities are accumulated in the software, and it is called as ’debt.’ If there is too much technical debt that is accumulated, it causes low software quality, pointing to the initiation of design and code quality problems. Because development will slow down, maintainability of the software will be difficult. To fix these quality problems, it requires extra effort for their mitigation. TD is a measure of the effort needed for fixing these problems in the future and used as a measure of quality. Therefore, the higher value of TD for a software product means more unresolved quality problems included in, and lower overall quality. Since measuring TD directly can be difficult, we propose to analyze whether there is a relation between TD with internal and external metrics.
  
### TD metrics that were measured:
  - Metric1: Code Duplication Ratio (CDR): Density of duplicated line of code
  
  - Metric2: Technical Debt (TD):Ratio between the cost to develop the code changed in the new code period and the cost of the issues linked to it 
### External metrics that were measured:

  - Metric3: Number of Bugs (NoB): It gives information about the number of bug
  
  - Metric4: Vulnerabilities (V): It gives information about the number of vulnerability
  
  - Metric5: Security Hotspots (SH): It is about number of security hotspots,
  
  - Metric6: Code Smells (CS): Total count of code smell issues
  
### Internal metrics that were measured:
  - Metric7: Number of Children (NOC): number of subclasses that are linked to a class in the hierarchy
  
  - Metric8: Coupling between Object Classes (CBO): number of classes coupled to a given class
  
  - Metric9: Lack of Cohesion in Methods (LCOM): Let us assume that class C1 has a set of M1, M2,...Mn methods and that the set is a set of attribute variables used in the Mi method. In this case, LCOM is the number of discrete clusters that are the intersection of these n clusters.

  - Metric10: Fanin: a measure of how many other classes use the specific class. It indicates the number of classes to be affected if class changes. It can also be expressed as internal coupling.

  - Metric11: FanOut: Indicates how many classes are coupled on the class being examined. It refers to the external coupling of a class.

  - Metric12: Response for a Class (RFC): number of different methods that can be executed when an object of that class receives a message (when a method is invoked for that object)

  - Metric13: Depth of Inheritance Tree (DIT): maximum level of inheritance hierarchy of a class

  - Metric14: Weighted Method Per Class (WMC): sum of the complexity of all methods of a class

  - Metric15: Line of Code (LOC): It gives information about the size of the software.

  - Metric16: Comment Lines of Code (CLOC): It is the number of comment lines written for the program.
  
