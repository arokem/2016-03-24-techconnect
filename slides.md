class: center, middle

<image src="images/techconnect-logo.png">

### **Future Proofing Data-intensive Research**
## **The University of Washington eScience Institute**

### Ariel Rokem

<image src="images/eScience_Logo_RGB_PP.png">

<small>Follow along at: <a href="">arokem.github.io/2016-03-24-techconnect</a></small>

???

Hello! My name is Ariel Rokem, and I am a data-scientist at the University of Washington eScience Institute. Today, I am going to tell you about the future and what we are doing at the eScience Institue to make research at the University of Washington future-proof.

As you might already know...

---

layout: true

<div style="position: absolute; left: 650px; top: 370px;">
<image src="images/escience-network.png" width=500px style="opacity:0.4;filter:alpha(opacity=40);"> </div>

---

### The future is already here

--

### ... it's just not very evenly distributed.
                                              (William Gibson)

???

... the future is already here (click). It's just not very evenly distributed.

--

The promise of data-intensive discovery

???

In more and more research, future advances depend on our ability to record, process, analyze, and understand large, heterogeneous, noisy data. On the one hand, these are exciting times, in which we look forward to a near future in which data will be able to address many important societal challenges.


--

  and the challenges

???

On the other hand, the data-intensive future poses some tremendous challenges.

--

The eScience Institute: data-science at the UW

???

In this presentation, I will tell you aout the eScience Institute, and I will tell you how we are working at the eScience Institute to future-proof data-intensive discovery, by developing the role of data science at the University, and beyond.

--

Future proofing:

???
What does that mean?

--

   - Catalyzing collaborations

???

Much of our work capitalizes on unique opportunities to collaborate across disciplines.

--

   - Building and maintaining the tools

???
We believe that the future requires new tools for discovery, and we are building these tools. Even more importantly, we are creating the conditions for these tools to survive and to thrive.

--

   - Sustaining career paths in data-intensive research

???
One of the main challenges that we face as individuals, and also as an organization is sustaining careers at the interesection of tool-building and research. The eScience Institute provides a career path for data scientists like myself to pursue these important avenues, and also serves as a laboratory to experiment with what these career paths might look like.

--

   - Training data-savvy researchers

???
Finally, the topic of this session, and a focus of much of our energy is an investment in education and the training of a future generation of data-savvy researchers.

In this talk, I will discuss all of these challenges and provide you a glimpse into some of the work we are doing at the eScience Institute to secure a future-proof environment for data-intensive research.

But first, let me set the stage by telling you a little bit about my own career trajectory...
---

### Who am I?
--

<image src="images/huji-logo.png" height=100px> I am originally from West Jerusalem, Israel

???
I come from West Jerusalem, in Israel. In college, at the Hebrew University, I studied Biology and Psychology. This education provided a basis for my interest in interdisciplinary work and for graduate school...
--

<image src="images/berkeley-logo.png" height=100px> Ph.D. In neuroscience

???
...I came to the United States, and studied, at the University of California, Berkeley
--

<image src="images/stanford-logo.png" height=100px> Research experience in computational neuroimaging

???
After graduate school, I spent a few years conducting research in computational neuroimaging, as a post-doc at Stanford.
--

 <image src="images/scipy-logo.png" height=100px> <image src="images/nipy-logo.png" height=100px> Open source software development

???
In graduate school, I started developing open-source software for computational neuroimaging, and became part of a community called "NIPY" (or neuroimaging in Python), which uses the Python programming language to develop open-source tools for analysis of data from human neuroimaging.

---

### Neuroimaging is data-intensive!

<video id="mri-zstack" preload="auto" width="85%" height="auto" data-setup="{}" autoplay loop ><source src="./videos/mri-zstack.mov"/></video>

???
Neuroimaging data, here showing a human brain scanned with an MRI machine at millimeter resolution, can provide detailed information about the structure and function of an individual human brain.

