# Kotlin Data Science Resources
### Libraries, media, links, and other resources to use Kotlin for data science applications


![](https://camo.githubusercontent.com/705d7144bcce5b0fcb68ea1bd563837bdf3398da/687474703a2f2f692e696d6775722e636f6d2f763346716945412e706e67)

This document serves as an awesome-like curation of helpful links in using Kotlin for data science/data engineering/machine learning/optimization purposes. Please feel free to put in PR's with other links you find helpful. 

Data Science is a [broad, buzzwordy](https://towardsdatascience.com/data-science-has-become-too-vague-538899bab57) domain that seeks to gain insight from data. Arguably, [optimization and operations research](https://cs.stackexchange.com/questions/71525/data-science-vs-operations-research) algorithms play a role in this space as well. While the incumbent programming tools in data science are [R](https://www.r-project.org/), [Python](https://www.python.org/), and even [Scala](http://www.scala-lang.org/), there is a [large opportunity for Kotlin](https://www.youtube.com/watch?v=J8GYPG6pt5w) to enter this space. Kotlin can add value by closing the gap between data science and software engineering, and essentially finish what Scala started. 

With [Kotlin/Native](https://kotlinlang.org/docs/reference/native-overview.html) on the horizon, the scope of this document will hopefully expand beyond the JVM. 

# Showcases

Open-source applications and proof-of-concepts demonstrating data science modeling with Kotlin. 

|Project|Description|
|---|---|
|[Kotlin Machine Learning Demos](https://github.com/thomasnield/kotlin-machine-learning-demos)|A simple demo with from-scratch Kotlin machine learning algorithms, as well as library implementations|
|[Kotlin Math Cheatsheet](https://github.com/thomasnield/kotlin_math_cheatsheet/blob/master/README.md)|How to turn mathematical symbol expressions into Kotlin code|
|[Traveling Salesman Problem](https://github.com/thomasnield/traveling_salesman_demo)|A visual Kotlin demo of the [Traveling Salesman Problem](https://en.wikipedia.org/wiki/Travelling_salesman_problem)|
|[Customer Wait Time Simulator](https://github.com/thomasnield/poisson-optimizer-and-simulator)|A simulation of customer wait time for a specified number of cashiers and rates of processing/arrival
|[Bayes Email Spam Filter](https://github.com/thomasnield/bayes_email_spam)|A Kotlin proof-of-concept implementation of a spam filter
|[Bayes User Input Prediction](https://github.com/thomasnield/bayes_user_input_prediction)|A simple TornadoFX app that predicts user inputs using Naive Bayes text categorization
|[Sudokus and Schedules](https://towardsdatascience.com/sudokus-and-schedules-60f3de5dfe0d)|An article on using Kotlin to solve Sudokus and scheduling problems from scratch|
|[Linear Regression](https://github.com/thomasnield/kotlin_linear_regression)|Different algorithms for linear regression written and visualized with Kotlin/TornadoFX|
|[Kotlin Simple Logistic Regression](https://gist.github.com/thomasnield/6f7d1cb8ab0faa839299cfdbbb70d860)|A logistic regression from scratch in Kotlin|
|[Kotlin K-Means Clustering](https://gist.github.com/thomasnield/b083058f34d8428df5734c97a8c10e0c)|A simple K-means clustering of points|
|[Classroom Scheduler](https://github.com/thomasnield/optimized-scheduling-demo)|A discrete programming model that schedules classes against one classroom|
|[Sudoku Solver](https://github.com/thomasnield/kotlin-sudoku-solver/blob/master/README.md)|A showcase of constraint programming and discrete optimization|
|[Driver Shift Optimizer](https://github.com/thomasnield/continuous-optimization-example)|A  linear programming model using ojAlgo to minimze the cost of driver shifts in a day
|[Federated Learning - Building an Android ML App](https://proandroiddev.com/federated-learning-e79e054c33ef)|Showcase of an Android app recognizing images using DL4J|
|[Kubed Map Visualization](https://medium.com/@hudsonb/lets-make-a-visualization-choropleth-map-f2a90a82f9b6)|A U.S. heat map of unemployment rates|


# Kotlin Libraries

|Library Name|Category|Description
|---|---|---|
|[Kotlin-Statistics](https://github.com/thomasnield/kotlin-statistics)|Analytics|Idiomatic statistical/analytical extension functions for Kotlin|
|[KMath](https://github.com/altavir/kmath)|Math/Linear Algebra|Kotlin mathematical library analogous to NumPy|
|[okAlgo](https://github.com/optimatika/okAlgo)|Optimization|Kotlin extensions to [ojAlgo](https://github.com/optimatika/ojAlgo)|
|[Data2Viz](http://data2viz.io/)|Charts|Cross-platform charts and visuals for Kotlin|
|[Sparklin](https://github.com/khud/sparklin)|Scaled Data Processing|Kotlin framework for Apache Spark|
|[Krangl](https://github.com/holgerbrandl/krangl)|Analytics|[dplyr](https://github.com/tidyverse/dplyr)-like data frame wrangling for Kotlin|
|[Koma](https://github.com/kyonifer/koma)|Computation|Scientific library for Kotlin with interop/multiplatform capabilities|
|[Komputation](https://github.com/sekwiatkowski/komputation)|Deep Learning|Neural network platform for Kotlin, primarily for text processing|
|[KotlinNLP](https://github.com/KotlinNLP)|Natural Language Processing|Natural Language Processing framework for Kotlin|
|[TornadoFX](https://www.gitbook.com/book/edvin/tornadofx-guide/details)|UI, Charts|Kotlin UI desktop app framework, built on top [JavaFX](https://docs.oracle.com/javase/8/javafx/get-started-tutorial/jfx-overview.htm)|
|[TornadoFX-ControlsFX](https://github.com/edvin/tornadofx-controlsfx)|UI|[ControlsFX](http://fxexperience.com/controlsfx/features/) extensions with more data views and controls for TornadoFX|
|[Kotlin Jupyter](https://github.com/ligee/kotlin-jupyter)|Notebook|Kotlin support for Jupyter|
|[JINX](https://exceljava.com/docs/tutorials/kotlin.html)|Plugin|Create Excel functions with Java/Scala/Kotlin instead of VBA|
|[Kotlin Algorithm](https://github.com/gazolla/Kotlin-Algorithm#machine-learning)|Algorithm|Kotlin algorithm implementations|

# Java Libraries

|Library Name|Category|Description|
|---|---|---|
|[DeepLearning4J](https://deeplearning4j.org/)|Deep Learning|Deep learning library for Java|
|[ND4J](http://nd4j.org/)|Computation|Efficient matrix math library for JVM|
|[TableSaw](https://github.com/jtablesaw/tablesaw)|DataFrame|Tabular data processing and manipulation|
|[Joinery](https://cardillo.github.io/joinery/v1.8/api/reference/joinery/DataFrame.html)|DataFrame|Tabular data processing and manipulation|
|[Kubed](https://github.com/hudsonb/kubed)|Visualization|JavaFX-based, [D3.js](https://d3js.org/)-like visualizations|
|[Dex](https://github.com/PatMartin/Dex)|Charting|Java-based data visualization tool|
|[JSoup](https://jsoup.org/)|Data Wrangling|HTML parsing library for Java|
|[Smile](https://github.com/haifengl/smile)|ML and analytics|Comprehensive machine learning, NLP, linear algebra, graph, interpolation, and visualization system|
|[ojAlgo!](http://www.ojalgo.org/)|LP and Optimization|Helpful library for linear/mixed optimization and linear algebra
|[Apache Commons Math](http://commons.apache.org/proper/commons-math/)|Math/Statistics/ML|General math, statistics, and ML library for Java|
|[Apache Commons IO](https://commons.apache.org/proper/commons-io/)|IO|IO Utilities|
|[JBlas](https://github.com/mikiobraun/jblas)|Linear Algebra|Linear Algebra for Java|
|[OptaPlanner](https://www.optaplanner.org/)|Optimization|Solver utility for optimization planning problems|
|[Charts](https://github.com/HanSolo/charts)|Charting|Scientific JavaFX charting library in development|
|[CoreNLP](https://stanfordnlp.github.io/CoreNLP/)|Natural Language Processing|Natural language processing toolkit|
|[Renjin](https://en.wikipedia.org/wiki/Renjin)|Interop|R JVM implementation|
|[Apache Mahout](https://mahout.apache.org/)|Linear Algebra|Distributed framework for regression, clustering and recommendation|
|[Weka](https://www.cs.waikato.ac.nz/ml/index.html)|Data Mining Software|Collection of machine learning algorithms for data mining tasks|
|[Apache MXNet](https://mxnet.apache.org/)|Deep Learning Framework|Deep learning framework with a Java API (inference only)|

# Resources for Python Developers

If you already are proficient in Python but want to learn Kotlin and its potential on the data science domain. 

|Name|Media|Topic|Description|
|---|---|---|---|
|[From Data Science to Production with Kotlin (O'Reilly)](https://www.safaribooksonline.com/library/view/from-data-science/9781491998205/)|Video|Kotlin|Trains Python data science professionals transitioning to Kotlin|
|[Kotlin for Data Science (KotlinConf)](https://www.youtube.com/watch?v=J8GYPG6pt5w)|Video|Kotlin|KotlinConf session explaining the merits of Kotlin for data science|
|[Kotlin for Python Programmers](https://khan.github.io/kotlin-for-python-developers/)|Document|Kotlin|A thorough documentation of Kotlin for Python devs|


# Resources for Kotlin Developers

If you are a veteran JVM/Kotlin developer trying to break into the broad, buzzwordy domain of "data science".

|Name|Media|Topic|Description|
|---|---|---|---|
|[Brandon Rohrer](https://brohrer.github.io/blog.html)|Blog|ML|Excellent videos and articles on machine learning topics|
|[3Blue1Brown](https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)|Video|Math, ML, etc|Excellent YouTube channel visually covering mathematical concepts, including [linear algebra](https://www.youtube.com/watch?v=fNk_zzaMoSs&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) and [neural networks](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)|
|[Thomas Nield](https://www.youtube.com/playlist?list=PLYDlqiU6gadsBEHh-N861iWcBzazs4sEU)|Video|ML, Optimization|Thomas Nield's YouTube channel covering ML and optimization topics, all in Kotlin!|
|[PatrickJMT](http://patrickjmt.com/)|Video|Math, Linear Algebra|Patrick is the most comprehensive and effective math tutor on YouTube|
|[An Intuitive Introduction to Probability](https://www.coursera.org/learn/introductiontoprobability/home/info)|Online class|Probability|A short but excellent beginner class introducing probability and its applications|
|[Discrete Optimization (Coursera)](https://www.coursera.org/learn/discrete-optimization/)|Online Class|Optimization|Deep dive class into search algorithms, optimizatoin, as well as linear/integer programming|
|[No BS Guide to Math and Physics](http://www.lulu.com/shop/ivan-savov/no-bullshit-guide-to-math-and-physics/paperback/product-23632949.html)|Book|Math|A helpful and unassuming book to learn high school/college math as well as calculus.|
|[No BS Guide to Linear Algebra](https://gumroad.com/l/noBSLA)|Book|Math|A helpful and unassuming book to learn linear algebra|
|[Make Your Own Neural Network](https://www.amazon.com/Make-Your-Own-Neural-Network/dp/1530826608/)|eBook|ML|A gentle introduction to neural networks|
|[Grokking Deep Learning](https://www.manning.com/books/grokking-deep-learning)|Book|ML|A thorough but practical "from scratch" approach to learning neural networks|
|[Python for the Busy Java Developer](https://www.apress.com/us/book/9781484232330)|Book|Python|Helpful resource for Java devs to learn Python quickly|
|[Data Science with Java (O'Reilly)](http://shop.oreilly.com/product/0636920043171.do)|Book|Data Science|Teaches data science for Java developers|
|[Mastering Java for Data Science (Packt)](https://www.amazon.com/Mastering-Java-Data-Science-production-ready/dp/1782174273/)|Book|Data Science|Data science for Java developers|
|[Mastering Java Machine Learning (Packt)](https://www.amazon.com/Mastering-Java-Machine-Learning-architectures/dp/1785880519)|Book|ML|Machine learning for Java developers|
|[Machine Learning for Absolute Beginners](http://a.co/4Ir0KhJ)|eBook|ML|Excellent eBook to get high level understanding of ML|



# FAQ

**Q) I am a Java/Kotlin developer and I want to dive into "data science". Where do I start?** 

**A)** The funny thing about buzzwords is they do prompt people to be open to new ideas, but when you reach the actual problem-solving stage it can be difficult knowing where to start. This is because "data science" means something different to every individual, company, and industry. Therefore it is easy for newcomers to chase [machine learning](https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) as a solution to their problems when what they really need is [discrete optimization](https://www.coursera.org/learn/discrete-optimization/home/welcome). Some data scientists like tinkering with data sets in Jupyter notebooks and Pandas DataFrames while software engineers find such approaches undisciplined and messy. Many data science book authors will tell you to [become proficient in linear algebra](https://www.youtube.com/watch?v=fNk_zzaMoSs&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab), even though it seems pointless to learn without seeing real-world applications.

In my opinion, the best way to break into "data science" is to find problems with a nondeterministic nature that you would like to solve. Self-started projects like [generating a classroom schedule](https://github.com/thomasnield/optimized-scheduling-demo) or [categorizing text](https://www.youtube.com/watch?v=JLSdW60t898) are great ways to get insight and intuition pretty quickly. It also channels you into the areas of "data science" you will more likely be interested in. 

I do think it is better to start learning [optimization](https://www.coursera.org/learn/discrete-optimization/home/welcome) before diving into [machine learning](https://www.youtube.com/watch?v=tAioWlhKA90), not just because optimization is a key part of ML, but rather it solves a larger number of real-world problems on its own. Be sure to also develop a healthy curiosity for math and how it applies to the real-world, and YouTube channels like [3Blue1Brown](https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw/playlists) do a wonderful job fostering this kind of curiosity. 

<br>

**Q) Why are you proposing using Kotlin for data science/machine learning purposes when most people are using Python?** 

**A)** Kotlin is a production-grade and statically typed JVM language that fills the much-needed void of a more "pragmatic Scala". While many people are being productive with Python, [many organizations are finding Kotlin can help them be more productive](https://engineering.khanacademy.org/posts/kotlin-adoption.htm). This is especially true when it comes to building entire production systems and not just models.

To give a more thorough answer, Roman Elizarov at JetBrains summarized it best [in this post](https://discuss.kotlinlang.org/t/ai-and-deep-learning-define-the-future-of-programming-will-kotlin-fly-or-die/2264/5): 

> Most other “Python” deep learning frameworks are actually written in C++. Python is used just as a scripting language to “glue” various moving pieces together. Any other scripting language could be used instead, with the corresponding (relatively thin) bridge. Of course, the current momentum is on the Python side. If the past history on innovation and rise/fall of languages teaches us anything, the lesson we can learn is that it does not really matter who came first to the field and it does not even matter who is the leader now.

> Kotlin is, without doubt, considerably more productive for any project of non-trivial size due to its static types and emphasis on toolability. Even at 10K+ Python LOCs you start to feel pains of a dynamic language. Python works nicely in slide-ware and in small code snippets of the kind you can put into iPython notebooks, where you can actually execute the code on your data and then enjoy code completion and integrated help on the actual, dynamically resolved object instances. As soon as you start writing the actual non-tirival code, abstracting it into modules, etc, it all starts to fail utterly – code completion and help becomes useless for any non-trivial framework even in state-of-the-art Python IDEs like PyCharm.

> The first player in ML field that will realise that Python is roadblock to further scale will reap the benefits. All we can do in Kotlin team is to make sure that when this realisation comes, Kotlin is in good shape to serve as a viable alternative to be considered.  - Roman Elizarov

<br>

**Q) I'm a programmer but I'm bad at math. Is there any hope for me?**

A) Absolutely. If you have successfully hacked your way with programming, you can hack your way through math. Granted it is helpful to have gone through the exposure of high school and college math, but chances are you forgot most of it anyways. The key is to learn math that is useful for the problems you are trying to solve, and to pair it effectively with your programming skills. It is also easier to learn as an adult when you have a purpose for it. 

However, this can still be hard and it is important to not give into discouragement. Keep studying your roadblocks and use multiple resources to demystify what you are struggling with. When you cannot find an alternative explanation of a concept, it can help to study what is confusing you repeatedly until you start absorbing it. 

On top of learning enough math to solve nondeterministic problems you are interested in, try to foster your general curiosity. Do not memorize like in high school/college but take time to understand why something is so. [3Blue1Brown](https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw) on YouTube and the book _[No BS Guide to Math and Physics](http://www.lulu.com/shop/ivan-savov/no-bullshit-guide-to-math-and-physics/paperback/product-23632949.html)_ are great resources to do this. [PatrickJMT](http://patrickjmt.com/) does an excellent job showing how to apply mathematical concepts, and [tThis article](https://towardsdatascience.com/essential-math-for-data-science-why-and-how-e88271367fbd) effectively summarizes all the areas of applied math in data science.

<br>

**Q) How can Kotlin do any machine learning or data science tasks when it does not match the library catalogue of Python or R?**

A) Read the rest of this document and you will be surprised what the JVM ecosystem already offers :)

<br>

# Communities

|Name|Platform|Description|
|---|---|---|
|[PySlackers](https://pyslackers.com/)|Slack|A Slack community of Python developers and data science professionals.|
|[Kotlin Slack](https://kotlinlang.slack.com/messages/C4W52CFEZ)|Slack|A Slack community of Kotlin developers. Join the #datascience channel|

# Blogs, Press, Media

|Name|Media|Description|
|---|---|---|
|[KotlinConf - Mathematical Modeling with Kotlin](https://youtu.be/-zTqtEcnM7A)|Conference|Thomas Nield talks about optimization and ML with Kotlin|
|[Kotlin Machine Learning  and Optimization](https://www.youtube.com/playlist?list=PLYDlqiU6gadsBEHh-N861iWcBzazs4sEU)|Video|Thomas' demos and walkthroughs of different optimization and machine learning algorithms in Kotlin|
|[KotlinConf - Data Science Workflows with Kotlin](https://youtu.be/yjVW6uCmVBA)|Conference|Holger Brandl demonstrates Krangl workflows in Kotlin|
|[KotlinConf- Kotlin for Data Science](https://www.youtube.com/watch?v=J8GYPG6pt5w)|Conference|Thomas Nield explains the merits of Kotlin on the data science domain|
|[KotlinConf - Kscript](https://www.youtube.com/watch?v=cOJPKhlRa8c)|Conference|Holger Brandl covers kscript for data science workflows|
|[Talking Kotlin - Data Science with Thomas Nield](http://talkingkotlin.com/Data-Science-with-Thomas-Nield/)|Podcast|Thomas Nield explains the merits of Kotlin on the data science domain
|[Kotlin's Emerging Data Science Ecosystem](https://holgerbrandl.github.io/kotlin4ds_kotlin_night_frankfurt//emerging_kotlin_ds_ecosystem.html)|Talk/Slides|Holger Brandl gives an update on Kotlin's state as a data science platform|
