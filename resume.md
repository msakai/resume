MASAHIRO SAKAI (酒井 政裕) ― Research and Development Engineer
==============================================================

* Email: masahiro.sakai@gmail.com
* Web: http://msakai.jp
* LinkedIn: https://www.linkedin.com/in/masahirosakai
* GitHub: https://github.com/msakai

Research and development engineer with a strong background in theoretical computer science, including programming language theory, over seven years of experience in R&D involving SAT/SMT solvers, and more than ten years of delivering solutions based on deep learning, machine learning, and mathematical optimization.

Experienced in engineering management and agile development, having served as a Scrum Master to facilitate effective team collaboration. Co-translated *Software Abstractions* and *Types and Programming Languages* into Japanese, contributing to the accessibility of key works in formal methods and programming language theory for Japanese readers.

Professional Experience
-----------------------

### [Preferred Networks, Inc.](https://www.preferred-networks.jp)

Engineer (May 2017 to Present), Engineering Manager (Dec. 2019 to
May 2022), Tech Lead (Jun. 2022 to Feb. 2023 and Oct. 2024 to Present),
and Scrum Master (May 2023 to Sep. 2024).

Worked on applying cutting-edge deep learning techniques to solve technically demanding real-world problems across multiple domains, including manufacturing, logistics, and process automation:

* Application of Black-Box Optimization to Manufacturing Processes of Heavy Industries (Oct. 2024 - Present)

  Lead multiple projects optimizing customers' manufacturing processes by combining Preferred Networks' black-box optimization framework Optuna with simulators of the target processes.
  Produced key experimental results that formed the foundation for achieving project goals, contributing to successful project outcomes delivered by the team.

* R&D Project on LLM-based Agents (Oct. 2024 - Present)

  Lead software engineering efforts within a cross-functional team of researchers and engineers, developing a robust and efficient experimental platform that supports large-scale LLM-based experiments.
  Applied expertise in mathematical optimization to deepen the team’s understanding of the underlying problem and contribute to improving solution methods.

* Data Processing for Weather Radar Project (Jun. 2024 - Sep. 2024):

  Assisted the team developing technology to compress and distribute a massive amount of four-dimensional observation data from the latest Multi-Parameter Phased Array Weather Radar (MP-PAWR).
  Developed a data processing workflow by modifying and integrating existing C programs to handle past observational datasets.

* Optimization Project in the Logistics Field (Nov. 2021 - Jan. 2022):

  Led a team of engineers to quickly gain expertise in an unfamiliar domain and develop a solution combining reinforcement learning, SMT solvers, and physical simulation to address the customer’s optimization problem.