These data provide some amazing opportunities

---

### Amazing opportunities...

<image src="images/obama_and_dna.jpg"  height="30%">

The <a href="https://www.whitehouse.gov/the-press-office/2015/01/30/fact-sheet-president-obama-s-precision-medicine-initiative"> **Precision Medicine** </a> initiative aims to make medicine:

#### Personalized, Predictive, Preventative, Participatory

<small><a href="http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3978637/">Hood and Auffray (2013)</a></small>

???
Just last year, President Obama announced the Precision Medicine Iniative. This initiative aims to propel medical practice into the future, by making it Personalized, Predictive, Preventative and Participatory.

--

### The key to do this is in the data!

???

The key to making this vision a reality is *data*! Though a major focus of the current precision medicine initiative is in caner research, let me give you an example from human neuroimaging.

---

### Automated Fiber Quantification

<a href="http://depts.washington.edu/bdelab/"> Jason Yeatman </a>, UW ILABS

<video preload="auto" width="60%" height="auto" data-setup="{}" autoplay loop ><source src="./videos/cc_tube_movie-373.mov"/> </video>

???

This example is taken from my work in collaboration with Jason Yeatman, a neuroscientist working at the University of Washington Institute for Learning and Brain Science.

In this movie, I am showing you the result of an MRI scan aimed at delineating the connections between different parts of the brain. This scan, conducted on a living breathing human being, provides us with information that allows us to trace the connections through the part of the brain known as the "white matter". This part of the brain contains the 'cables' that connect different parts of the so-called "gray matter", or the "cerebral cortex" that contains the bodies of the many billions of nerve cells in our brain. Many years of research have shown that these connections can be quite different between different individuals. Moreover, differences in the physical properties of these connections account for differences in health, and in cognitive abilities.

---

### Automated Fiber Quantification

<a href="http://depts.washington.edu/bdelab/"> Jason Yeatman </a>, UW ILABS

<image height="60%" src="images/AFQ-FA-CC.png">

<small><a href="http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0049790">Yeatman et al. (2012)</a></small>

???
Jason and his colleagues have developed a method to automatically trace these connections from MRI data, and to extract the physical properties of the tissue along the tracks. This is called Automated Fiber Quantification, or AFQ.

---

### Automated Fiber Quantification

<a href="http://depts.washington.edu/bdelab/"> Jason Yeatman </a>, UW ILABS

<image height="35%" src="images/AFQ-cerebral-palsy.png">

<small><a href="http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0049790">Yeatman et al. (2012)</a></small>

???
AFQ is useful, because in some individuals differences in the physical properties are only found in some parts of the tracks, and not in others

For example, in this image from a child with cerebral palsy, the tissue fractional anisotropy, a measurement of the tissue that tells us about the density of packing of the fibers in the tissue, the properties of the insulation of the nerve fibers, and about the prevalence of crossing fibers, among others  (her in yellow) is lower from that of a healthy control group (here in black) only in some parts of a track that connects the brain with the spinal cord, but not in others.
---

### Automated Fiber Quantification

<a href="http://depts.washington.edu/bdelab/"> Jason Yeatman </a>, UW ILABS

<image height="22%" src="images/AFQ-reading.png">

<small><a href="http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0049790">Yeatman et al. (2012)</a></small>

???

Similarly, differences between children in their reading abilities correlate with differences in the fractional anisotropy in some parts of tracks through the temporal lobe of the brain, but not other parts of these same tracks.

These measurements, and the algorithms to analyze them are developing very quickly

---

### ...and daunting challenges

<image src="images/vanhorn-toga-2014.png" height=400px>
<p><small>Van Horn and Toga (2014)</small></p>

???
One of the big challenges facing the field is that with the development of measurements at higher and higher resolution, and with the public availability of data from many studies, the amount of data is growing very fast.
---

### The data deluge

--
Across many different fields

???

