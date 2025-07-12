## Hi there 👋

<!--
**comp-phys-marc/comp-phys-marc** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!-- <img width="1993" height="726" alt="image1-23-2" src="https://github.com/user-attachments/assets/df1342b4-9abc-4aa1-acce-872ca3ac25dd" /> -->
<img width="1964" height="670" alt="image1-81-4" src="https://github.com/user-attachments/assets/7c498065-4198-47b8-a80a-b9caf65dbd69" />


![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![TypeScript](https://img.shields.io/badge/typescript-007acc?style=for-the-badge&logo=typescript&logoColor=ffffff)
![PHP](https://img.shields.io/badge/php-474a8a?style=for-the-badge&logo=php&logoColor=ffffff)
![HTML](https://img.shields.io/badge/html-e34c26?style=for-the-badge&logo=html5&logoColor=ffffff)
![SASS](https://img.shields.io/badge/sass-cd6799?style=for-the-badge&logo=sass&logoColor=ffffff)
![Rust](https://img.shields.io/badge/rust-ce422b?style=for-the-badge&logo=rust&logoColor=000000)
![Bash](https://img.shields.io/badge/GNU%20Bash-4EAA25?style=for-the-badge&logo=GNU%20Bash&logoColor=white)

![OpenQASM](https://img.shields.io/badge/openqasm-blue?style=for-the-badge)
![BlackBird](https://img.shields.io/badge/blackbird-black?style=for-the-badge)
![QMASM](https://img.shields.io/badge/qmasm-555555?style=for-the-badge)
![Q Sharp](https://img.shields.io/badge/qsharp-purple?style=for-the-badge)

![Docker](https://img.shields.io/badge/docker-0db7ed?style=for-the-badge&logo=docker&logoColor=ffffff)
![Kubernetes](https://img.shields.io/badge/kubernetes-blue?style=for-the-badge&logo=kubernetes&logoColor=ffffff)

I completed a Masters in Quantum Information Science through the [Institute for Quantum Computing](https://uwaterloo.ca/institute-for-quantum-computing/) at the University of Waterloo in 2020. After a brief stint as a quantum software engineer at [Photonic Inc](https://photonic.com/), I am now pursuing a PhD in Electrical and Computer Engineering at the University of British Columbia in the [Quantum Science and Technology Lab](https://sites.google.com/view/ubcqtl/home) and am in a summer residency at [Xanadu Quantum Technologies](https://www.xanadu.ai/).

This has meant switching from the computer and information science subfield, which saw my first thesis, paper and three patents between 2018 and 2020, to the new subfield of quantum devices in which I have also published recently in 2024. Read on my [Google Scholar](https://scholar.google.ca/citations?user=XkHhU_0AAAAJ&hl=en).

I have founded two profitable tech companies in the past, [rQadium](https://marcusedwards.me/rqadium/) and Leadme Inc., building our products myself as a full stack software and hardware engineer.
I also enjoy writing hard sci-fi. In my spare time, I love hiking, camping and spending time with my wife and dog.

- 🔭 I’m currently working on ...

  - **Quantum programming languages**, like my implementations of:

    - [OpenQASM](https://openqasm.com/): ([parser](https://github.com/comp-phys-marc/qasm-ts) in TypeScript: ![NPM Downloads](https://img.shields.io/npm/dy/qasm-ts)) ([interpreter](https://github.com/PennyLaneAI/pennylane/blob/master/pennylane/io/qasm_interpreter.py) in Python: ![PyPI - Downloads](https://img.shields.io/pypi/dw/pennylane))
   
    - [BlackBird](https://strawberryfields.ai/photonics/demos/run_blackbird.html): ([parser](https://github.com/comp-phys-marc/blackbird-ts) in TypeScript: ![NPM Downloads](https://img.shields.io/npm/dy/blackbird-ts)) ([visualizer](https://github.com/XanaduAI/strawberryfields/blob/master/strawberryfields/circuitdrawer.py) in Python: ![PyPI - Downloads](https://img.shields.io/pypi/dw/strawberryfields))

    - [Q#](https://learn.microsoft.com/en-us/azure/quantum/qsharp-overview): ([parser](https://github.com/comp-phys-marc/q-sharp-ts) in TypeScript ![NPM Downloads](https://img.shields.io/npm/dy/q-sharp-ts))
  
    - [QMASM](https://github.com/lanl/qmasm): ([parser](https://github.com/comp-phys-marc/qmasm-ts) in TypeScript ![NPM Downloads](https://img.shields.io/npm/dy/qmasm-ts))

    I am maintaining a [web-first compile toolchain](https://www.researchgate.net/publication/391803478_A_Web_Based_Compile_Toolchain_for_Quantum_Programming_Languages) (that runs [here](https://github.com/comp-phys-marc/distributed-emulator)) for these langauges on GitHub and on [npm](https://www.npmjs.com/~marcusedwards). I am also implementing an open source OpenQASM 3.0 [interpreter](https://github.com/PennyLaneAI/pennylane/blob/master/pennylane/io/qasm_interpreter.py) [@XanaduAI](https://github.com/XanaduAI) in [PennyLane](https://github.com/PennyLaneAI/pennylane). <!-- ![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/PennyLaneAI/pennylane/total). -->

  - **Quantum compilation strategies**, like:
    -  [compiling Shor's algorithm](https://github.com/comp-phys-marc/compiling-shor) to Clifford+T
    -  [this project](https://github.com/comp-phys-marc/quantum_channel_characterization) using deep learning
    -  [this experiment](https://github.com/comp-phys-marc/circuit-parsers) using quantum circuit image recognition
    -  [this](https://github.com/PennyLaneAI/pennylane/pull/7748) compiler pass
    -  [this](https://github.com/PennyLaneAI/pennylane/pull/7754) compiler pass
    -  a [strategy](https://uwspace.uwaterloo.ca/items/217087f7-8443-4ebd-8299-bba947a552c0) for lowering WebAssembly to QUBOs for D-Wave.

  - **Quantum simulators and emulators**, like:
    - this [Python based simulator](https://github.com/comp-phys-marc/qeelib) with
      - a linear-algebra free implementation on [this branch](https://github.com/comp-phys-marc/qeelib)
      - usual LA approach [here](https://github.com/comp-phys-marc/qeelib/tree/vectorize)
    - this [Rust based simulator](https://github.com/comp-phys-marc/qeelibrs)
    - this [hardware emulator](https://arxiv.org/abs/2302.00821).

  - **Low level control software** for operating quantum devices, like:
    - this [framework](https://github.com/Quantum-Science-and-Technology-Lab/labber-wrapper) built on KeySight's stack

  - **Quantum computing hardware**, like:
    - my [PCB carrier](https://github.com/comp-phys-marc/carrier_PCB) for quantum processors
    - and more!

- 👯 I’m looking to collaborate on ...

  - **Quantum computing projects**, and especially open source! A success story is my recent collaboration with [@seankim658](https://github.com/seankim658) on updating [QASM-TS](https://github.com/comp-phys-marc/qasm-ts) to a new vresion supporting the full OpenQASM 3.0 spec. It is now in the hands of hundreds of users.

  - **Machine learning projects**, like [this project](https://patents.google.com/patent/US20210303973A1/en) where we designed convolutional neural networks that generated web UIs before it was cool (before Chat GPT existed).

- 🤔 I’m looking for help with ...

  - **Tests** for the Q\# parser in [this great first issue](https://github.com/comp-phys-marc/q-sharp-ts/issues/1).

  - **Implementation** of more compiler features in [this more advanced issue](https://github.com/comp-phys-marc/q-sharp-ts/issues/2).

- :bar_chart: GitHub stats ... 

![Marcus' GitHub stats](https://github-readme-stats.vercel.app/api?username=comp-phys-marc&show=reviews,prs_merged&theme=dark)

<!-- <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=comp-phys-marc" /> -->

- :dollar: Donate ...

  If you use or benefit from my any of my ongoing unremunerated open source work, consider donating me a coffee on [Ko-Fi](https://ko-fi.com/marcusedwards).