* Automated Operation of Petrochemical Plants (2019-2024):

  Contributed to the development of control systems enabling fully automated operation of petrochemical plants, including a [butadiene extraction unit](https://www.preferred.jp/en/news/pr20211202/) and later a more complex [crude distillation unit](https://www.preferred.jp/en/news/pr20240524/), now operating 24/7 at ENEOS's Kawasaki Refinery.

  Designed key components in the early stages of the project that remain in use, including an overall control scheme, inductive biases for integrating domain knowledge into neural network models, and communication with distributed control systems (DCS).

  Participated in simulator-related R&D and system development (both front- and back-end), and supported the project as engineering manager and scrum master during certain periods.

* PoC Projects on Anomaly Detection for Manufacturing Sites (2017-2019):
  
  Worked on multiple proof-of-concept projects applying anomaly detection to factory processes (e.g., detection of cutting tool anomalies).
  Adapted neural network–based algorithms to customer environments by developing specialized data preprocessing and augmentation methods, and resolving deployment issues such as memory leaks.
  The resulting technology was later incorporated into FANUC’s products as the “[AI Servo Monitor](https://www.fanucamerica.com/products/cnc/cnc-software/machine-tool-data-collection-software/ai-servo-monitor).”

* Menoh DNN inference library (2018-2019):

  Contributed to the development of [Menoh](https://github.com/pfnet-research/menoh), a deep neural network inference library that loads trained DNN models in ONNX format and runs high-performance inference on Intel CPUs using MKL-DNN (oneDNN).
  Worked on code reviews, CI setup, cross-platform support for Windows and macOS, and Haskell bindings. Also proposed the project name “Menoh” (瑪瑙).

* Research on applying deep learning to automated theorem proving (2017-2019):

  Conducted research on applying deep neural networks to various theorem-proving tasks, including [premise selection in first-order logic ATP](https://github.com/pfnet-research/chainer-formulanet), inference rule selection in [intuitionistic propositional logic](https://arxiv.org/abs/1811.00796), and neural-network-based decision heuristics for SAT solvers.
  [[Slides at ProofSummit 2017 (in Japanese)]](https://www.slideshare.net/slideshow/proof-summit-2017-for-slideshare/78254931)

### [Toshiba Corporation](https://www.global.toshiba/)

Engineer (Apr. 2007 to Jun. 2015) and Research Scientist (Jul. 2015 to Apr. 2017).

Worked on R&D of dependable software technologies based on formal methods and program analysis, and later contributed to projects applying optimization and data-driven approaches to social infrastructure, including an economic load dispatch system for power generation and a smartphone-based recommendation system for regional economic promotion.

* Optimization for economic load dispatch in power generation (2015-2016):

  Contributed to a R&D project on economic load dispatch — optimizing electricity generation to minimize cost under operational constraints — by improving the performance of the prototype optimization system, setting up a continuous integration environment, and developing heuristic algorithms. Some of these contributions were applied to the system for TEPCO Fuel & Power, Incorporated.
  [[News release regarding presentation at thermal and nuclear power generation conference (in Japanese)]](https://www.global.toshiba/jp/news/energy/2016/10/news-20161026-01.html)
  [[Toshiba Review article (in Japanese)]](https://www.global.toshiba/content/dam/toshiba/migration/corp/techReviewAssets/tech/review/2016/03/71_03pdf/0A.pdf#page=6)

* Recommendation system for the Kawasaki Grand City Mall project (2013-2015):

  Developed a smartphone-based recommendation system for regional economic promotion as part of Toshiba's smart city and O2O service demonstration around Kawasaki Station. Led a team responsible for data analysis and recommendation algorithm development.
  [[Press release announcing the start of the experient]](https://warp.ndl.go.jp/info:ndljp/pid/8406771/www.city.kawasaki.jp/200/page/0000053904.html)

* SMT-based semi-automatic test-case generation for power plant control systems (2010-2014):

  Contributed to the development of a semi-automatic test-case generation technology for Function Block Diagram (FBD) programs used in power plant controllers, which introduced new FBD-specific test coverage criteria. Designed and implemented the core algorithms that encode FBD programs and coverage conditions into logical formulas and use SMT solvers to generate test cases.

* Molatomium (2009-2011):

  Provided technical advice and support on the design of the language and runtime system for *Molatomium*, a parallel programming model for “Cell Broadband Engine”-like heterogeneous multicore processors, contributing to Toshiba's flagship digital TV, CELL REGZA, from the perspective of programming language theory.
  [[HotPar'10 paper]](https://www.usenix.org/conference/hotpar-10/molatomium-parallel-programming-model-practice)

* Specification mining based on UNSAT core enumeration (2008-):

  Contributed to a research project on specification mining to address software reliability and maintenance challenges.
  Developed a method for mining preconditions by integrating model checking with minimal unsatisfiable core enumeration, implemented on top of the *CForge* program analysis framework.

* CForge: Bounded model checker for C language (2008-2012):

  Served as the main developer of *CForge*, a C-language frontend for the *Forge* program analysis framework developed by the Software Design Group at MIT.
  Developed as part of a joint research project with MIT SDG. Responsible for the overall design, development of a formal specification language for C, implementation of the compiler frontend translating C programs into Forge's intermediate representation, and encoding of low-level C features such as pointers and unions.

* Verification of workflow networks based on model checking (2007).

Skills
------

* Research and Technical Interests:
  * Functional Programming, Type Theory, Category Theory, Formal Methods,
    Model Checking, Automated Theorem Proving, Mathematical Logic,
    SAT/SMT Solvers, Machine Learning, Deep Learning, Mathematical Optimization

* Programming Languages:
  * Haskell, Python, Ruby, Java, C

* Languages:
  * Japanese: Native
  * English: Professional Working Proficiency
  * German: Intermediate (CEFR B1)

Qualifications
--------------

* Coursera
  * Application Development with Cloud Run (Jan. 2023)
    by Google Cloud Training
  * Securing and Integrating Components of your Application (Jan. 2023)
    by Google Cloud Training
  * Getting Started With Application Development (Jan. 2023)
    by Google Cloud Training
  * Getting Started with Google Kubernetes Engine (Dec. 2022)
    by Google Cloud Training
  * App Deployment, Debugging, and Performance (Dec. 2022)
    by Google Cloud Training
  * Google Cloud Fundamentals: Core Infrastructure (Dec. 2022)
    by Google Cloud Training
  * Oil & Gas Industry Operations and Markets (Apr. 2020)
    by Prof. Lincoln Pratson, Duke University
  * Process Mining: Data science in Action (May. 2015)
    by Prof. Wil van der Aalst, Eindhoven University of Technology
  * Discrete Optimization (May. 2015)
    by Prof. Pascal Van Hentenryck, The University of Melbourne
  * Gamification (Mar. 2015)
    by Assoc. Prof. Kevin Werbach, University of Pennsylvania
  * Heterogeneous Parallel Programming (Mar. 2014)
    by Prof. Wen-mei W. Hwu, University of Illinois at Urbana-Champaign
  * Introduction to Recommender Systems (Dec. 2013)
    by Prof. Joseph A. Konstan and Assist. Prof. Michael D. Ekstrand, University of Minnesota
  * Maps and the Geospatial Revolution (Aug. 2013)
    by Assist. Prof. Anthony C. Robinson, The Pennsylvania State University
  * Developing Innovative Ideas for New Companies: The First Step
    in Entrepreneurship (May. 2013)
    by Dr. James V. Green, University of Maryland, College Park
  * Model Thinking (Aug. 2013)
    by Prof. Scott E. Page, University of Michigan
  * Machine Learning (July 2013)
    by Assoc. Prof. Andrew Ng, Stanford University
  * Linear and Discrete Optimization (Apr. 2013)
    by Prof. Friedrich Eisenbrand, École Polytechnique Fédérale de Lausanne
  * Data Analysis (Mar. 2013)
    by Assist. Prof. Jeff Leek, Johns Hopkins University
  * Computing for Data Analysis (Jan. 2013)
    by Assoc. Prof. Roger D. Peng, Johns Hopkins University

* TOEIC Score 960 (Listening: 490; Reading: 470) (Mar. 2018)

* ドイツ語技能検定試験 2級 (German Diploma in Japan, Intermediate level) (Feb. 2025)

* C言語ベースの組込みハードウェア設計 (A course on C-based design of
  embedded hardware) (Oct. 2007)
  by NEXCESS (Nagoya University Extension Courses for Embedded
  Software Specialists).

* Google Cloud Certified Professional Cloud Developer (issued Feb. 2023, expired Feb. 2025)
  by Google Cloud

Education
---------

* Mar. 2007: Master of Media and Governance (Course: Cyber Informatics),
  Graduate School of Media and Governance, Keio University.
  * Master's thesis: "Fusion Transformations Applicable to Non-Strict Functions"
    ("非正格関数に対して適用可能な融合変換").
    Adviser: Prof. Tatsuya Hagino.

* Mar. 2005: Bachelor of Arts in Policy Management,
  Faculty of Policy Management, Keio University.

Books and Selected Publications
-------------------------------

* Benjamin C. Pierce, Eijiro Sumii, Yusuke Endoh, Masahiro Sakai,
  Keigo Imai, Yusuke Kuroki, Yoshihiro Imai, Takafumi Saikawa and
  Takeo Imai, “型システム入門－プログラミング言語と型の理論－”
  (Japanese translation of “Types and Programming Languages”).
  Ohmsha, 2013. ISBN: 978-4-274-06911-6

* Daniel Jackson, Shin Nakajima, Takeo Imai, Masahiro Sakai,
  Yusuke Endoh and Yoshio Kataoka,
  “抽象によるソフトウェア設計－Alloyではじめる形式手法”
  (Japanese translation of “Software Abstractions: Logic,
  Language, and Analysis”). Ohmsha, 2011. ISBN: 978-4-274-06858-4

* Momoko Hattori, Shimpei Sawada, Shinichiro Hamaji, Masahiro Sakai, Shunsuke Shimizu,
  "Semi-static type, shape, and symbolic shape inference for dynamic computation,"
  In MAPL 2020: Proceedings of the 4th ACM SIGPLAN International Workshop on
  Machine Learning and Programming Languages, Jun. 2020, pp. 11–19,
  https://dl.acm.org/doi/abs/10.1145/3394450.3397465

* Mitsuru Kusumoto, Keisuke Yahata, and Masahiro Sakai,
  "Automated theorem proving in intuitionistic propositional logic
  by deep reinforcement learning," Nov. 2018.
  https://arxiv.org/abs/1811.00796

* Masahiro Sakai and Takeo Imai,
  “Interplay between SAT and other Constraint Problems,”
  Computer Software, Vol. 32, No. 1, 2015, pp. 103-119.
  doi:10.11309/jssst.32.1_103
  https://www.jstage.jst.go.jp/article/jssst/32/1/32_1_103/_article/-char/en/

* Kohei Maruchi, Hiromasa Shin and Masahiro Sakai,
  "MC/DC-like Structural Coverage Criteria for Function Block Diagrams,"
  In proceedings of Software Testing, Verification and Validation Workshops
  (ICSTW). Cleveland, Ohio USA, 2014. pp. 253-259.
  doi:10.1109/ICSTW.2014.27
  http://ieeexplore.ieee.org/xpl/articleDetails.jsp?arnumber=6825670

* Takeo Imai, Masahiro Sakai, Masami Hagiya, “An Inference
  Method of Quasi-Weakest Preconditions by Minimal Unsatisfiable
  Core Enumeration,”
  Computer Software, Vol. 30, No. 2, 2013, pp. 207-226.
  doi:10.11309/jssst.30.2_207
  https://www.jstage.jst.go.jp/article/jssst/30/2/30_2_207/_article/-char/en/

* Masahiro Sakai, Kohei Maruchi and Takeo Imai, "Model-checking
  C programs against JML-like specification language," in Proceedings
  of the 19th Asia-Pacific Software Engineering Conference (APSEC2012),
  Hong Kong, 2012, pp. 174-183. doi:10.1109/APSEC.2012.68
  http://ieeexplore.ieee.org/xpl/articleDetails.jsp?arnumber=6462652

* Masahiro Sakai,
  "Fusion Transformations Applicable to Non-Strict Functions,"
  ("非正格関数に対して適用可能な融合変換,")
  Master's thesis, Graduate School of Media and Governance, Keio University,
  Jan. 2007.

Recognition and Awards
----------------------

* 2017 (社内表彰): 株式会社東芝 研究開発センター 業績賞優秀賞 (平成29年4月6日)
* 2015: the 19th Research Paper Award from Japan Society for
  Software Science and Technology for the paper “An Inference Method of
  Quasi-Weakest Preconditions by Minimal Unsatisfiable Core Enumeration”
  (日本ソフトウェア科学会第19回研究論文賞)
* 2014 (社内表彰): 株式会社東芝 コミュニティ・ソリューション社
  知的財産活動奨励賞 (平成26年7月7日)

Professional Services
---------------------

* One of the founding members of the [Machine Learning Engineering Research Group (MLSE) of the Japan Society for Software Science and Technology](https://sites.google.com/view/sig-mlse/)

* Editorial Board Member of the [Information Processing Society of Japan's journal
  "Information Processing"](https://www.ipsj.or.jp/magazine/magazine.html):  2021 to 2025

* Program Committee Member of the PPL (Programming and Programming Languages) Workshops:
  [PPL 2019](https://jssst-ppl.org/workshop/2019/), [PPL 2026](https://jssst-ppl.org/workshop/2026/)

* Program Committee Member of the xSIG (Cross-disciplinary Workshop on Computing Systems,
  Infrastructures, and Programming) workshops: [xSIG 2020](https://xsig.ipsj.or.jp/2020/),
  [xSIG 2021](https://xsig.ipsj.or.jp/2021/), [xSIG 2022](https://xsig.ipsj.or.jp/2022/),

* External reviewer of IPSJ/SIGSE Software Engineering Symposiums
  (SES2014, SES2015).

* Reviewed some technical books (about computer science and
  functional programming) before publication:

  * Graham Hutton and Kazuhiko Yamamoto, “プログラミングHaskell”
    (Japanese translation of “Programming in Haskell”), Ohmsha, 2009.
    ISBN: 978-4274067815

  * Jeremy Gibbons, Oege de Moor, and Nobuo Yamashita,
    “関数プログラミングの楽しみ”(Japanese translation of “the fun
    of programming”), Ohmsha, 2010. ISBN: 978-4274068058

  * Richard Bird and Nobuo Yamashita, “関数プログラミング入門 ―
    Haskellで学ぶ原理と技法―” (Japanese translation of
    “Introduction to Functional Programming with Haskell),
    Ohmsha, 2012. IBSN: 978-4274068966

  * Tom Stuart, Koichi Saasda and Takashi Sasai, “アンダースタン
    ディング コンピュテーション--単純な機械から不可能なプログラムまで”
    (Japanese translation of “Understanding Computation -- From
    Simple Machines to Impossible Programs”), O'Reilly Japan, 2014.
    ISBN: 978-4873116976

  * Richard Bird and Nobuo Yamashita, “関数プログラミング 珠玉の
    アルゴリズムデザイン” (Japanese translation of “Pearls of
    Functional Algorithm Design”), Ohmsha, 2014.
    ISBN: 978-4274050640

  * Mark C. Chu-Carroll and cocoatomo, “グッド・マス ギークのための数・論理・計算機科学”
    (Japanese translation of “Good Math: A Geek's Guide to the
    Beauty of Numbers, Logic, and Computation”), Ohmsha, 2016.
    ISBN: 978-4-274-21896-5

  * Tomoshi Otsuki and Youichiro Miyake, “最強囲碁AI アルファ碁 解体新書 増補改訂版 
    アルファ碁ゼロ対応 深層学習、モンテカルロ木探索、強化学習から見たその仕組み” (A commentary
    on AlphaGo and AlphaGo Zero), Shoeisha, 2018. ISBN: 9784798157771

  * Yusuke Endoh, “型システムのしくみ ― TypeScriptで実装しながら学ぶ型とプログラミング言語”
    (a book that explains the principles of type systems by implementing
    a type checker for a subset of TypeScript), Lambda Note, 2025. ISBN: 978-4-908686-20-7

Open Source Activities
----------------------

* toysolver / toysat [[hackage]](https://hackage.haskell.org/package/toysolver) [[github]](https://github.com/msakai/toysolver)

  Solver implementation of various problems including SAT,
  Max-SAT, PBS (Pseudo Boolean Satisfaction), PBO (Pseudo Boolean
  Optimization), MILP (Mixed Integer Linear Programming) and
  non-linear real arithmetic.
  In particular, it contains a moderately-fast pure-Haskell
  SAT solver 'toysat'. I submitted it to solver competitions
  (Pseudo Boolean Competition and Max-SAT Evaluations) and
  ranked high in some competition categories.

* Ruby-GNOME2 [[github]](https://github.com/ruby-gnome/ruby-gnome)

  Ruby-GNOME2 is a set of Ruby language bindings for the
  GNOME >=2.0 development environment. I was one of core
  developers in the early days. In particular, I have
  designed/wrote a general bridge between Ruby's object system
  and GObject object system using reflection/introspection
  features and replaced non-extensible hard-coded ones in
  its predecessor Ruby/GTK1.

* CPL : A categorical programming language interpreter [[hackage]](https://hackage.haskell.org/package/CPL) [[github]](https://github.com/msakai/cpl)

  I implemented an interpreter of CPL, a functional programming
  language based on category theory, designed by Prof. Tatsuya
  Hagino. In CPL, data types are declared in a categorical
  manner by adjunctions. Each data type is declared with its
  basic operations or morphisms. Programs consist of these
  morphisms, and the execution of programs is the reduction of
  elements (i.e. special morphisms) to their canonical form.

Other Activities
----------------

* Google Code Jam Japan 2011: 44th place among 918 participants

* Computer security competitions (CTF; Capture the Flag)
  * CTF for beginners 2015 Tokyo: 6th place among 103 participants
  * Trend Micro CTF Asia Pacific & Japan 2015 Online Qualifier:
    46th place among 881 teams, as a team "Ten*48"
  * SECCON 2015 Online CTF:
    43th place among 1251 teams, as a team "Ten*48"
  * DEF CON CTF Qualifier 2016:
    164th place among 1335 teams, as a team "Ten*48"
  * HITCON CTF 2016 Quals:
    34th place among 1024 teams, as a team "Ten*48"

* Study group of category theory (圏論勉強会): 2004 - 2012

  Category theory is a highly general and abstract mathematical
  theory, which has applications not only in mathematics but also
  in theoretical computer science, functional programming,
  physics, linguistics, and many other fields. I was one of core
  members of the study group and we studied following
  materials:

  * “Conceptual Mathematics: A First Introduction to Categories”
    by F. William Lawvere and Stephen Hoel Schanuel,
  * “Categories, Types, and Structures: An Introduction to
    Category Theory for the Working Computer Scientist”
    by Andrea Asperti and Giuseppe Longo,
  * “The Haskell Programmer's Guide to the IO Monad — Don't
    Panic” by Stefan Klinger,
  * “Temperley-Lieb Algebra: From Knot Theory to Logic and
    Computation via Quantum Mechanics”
    by Samson Abramsky
  * “A survey of graphical languages for monoidal categories”
    by Peter Selinger
  * “Categorical Logic and Type Theory”
    by Bart Jacobs.

  There is a Japanese article about this study group:
  “Technical Study Session Map in Japan - Join a Live Session
  of Engineers!”, 情報処理, Vol.52, No.4, Apr. 2011.
  http://id.nii.ac.jp/1001/00073853/

* RHG reading group (RHG読書会): 2003 - 2009

  This study group was a group of programming language geeks.
  It was initially started as a study group for reading
  “Rubyソースコード完全解説” (known as “Ruby Hacking Guide”),
  but eventually, we studied many programming and
  programming-language related books/materials:

  * YARV (Ruby >=1.9 VM),
  * なでしこ (a Japanese programming language),
  * MinCaml,
  * “ふつうのLinuxプログラミング--Linuxの仕組みから学べるgccプログラミングの王道” (A hands-on guide to Linux system programming, covering topics from “Hello, World” to building an HTTP server in C),
  * “ふつうのHaskellプログラミング--ふつうのプログラマのための関数型言語入門” (An introductory guide to Haskell for procedural programmers, designed to help them master the 'ordinary' functional programming paradigm),
  * “入門JavaScript” (An introductory guild of JavaScript, covering not only in-page scripting, but also language specifications and prototype-based object-oriented programming),
  * “実践Common Lisp” (Japanese translation of “Practical Common Lisp”),
  * “ふつうのコンパイラをつくろう--言語処理系をつくりながら学ぶコンパイルと実行環境の仕組み” (A book for learning compilers and runtime environments by implementing a compiler for a simple language).

* Teaching Assistant
  * 2014-2015: Toshiba Systems & Software Institute
  * Feb. 2006: ベトナム高度IT教育者実践研修
  * Aug. 2003 - Sep. 2003: ITスキル標準人材育成研修