This data deluge is not unique to neuroscience
--

Astronomy

???
Other fields, like astronomy...
--

Genetics

???
...and genetics, have been dealing with large data sets for many years.

What is unique at this time is that this data deluge is now affecting many more fields, some of whom have never been
--

...

--

Social sciences

???
One example are fields in the social sciences. Where some questions could once be answered by collecting responses in a survey, many researchers can now turn to large data-sets at the scale of entire societies.

--
<image height="25%" src="images/cell-phone-poverty.jpg">

Josh Blumenstock

???
For example, in this research from I-School researcher Josh Blumenstock and his group, high resoltion maps of poverty and wealth in an entire country (In this case, the central-African country Rwanda) can be generated based on cell-phone usage patterns

---

### The eScience Institute

<image src="images/eScience_Logo_PMS.png" height=150px>

???

The mission of the University of Washington eScience Institute is to collaborate with researchers across disciplines, to develop and apply advanced computational methods and tools to ask interesting and important questions amidst this data deluge.
--
<p>
</p>
<image src="images/DSE-and-sponsors.png" height=200px>

$ 37.8M for 5 years: <a href="http://msdse.org/">"Moore-Sloan Data Science Environments"</a>

???
We have a broad portfolio of funding from many sources, but a major source of support is a grant that we got a few years ago from the Moore and Sloan foundations. The funding from these foundations has created a collaborative network of environments at three institutions: NYU, Berkeley and The University of washington, devoted to data science.

---

### What is *Data Science*?

<image src="images/Data_Science_VD.png" height=400px>

<a href="http://drewconway.com/zia/2013/3/26/the-data-science-venn-diagram">Drew Conway</a>

???
Wait, you say. What is data science? Well, the term actually comes from the data deluge that companies in the private sector have . They realized that a combination of different skills: knowledge about the domain from which the data was taken, programming skills, and quantitative skills together form a very powerful background to extract meaningful.

Data science has been very fruitful in the private sector, producing new and novel products such as image search on Google, or personalized movie and reading recommendations on Amazon or Netflix, but it has also had a large impace on traditional industries: with data-driven companies such as Uber revolutionizing old industries such as transportation.
---

### Challenges for DS in academia:

???
In academia, on the other hand, data science presents several challenges. These challenges are the focus of our work, and form the main working groups that the Moore-Sloan effort is funding
--

- Tools and software

???
The first is the development of tools and software for
--

- Reproducibility and open science

???
A second challenge that faces science that depends on an intensive engagement with data is the challenge to make this research open and reproducible.
--

- Career paths for data scientists

???
Faced with compelling opportunities in the private sector, academia is challenged to retain and nurture the careers of individuals with the combination of skills needed to pursue data-science.
--

- Education and training

???
It is almost equally challening to provide training and education to a new generation of data-driven researchers, in the face of rapidly developing tools and systems, and within the confines of traditional academic disciplinary silos.
--

- Physical and intellectual space

???
One of the solutions to this problem is the creation of physical and intellectual spaces that provide the setting for work on . More about that in just a minute.

--

- Data Science studies

???
Similarly, we are interested in distilling the lessons we are learning about data science in academia. For this purpose, researchers in the eScience Institute are conducting ethnographic studies, and a working group on data science studies is conducting explorations aimed to understand what facilitates success in academic data science. This group is also exploring the complex ethical implications of data science.

---

### Tools and software

Connecting research on data science methodology (Computer Science and Engineering, Statistics, Applied Math) with domain research questions.

???
A major part of the work that we do is to develop tools and software that will be useful to researchers in a variety of fields. This means that we connect work in data science methodology, such as computer science, statistics, and others, with work in specific domains.

---

### Image Processing Across Domains

Many research domains use image data!

<video preload="auto" width="60%" height="auto" data-setup="{}" autoplay loop ><source src="./videos/moth.mov"/> </video>

