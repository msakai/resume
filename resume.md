MASAHIRO SAKAI (酒井 政裕) ― Research and Development Engineer
==============================================================

* Email: masahiro.sakai@gmail.com
* Web: http://msakai.jp
* LinkedIn: https://www.linkedin.com/in/masahirosakai
* GitHub: https://github.com/msakai

Masahiro Sakai is a researcher in the field of theoretical computer
science. He is working as a software engineer at Preferred Networks, Inc.
He received a master's degree
in “Media and Governance” with “Cyber Informatics” concentration at
Keio university. He translated “Software Abstractions” and “Types and
Programming Languages” into Japanese with his colleagues.

He is passionate in learning new technologies / skills / knowledge
and putting them into practice by writing code, and he strives hard
toward perfection.

His interest includes Programming Language Theory, Functional
Programming, Software Engineering, Category Theory, Constraint
Solving, SAT/SMT Solvers, Machine Learning, Mathematical Optimization,
and Computer Security.

Professional Experience
-----------------------

### [Preferred Networks, Inc.](https://www.preferred-networks.jp)

Engineer (May 2017 to Present), Engineering Manager (December 2019 to
May 2022), Tech Lead (June 2022 to February 2023 and Nov 2024 to Present),
and Scrum Master (May 2023 to Sep 2024):

I worked as a software engineer applying cutting-edge deep learning
techniques to solve highly challenging real-world problems.

* Application of black-box optimization to manufacturing processes for heavy industries (Oct 2024 - Present)

  Multiple projects performing black-box optimization by combining Preferred Networks' black-box optimization software Optuna with simulators for target processes.
  I led the projects, delivered key results, and achieved outcomes that exceeded customer expectations.

* R&D Project for developing LLM agents for a certain task (Oct 2024 - Present)

  As part of a team comprising researchers and engineers, I contributed by leveraging my software engineering skills and knowledge of mathematical optimization while also catching up on LLM technology.

* Data processing of the latest weather radar data (June 2024 - Sep 2024):

  Preferred Networks is developing technology to compress and distribute four-dimensional observation data acquired by the latest weather radar, the Multi-Parameter Phased Array Weather Radar (MP-PAWR). I temporarily assisted the team on the project and developed a workflow (involving modification and integration of existing C programs) to process their past observational data. 

* Optimization Problems in the Logistics Field (2021-2022):

  I led the project, and our team proposed methods utilizing reinforcement learning and SMT solvers.

