# A Guide to Building Your Open-Source Science Library

A cheatsheet to develop a scientific open-source library from scratch.

## Zero to Library

Here you will find information to design, build, and release an open-source library to perform scientific research in Python from scratch to finish.


[Before Starting Coding](1-code.md): Setting up the environment on your machine, including the tools you will need to write code efficiently. Some information about the Python and open source ecosystem, and how they relate to open science are also given. 

[Developing your Project](2-develop.md): A step-by-step guide with best practices for coding, and tips for making code development as effortless as possible.  

[Testing](3-test.md): Especially in software related to scientific research, at start, the destination is not always crystal clear. Code is written, optimized, reorganized. Unit testing is a crucial task to avoid getting lost in the process.  

[Documentation](4-docs.md): "Code is more often read than written" said Guido Van Rossum, the creator of Python. This is especially true for collaborative projects in the scientific research space, in which researchers might interact with code in a delocalized manner, at different times, and on different time scales. Making good comments of features, from functions to classes, allows one to generate with little effort a full fledged online documentation, drastically increasing the rate of adoption.    

[Distributing](5-distribute.md): It's time to release your library. Making importing your library easy is a key feature for its users, potential future contributors. Several tools now allow to deploy code in a variety of environments using package managers.  

[Publishing](6-publish.md): As a researcher, you are asked to publish your research results. In the case of a code project these can be novel research results derived from the software or the software itself, if it provides an innovative method or approach that can help the research community. Some examples on best practices to publish code and datasets are given, such as considering Zenodo for file hosting and an immediate DOI reference. A list of research journals especially relevant for physicists is provided. 

[Hosting](7-host.md): Interactive notebooks allow users to play with your code effortlessly, without worrying about installing software. They are also a great solution for interactive workshop and in the classroom, as they allow students and in general users to tinker with code without any installation.   


## References
This project stems from a series of talks, lectures, material developed in relation to the QuTiP (Quantum Toolbox in Python) library and open source in quantum-tech research. The aim is to provide useful information in a concentric way, starting from the quantum-tech research community, to the physics, academic and in general scientific community engaging with open-source software.  


["Open-source scientific computing for quantum technology: QuTiP"](https://conferences.lbl.gov/event/195/other-view?view=standard), Nathan Shammah RIKEN Berkeley workshop, Berkeley, USA, 2019

["The rise of open source in quantum physics research"](http://blogs.nature.com/onyourwavelength/2019/01/09/the-rise-of-open-source-in-quantum-physics-research/), Nathan Shammah and Shahnawaz Ahmed, *Nature*'s physics blog, January 9, 2019  

"Make Your Code Count", Shahnawaz Ahmed 
FOSDEM Conference - Quantum Software Track, Bruxelles, Belgium, [YouTube](https://www.youtube.com/watch?v=aAlkNuYFi-8), 2019
[JST ImPACT School](http://www.jst.go.jp/impact/hp_yamamoto/symposium/school1/index.html), Toyama, Japan, 2018

"Bit to QuBit: Data in the age of quantum computers", Shahnawaz Ahmed, 
[PyData 2018](https://pydata.org/warsaw2018/schedule/presentation/22/), Warsaw, Poland, 2019

["Scientific computing for quantum technology"](https://www.euroscipy.org/2018/descriptions/Scientific%20computing%20for%20quantum%20technology.html), Nathan Shammah, EuroSciPy 2018, Trento, Italy, [YouTube](https://youtu.be/J32Guga4mtM?t=2), 2018