???
For example, we have noticed that researchers at the institute from several different fields all use image data and image processing algorithms in their research. For example, researchers in the biology department use high-speed cameras to record the flight of moths, and analyze these data to better understand how their wings work.
---

### Image Processing Across Domains

Many research domains use image data!

<image src="images/Cepheid-Variable-Stars.jpg">

???
Researchers in astronomy use humongous image data to model the structure of distant galaxies.
---

### Image Processing Across Domains

Computer Science: Magda Balazinska, Alvin Cheung, Parmita Mehta, Sven Dorkenwald

<image src="images/myria-logo.png">

Astronomy: Andy Connoly, Jake Vanderplas

Biology: Dave Williams

???

Magda Balazinska and others on the Computer Science and Engineering department have developed systems for cloud computing data analysis, such as the Myria system. Our current work together builds upon this expertiese to build together the next generation of scientific image processing tools, that will serve researchers across all of these domains, and more.
---

### The challenge of novelty squared

<a href="https://medium.com/@profjsb/novelty-squared-dd88857f662#.j9jtwaxe9">Josh Bloom</a>:

"the challenge of finding work that may be simultaneously novel both to the domain scientist and to the core computation, statistical, and algorithmic scientist. "

???
This kind of research poses a particular kind of challenge, because both sides of the collaboration have to be interested in it. This is what Josh Bloom, an astrophysicst from our collaborating institute at Berkeley has called "The challenge of novelty squared"

--

“The last thing I want to have happen with an interdisciplinary collaboration is that my CS and stats colleagues find their contribution to be routine if not mundane.”

???

Living in the future has its downsides! This work will not produce a neuroscience paper in the immediate future. Instead, it might produce the systems that all neuroscientists will use in 5 years!

So - while novelty squared is hard, it is also potentially transformative!
---

### The challenge of reproducibility

Reproducibility is a bed-rock of the scientific method.

--

As data and computations become more elaborate, it's not enough to describe you did.

--

#### Show your work!

???
As I mentioned before, one of the challenges for DS is that as the data and computations become more elaborate, a simple verbal description of the procedures will not suffice.

Instead, one way to restore the trust in the reproducibility of the work is to conduct our research in a manner that is transparent and open.
---

### The three pillars of open science

<image src="images/gorgolewski-poldrack-three-pillars.png" height=400px>

  <a href="http://biorxiv.org/content/early/2016/02/12/039354.full.pdf+html">Gorgolewski and Poldrack (2016)</a>

???
Chris Gorgolewski and Russ Poldrack, two neuroscientists from Stanford recently wrote a paper introducing these three pillars of open science. They called for the publication of code and data, and for open dissemination of the papers.

At the eScience Institute, we spend a lot of time thinking about these things, and discussing them with researchers in various fields. We also spend a lot of time and energy developing open-source software. As I told you before, I am involved in a community that develops open-source software for the analysis of neuroimaging data in python.

This community is part of a much larger community of researchers and programmers that develop a whole eco-system of tools for data analysis and scientific research in Python
---

#### Open-source science: the scientific Python eco-system

<image src="images/python-ecosystem1.png" height=500px>

???

We all rely on the Python language itself
---

#### Open-source science: the scientific Python eco-system

<image src="images/python-ecosystem2.png" height=500px>

???

Over the years, people have developed excellent tools in Python to support basic computational tasks that are common across many fields. For example, a library called numpy supports numerical operations on multi-dimensional arrays of data, such as those in image data.

Another library called scipy supports a wide range of computations, signal processing, statistics, optimization, and so forth.
---

#### Open-source science: the scientific Python eco-system

<image src="images/python-ecosystem3.png" height=500px>

???
On top of these basic tools, others have built tools that support a variety of domain agnostic operations: machine learning, plotting, symbolic math, etc.

---

#### Open-source science: the scientific Python eco-system

<image src="images/python-ecosystem4.png" height=500px>

???
Finally, researchers in various domains