* Automated operation of petrochemical plants (2019-2024):

  Petroleum refineries and petrochemical plants are large and complex,
  and their control requires operational know-how based on many years
  of experience. We first achieved the [automated operation of a butadiene extraction plant](https://www.preferred.jp/en/news/pr20211202/)
  and later the [automated operation of a crude distillation unit](https://www.preferred.jp/en/news/pr20240524/), which is more difficult and has a greater economic
  impact. Our system is used in ENEOS's Kawasaki Refinery 24/7.

  I made many important contributions early in the project,
  which are still in use: an overall control scheme,
  inductive bias for integrating domain knowledge into neural network
  models, and communication with DCS (Distributed Control System).  I
  I am also involved in many other parts of the project, including
  simulator-related R&D and system development (front- and backend).
  I also supported the project as an engineering manager and a scrum
  master.

* Several PoC projects for applying anomaly detection in factories and manufacturing sites (2017-2019):
  
  I worked on multiple anomaly detection projects in the factory
  (e.g. anomaly detection of cutting tools). I adapted already
  developed algorithms (neural network models) to the customer's
  environment and solved problems, including specialized data
  preprocessing and data augmentation, fixing memory leak issues in
  deployed environments, etc.  Our technology is incorporated in
  FANUC's products as [“AI Servo Monitor” (AIサーボモニタ)](https://www.fanucamerica.com/products/cnc/cnc-software/machine-tool-data-collection-software/ai-servo-monitor).

* [Menoh](https://github.com/pfnet-research/menoh) DNN inference
  library (2018-2019):

  Menoh is a DNN inference library that loads trained DNN models from
  the ONNX format and runs inference at high speed on an Intel CPU using
  MKL-DNN (oneDNN). The main developer is Shintarou Okada and I
  contributed with code reviews, CI, Windows/macOS support, Haskell
  binding, etc. I also proposed the name “Menoh” (瑪瑙).
  [[Blog post about the release (in Japanese)]](https://tech.preferred.jp/ja/blog/menoh-release/)

* Research for applying deep learning technologies in the field of automated
  theorem proving (ATP) (2017-2019):

  We tried to apply deep neural networks to theorem-proving related problems
  including [premise selection in automated theorem proving of first-order logic](https://github.com/pfnet-research/chainer-formulanet),
  [inference rule selection in intuitionistic propositional logic](https://arxiv.org/abs/1811.00796), and NN-based
  heuristics in SAT solver, etc.
  [[Slides at ProofSummit 2017 (in Japanese)]](https://www.slideshare.net/slideshow/proof-summit-2017-for-slideshare/78254931)

### [Toshiba Corporation](http://www.toshiba.co.jp/worldwide/index.html)

Engineer (Apr 2007 to June 2015) and Research Scientist (July 2015 to April 2017):

I worked as a researcher for the System Engineering Laboratory,
Toshiba Research and Development Center. I have worked in
software dependability team to develop technology based on
formal methods, program analysis, and automatic test-case
generation to achieve more dependable systems. I have also
worked in cities infrastructure solutions team and developed
a recommendation system that recommends brick-and-mortar
shops/goods on smartphones for regional promotion.

* Economic load dispatch (2015-2016):

  Economic load dispatch is the determination of the output
  of electricity generation units that meet the electricity
  demands with the lowest possible cost, subject to complex
  operational constraints. I assisted research project of
  economic load dispatch problem by removing performance
  bottlenecks of our prototype optimization system, setting
  up continuous integration environment, and writing heuristic
  algorithm and minor modules of the system. My work is partly
  applied to the system for TEPCO Fuel & Power, Incorporated.
  [[News Release Regarding Presentation at Thermal and Nuclear Power Generation Conference (in Japanese)]](https://www.global.toshiba/jp/news/energy/2016/10/news-20161026-01.html)
  [[Toshiba Review article (in Japanese)]](https://www.global.toshiba/content/dam/toshiba/migration/corp/techReviewAssets/tech/review/2016/03/71_03pdf/0A.pdf#page=6)

* Recommendation system for the Kawasaki Grand City Mall project
  (2013-2015):

  Toshiba carried out a demonstration experiment on smart city
  and O2O service around Kawasaki Station ([Press Release Announcing the Start of the Proof-of-Concept](https://warp.ndl.go.jp/info:ndljp/pid/8406771/www.city.kawasaki.jp/200/page/0000053904.html)).
  As part of this experiment, we
  have developed a recommendation system that recommends
  brick-and-mortar shops/goods on smartphones for regional
  promotion. I led a team for data analysis and
  recommendation algorithm development.

* SMT-based semi-automatic test-case generation for power
  plant control systems (2010-2014):

  Power plant controllers are often programmed using graphical
  data flow language such as Function Block Diagram (FBD).
  We have proposed new test coverage criteria for FBD and
  developed technology to automatically generate test cases
  that satisfy the proposed criteria. I developed core
  algorithms of our approach that encodes both FBD programs
  and conditions for proposed criteria into logical formulas and
  solves the conjoined formula using SMT solvers to generate
  test cases.

* Molatomium (2009-2011):

  I assisted language/runtime design of “Molatomium”, a parallel
  programming model for “Cell Broadband Engine”-like
  heterogeneous multicore processors, which was shipped
  with Toshiba's flagship digital TV “CELL REGZA”.
  [[HotPar'10 paper]](https://www.usenix.org/conference/hotpar-10/molatomium-parallel-programming-model-practice)

* Specification mining based on UNSAT core enumeration (2008-):

  Specification mining tackles software maintenance and
  reliability issues by mining latent specifications from
  source code. We have developed a novel technology to mine pre-condition
  (one type of specification) by combining model checking and minimal
  unsatisfiable core enumeration.

* CForge: Bounded model checker for C language (2008-2012):

  CForge is a C program analyzer based on a program
  analysis framework Forge developed by the Software Design
  Group (SDG) at MIT, and we developed CForge as part of a
  joint research project with MIT SDG. I worked as a main
  developer of CForge, and worked on its overall design,
  design of our formal specification language for C, implementation
  of a kind of C compiler, and so on.

* Verification of workflow networks based on model checking (2007).

Skills
------

* Engineering Knowledge and Interests:
  * Functional Programming, Formal Methods, Model Checking, SAT/SMT solvers,
    Machine Learning, Mathematical Optimization, Category Theory, Type Theory,
    Mathematical Logic.
* Programming Languages:
  * Haskell, Ruby, Python, Java, C.
* Languages:
  * Japanese: Native Speaker
  * English: Professional Proficiency
  * German: Intermediate level (CEFR B1)

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
  * Machine Learning (Jul. 2013)
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

* Google Cloud Certified Professional Cloud Developer (issued Feb 2023, expired Feb 2025)
  by Google Cloud

Education
---------

* March 2007: Master of Media and Governance (Course: Cyber Informatics),
  Graduate School of Media and Governance, Keio University.
  * Master's thesis: "Fusion Transformations Applicable to Non-Strict Functions"
    ("非正格関数に対して適用可能な融合変換").
    Adviser: Prof. Tatsuya Hagino.

* March 2005: Bachelor of Arts in Policy Management,
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

* toysolver / toysat [[hackage]](https://hackage.haskell.org/package/toysolver), [[github]](https://github.com/msakai/toysolver)

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

* PTQ : An implementation of Montague's PTQ in Haskell [[hackage]](https://hackage.haskell.org/package/PTQ) [[github]](https://github.com/msakai/ptq)

  Montague grammar and the PTQ (The Proper Treatment of
  Quantification in Ordinary English) by Richard Montague
  were pioneering work in the field of formal semantics
  of natural languages, and showed that natural languages
  (like English) and formal languages (like programming
  languages) can be treated in a similar way. I
  implemented his theory in an interactive environment.

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
  * “ふつうのLinuxプログラミング--Linuxの仕組みから学べるgccプログラミングの王道”,
  * “ふつうのHaskellプログラミング--ふつうのプログラマのための関数型言語入門”,
  * “入門JavaScript”,
  * “実践Common Lisp” (Japanese translation of “Practical Common Lisp”),
  * “ふつうのコンパイラをつくろう--言語処理系をつくりながら学ぶコンパイルと実行環境の仕組み”.

* Teaching Assistant
  * 2014-2015: Toshiba Systems & Software Institute
  * Feb. 2006: ベトナム高度IT教育者実践研修
  * Aug. 2003 - Sep. 2003: ITスキル標準人材育成研修