Part of what makes this ecosystem so powerful is the fact that information flows in both directions: researchers at the edges, in various domains rely on the central projects, such as numpy and scipy, but they also contribute back to the development of these projects, allowing everyone to enjoy the network effect of an open and collaborative development community.
---

### Neuroimaging in Python

<a href="http://nipy.org/"><image src="images/nipy-logo.png" height="40%"></a>

???
Much of my own work in this context has been out here in the Neuroimaging in Python community, but we also see ourselves as part of this broader community and several others at the eScience Institute actively contribute into this broader community, through their own domains, or to the core of the eco-system.
---

#### A physical space: The WRF Data Science Studio

<image src="images/DataScienceStudio.jpg" height=250px>
<p>
</p>
<image src="images/WRFLogo.png" height=100px>

???
In addition to the support of this kind of virtual communities, one important thing that the eScience Institute provides is a physical space for data science on campus. This space, built with support from Moore and Sloan, and from the Washington Research Foundation, the Data Science Studio is located at the top of the Physics/Astronomy tower on the Southwestern corner of campus.  

This bigh open plan space is home to a team of data scientists, including myself and also serves as a space for a variety of collaborative activities: hackathons, seminars, lecture series and conferences around data science.

One of the most popular activities that we pursue in this space are focused on education and collaboration.
---

### Teach a person to fish

<image src="images/swc-logo.png" height=200px>

???

Another activity that serves researchers across campus are workshops that we host at the Data Science Institute on a variety of topics.

One kind of workshop that has been very popular are Software Carpentry "bootcamps"
--

Volunteer-based organization

???

Software Carpentry is a volunteer-based organization and community of practice...
--

Teaches researchers basic computing skills:

???
That teaches researchers from a variety of fields basic computing skills
--

1. How to use the Unix shell
1. Basic programming
1. Version control
1. Sometimes also teach SQL and/or software testing.

???
How to use the unix operating shell to control their operating system, how to program in Python, or in R, how to use version control to make their research reproducible and open. Sometimes we also cover more advanced topics, such as use of data-bases, or software testing.
---

### Why is this worth doing?

???

You might ask: why is this worth doing? In the next couple of slides, I will argue that this is highly relevant to many of you, working at UW IT.

In a blog post that he wrote, Greg Wilson, the co-founder of Software Carpentry made three hypotheses
--

"Ask the managers of high-performance computing centers what fraction of their budget they spent on hardware, software, and training, and what fractions they would like to spend. My prediction is:"

<image src="images/gvwilson1.png">

<a href="http://software-carpentry.org/blog/2015/08/three-graphs-i-would-like-to-see.html
">Greg Wilson</a>

???
The first relates to the gap between the resources that are spent on training versus the need for these resources. Arguably, the best form of future-proofing is education, and we might ask whether we are doing enough of this form of future-proofing. I don't know.
---

### Why is this worth doing?

"Measure how much computing power all of the scientists at a university (not just those with HPC accounts) use during a year. My prediction is:"

<image src="images/gvwilson2.png">

  <a href="http://software-carpentry.org/blog/2015/08/three-graphs-i-would-like-to-see.html
  ">Greg Wilson</a>

???
The second hypothesis is about the impact of this kind of training. Greg posits that many researchers at the University today are not doing high-performance computing on Big Data. Rather, they are doing mediocre-performance computing on medium data: computing things on laptops or desktops on data sets on the order of Megabytes to Gigabytes in size.
---

### Why is this worth doing?
"Classify all the support requests received by HPC center staff according to technical complexity, and see how that changes after something like a two-day Software Carpentry workshop. My prediction is:"

<image src="images/gvwilson3.png">

  <a href="http://software-carpentry.org/blog/2015/08/three-graphs-i-would-like-to-see.html
  ">Greg Wilson</a>

???
The last hypothesis pertains to the kinds of questions that people will ask from the IT person in their department. One of the main value propositions of training like that provided in Software Carpentry workshops is that it raises the overall complexity of the interactions that researchers and IT people can have, because it brings researchers over the initial hump of clue-lessness to where they can ask more interesting questions, and collaborate more effectively with the IT people in their department.
---

### Data Science Incubator

--

Focused, intensive collaborative projects

--

Quarter-long

--

Data scientists and domain researchers work side-by-side

--

Researchers from departments across the university apply to participate.

--

Just finished our <a href="http://escience.washington.edu/get-involved/incubator-programs/winter-2016/">third cohort</a> of projects.

???
Another form of training and collaboration that we have been doing is the data science incubator.

As part of our effort to reach out to the campus community and collaborate with researchers from a wide range of fields, departments and institutes on campus, the incubator projects offer the possibility for a researcher or researchers to work together with us on a quarter-long. During the course of the quarter, we work together with the researchers shoulder-to-shoulder to implement the software needed.

We recently had the finishing presentations of the Winter Incubator. Many researchers who participated found it to be a highly productive : "I did more in these 10 weeks than I would be able to do on my own in a year!"

I'll show you one example of such a project
---

### Example incubator project

#### Pulse-trains to percepts : models for retinal prosthetics

Winter 2016

With <a href="http://faculty.washington.edu/ionefine/">Ione Fine</a> and <a href="http://faculty.washington.edu/gboynton/">Geoff Boynton</a>, Department of Psychology

---

### Retinal Prosthetics

<image height=60% src="images/retina-with-implants.png">

---

### Retinal Prosthetics

<image height=60% src="images/retinal-prosthetic-photo.png">

---

### Retinal Prosthetics

<image height=40% src="images/retinal-prosthetic1.png">

---

### Models: from pulse to percept

<image height="30%" src="images/cascade-model.png">

<small> Greenwald et al. (2009), Horsager et al. (2009, 2010, 2011), Nanduri et al. (2011, 2013)</small>
---

### Software: from pulse to percept

<image height="30%" src="images/cascade-model.png">

Implemented as open-source software: http://github.com/uwescience/pulse2percept

--

Technical challenge:

--

- Retina modeled at 25 `\(\mu m\)` resolution

--

- Pulse-trains modeled at 5 `\(\mu sec\)` resolution

--

- 3 second movie `\(\rightarrow \)`  `\(7.5 x 10^{12}\)` elements

--

#### Solution: parallelize and compute on Amazon Web Services

---

### A "virtual patient"

<video width="60%" height="auto" data-setup="{}" autoplay loop muted="muted"><source src="./videos/girlJumpsInPool.mov
"/> </video>


<video width="60%" height="auto" data-setup="{}" autoplay loop ><source src="./videos/girlJumpsInPool_percept_lambda6_ampmax_5.mov
"/> </video>

---

### A "virtual patient"

<video muted="muted" width="60%" height="auto" autoplay loop ><source src="./videos/platformBostonT.mov
"/> </video>

<video  width="60%" height="auto" autoplay loop ><source src="./videos/platformBostonT_percept_lambda6_ampmax_5.mov
"/> </video>

---


### Data Science for Social Good

Addresses two major challenges:

???

Another form of our incubator projects is our Data Science for Social Good Program (or DSSG). This program addresses two major challenges.
--

How do we provide training for data-scientists interested in social good?

???
The first is the education of data-scientists, especially in the social sciences, and fields that pertain to social good
--

How do we enable data-driven approaches in institutions devoted to social good?

???
The other is our ability to provide solutions to "real-world" problems outside the university.

--

<a href="http://urban.uw.edu/">Urban at UW
<image src="images/UrbanatUW-Seattle-World.png">
</a>

???
This project also dovetails with Urban at UW

Inspired by similar programs at the University of Chicago, and in the Atlanta Region, we initiated this program last summer.
---

### DSSG @ UW eScience 2015

--

16 student fellows

--

4 projects

--

Project leads from UW and from non-profit organizations in the region

--

???
The program consisted of 16 student-fellows, who, in teams of 4 pursued 4 different projects aimed at social good

---

#### Rerouting Solutions and Expensive Ride Analysis for King County Paratransit

Optimizing routing to reduce costs and develop tools to aid route planning

<image height="40%" src="images/paratransit-bus.png">

In collaboration with the <a href="https://tcat.cs.washington.edu/">Taskar Center for Accessible Technologies</a>
---

#### Rerouting Solutions and Expensive Ride Analysis for King County Paratransit

Optimizing routing to reduce costs and develop tools to aid route planning

<image height="70%" src="images/paratransit1.png">

---

#### Open Sidewalk Graph for Accessible Trip Planning

Connecting open sidewalk data through computational geometry

<image src="images/sidewalk-cleaning.png" height="40%">

In collaboration with the <a href="https://tcat.cs.washington.edu/">Taskar Center for Accessible Technologies</a>
---

#### Assessing Community Well-being through Open Data and Social Media

Creating a score-card for neighborhoods based on open data

<image src="images/report_page.png" height="40%">

In collaboration with <a href="http://thirdplacetechnologies.com/">Third Place Technologies</a>

---

#### Family homelessness: factors leading to permanent housing

Family Trajectories through Programs

<image height="35%" src="images/PierceTrajectories.png">

---

### DSSG @ UW eScience in 2016!

**Now accepting appplications for projects until March 30th**

<a href="http://escience.washington.edu/dssg-proposal">http://escience.washington.edu/dssg-proposal</a>

???

We are very excited to welcome a new cohort of DSSG fellows and projects this summer. Applications to participate as students have already closed (in fact, we are currently reviewing the more than 200 applications to participate!), but we are still soliciting applications for project proposals. Please spread the word about this program to your friends and colleagues on campus and beyond.
---

### Future proofing data-intensive discovery

#### The eScience Institute

--

  - Catalyzing collaborations

--

  - Building and maintaining the tools

--

  - Sustaining career paths in data-intensive research

--

- Training data-savvy researchers

---

### Come talk to us!

<image height="40%" src="images/eScience_Logo_RGB_PP.png">

The eScience Institute will have a table later today

--

Come to our <a href="http://escience.washington.edu/office-hours/">office hours</a> at the DSS!

---
class: center
layout: false

### Get in touch!

<div style="position:absolute; left: 220px; top:100px;">
  <img src="images/globe-xxl.png" width="100px;" style="background:none; border:none; box-shadow:none;">
  <div style="position:absolute; left: 120px; top:40px;">http://arokem.org
  </div>
</div>
<div style="position:absolute; left: 220px; top:220px;">
  <img src="images/email-11-xxl.png" width="100px;" style="background:none; border:none; box-shadow:none;">
  <div style="position:absolute; left: 120px; top:40px;">arokem@gmail.com
  </div>
</div>
<div style="position:absolute; left: 220px; top:340px;">
  <img src="images/twitter-xxl.png" width="100px;" style="background:none; border:none; box-shadow:none;">
  <div style="position:absolute; left: 120px; top:40px;">@arokem
  </div>
</div>
<div style="position:absolute; left: 220px; top:460px;">
  <img src="images/github-6-xxl.png" width="100px;" style="background:none; border:none; box-shadow:none;">
  <div style="position:absolute; left: 120px; top:40px;">github.com/arokem
  </div>
</div>



---

### Retinal Prosthetics

<image height="30%" src="images/paired-pulse-grid.png">

---

### Retinal Prosthetics

<image height="30%" src="images/paired-pulse-scoreboard-model.png">

---

### Retinal prosthetics:

<image height=40% src="images/paired-stimulation-percept.png">

---

### Retinal prosthetics: problems with the score-board model

<image height=40% src="images/paired-stimulation-w-oyster.png">
