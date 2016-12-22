# Authors

Please add your name and institution below if you would like to be an author. We are inviting everybody that contributed to the principles to review and be an author of this manuscript. We are trying to keep track of all the contributions in this [spreadsheet](https://docs.google.com/spreadsheets/d/1JyFX5q2CQU7gzTuXrHrxKWYthnE9YcNWmu-qtB-nNxc/edit?usp=sharing). Please let us know if we need to update the spreadsheet by making a comment inside the spreadsheet. 

* Rafael C Jimenez - ELIXIR Hub, Wellcome Genome Campus, Hinxton, CB10 1SD, UK. ORCID:0000-0001-5404-7670

* Steve Crouch - Web and Internet Science, University of Southampton, Southampton, United Kingdom.

* Mateusz Kuzak - Netherlands eScience Center, Science Park 140, 1098 XG Amsterdam, The Netherlands 

* Daniel Vaughan - EMBL-EBI, Wellcome Genome Campus, Hinxton, CB10 1SD, UK.

* Jonas Hagberg - National Bioinformatics Infrastructure Sweden (NBIS), Scilifelab, Department of Biochemistry and Biophysics (DBB), Stockholm University, Stockholm, Sweden orcid.org/0000-0003-2370-6025

* Daniel S. Katz, National Center for Supercomputing Applications & School of Information Sciences & Department of Electrical and Computer Engineering & Department of Computer Science, University of Illinois Urbana Champaign, USA; ORCID: 0000-0001-5934-7525

* Maarten van Gompel - Centre for Language and Speech Technology, Radboud University, Nijmegen, the Netherlands

* Maria Victoria Schneider, EMBL Australia Bioinformatics Resource, Lab-14, The University of Melbourne, 700 Swanston St, Parkville 3053, Victoria, Australia

* Madison Flannery, EMBL Australia Bioinformatics Resource, VLSCI node, Lab-14, The University of Melbourne, 700 Swanston St, Parkville 3053, Victoria, Australia

* Simon Gladman, EMBL Australia Bioinformatics Resource, VLSCI node, Lab-14, The University of Melbourne, 700 Swanston St, Parkville 3053, Victoria, Australia

* Philippa C. Griffin - EMBL Australia Bioinformatics Resource, Lab-14, The University of Melbourne, 700 Swanston St, Parkville 3053, Victoria, Australia

* Nathan S. Watson-Haigh - School of Agriculture, Food & Wine, University of Adelaide, South Australia, Australia; ORCID: 0000-0002-7935-6151

* Yasset Perez-Riverol - EMBL-EBI, Wellcome Genome Campus, Hinxton, CB10 1SD, UK.

* Björn Grüning, Bioinformatics Group, Department of Computer Science, University of Freiburg, Freiburg, Germany.

* Radka Svobodová Vařeková, CEITEC - Central European Institute of Technology & National Centre for Biomolecular Research, Masaryk University Brno, Brno, Czech Republic.

* [Andrew Treloar](http://andrew.treloar.net/), Australian National Data Service, 900 Dandenong Rd, Malvern East, 3145 Australia

* Bernard Pope - Victorian Life Sciences Computation Initiative (VLSCI),Lab-14, The University of Melbourne, 700 Swanston St, Parkville 3053, Victoria, Australia 

* Monther Alhamdoosh, CSL Limited, Bio21 Institute, 30 Flemington Road, Parkville, Victoria 3010, Australia

* Alejandra Gonzalez-Beltran, Oxford e-Research Centre, University of Oxford, Oxford, UK; ORCID: [0000-0003-3499-8262](http://orcid.org/0000-0003-3499-8262)

* Xiaochuan Wang, faculty of information technology, Monash University, 25 Exhibition Walk, Clayton VIC 3800

* Manuel Corpas, Repositive Ltd, Future Business Centre, Cambridge, UK

* Neil Chue Hong, Software Sustainability Institute, University of Edinburgh, JCMB, Peter Guthrie Tait Road, Edinburgh, EH9 3FD, UK.

* Harry-Anton Talvik, ELIXIR-EE, Institute of Computer Science, University of Tartu, Tartu, Estonia

* Bérénice Batut, Bioinformatics Group, Department of Computer Science, University of Freiburg, Freiburg, Germany.

* Allegra Via, IBBE, CNR, Bari, Italy & Biocomputing Group, Department of Physics, Sapienza University of Rome, Italy

* Jon Ison, Technical University of Denmark, Kemitorvet, Building 208, 2800 Kgs. Lyngby, Denmark

* Rowland Mosbergen, Stemformatics, University of Melbourne, Australia

* Michelle Barker, National eResearch Collaboration Tools and Resources, Australia. Orcid: 0000-0002-3623-172X

* Carole Goble, ELIXIR-UK, Software Sustainability Institute, School of Computer Science, The University of Manchester, Oxford Road, Manchester, M13 9PL, UK

* Mikael Borg, ELIXIR-SE, National Bioinformatics Infrastructure Sweden (NBIS), Scilifelab, Department of Biochemistry and Biophysics (DBB), Stockholm University, Stockholm, Sweden , ORCID: [0000-0002-0646-4231](https://orcid.org/0000-0002-0646-4231)

* Robert Pergl, ELIXIR-CZ, Czech Technical University in Prague, Faculty of Information Technology, Thákurova 9, 160 00 Praha 6, Czech Republic, ORCID: 0000-0003-2980-4400

* Salvador Capella-Gutierrez, ELIXIR-ES, Spanish National Bioinformatics Institute (INB), Spanish National Cancer Research Centre (CNIO), Melchor Fernandez Almagro 3, Madrid E-28026, Spain. ORCID: 0000-0002-0309-604X

* Victoria Stodden, University of Illinois at Urbana-Champaign. ORCID ID 0000-0003-2015-7825

# Title

Open Source Principles for Research Software

# Abstract

Research software is crucial infrastructure that underpins and enables modern scientific endeavour, yet software is not always developed following standard engineering practices that ensure quality and sustainability. This manuscript does not aim to propose or endorse software development best practices but rather to provide three simple principles that encourage adoption of existing best practices. These principles are designed around practical recommendations of how to make research software and its source code Findable, Accessible, Interoperable and Reusable (FAIR). This manuscript targets developers, but more importantly, it also targets organisations, projects, journals and funders that by adopting the principles will contribute to increasing quality and sustainability of research software.

# Keywords

Open Source, Code, Software, Principles, Open Science, Quality, Sustainability, FAIR

# Main Body

## Background

Developers globally recognise that the freedom to run, copy, distribute, study, change and improve software is extremely useful for an efficient and productive software engineering process.  These freedoms are enshrined through licensing of software source code.  It is commonly accepted that software is "open" and "free" if it released under license approved by both the Open Source Initiative (OSI) and the Free Software Foundation (FSF), and satisfies the criteria of the OSI Open Source Definition (https://opensource.org/docs/osd) and the FSF Free Software Definition (http://www.gnu.org/philosophy/free-sw.html). Open Source Software (OSS) development is used by organisations and projects to enable better software, science, and innovation [(Mulgan, Steinberg, and Salem 2005)](https://paperpile.com/c/InAwES/130C). OSS, particularly in the context of research, should not be a means to an end, but a collective intellectual product, a fundamental asset for building scientific knowledge [(Hettrick et al. 2016)](https://paperpile.com/c/InAwES/bENA). OSS not only increases transparency, discoverability, and visibility, but it is also a well proven mechanism for engagement of communities, social recognition, and trust among users [(McKiernan et al. 2016)](https://paperpile.com/c/InAwES/AIrV). OSS significantly increases the reproducibility of results generated by the software and facilitates software reuse and improvement [(Ince, Hatton, and Graham-Cumming 2012)](https://paperpile.com/c/InAwES/Bnw2). Opening code to the public is also an opportunity for developers to showcase their work, becoming a platform for adoption of software development best practices [(Leprevost et al. 2014)](https://paperpile.com/c/InAwES/ozy6). Thus we believe that OSS promotes quality and sustainability of software, leading to the delivery of better research.

## Purpose and scope

This manuscript describes a core set of OSS principles to improve the quality and sustainability of research software. It does not propose software development best practices but rather easy-to-implement principles that encourage adoption of existing best practices. The principles are intentionally few and simple, to lower the barrier of adoption. These principles do not aim to describe in detail how to develop software, but rather lay out recommendations on how to make research software and its source code findable, accessible, interoperable and reusable (FAIR), following the example of the FAIR Guiding Principles for scientific data management and stewardship [(Wilkinson et al. 2016)](https://paperpile.com/c/InAwES/t8a5). While the FAIR principles were originally designed for data, they are sufficiently general that the concepts can be applied to software. The OSS principles should be applied following existing and complementary best practices describing more specific methods of how to develop software. Some of these best practices are related to version control, code review, automated testing, code formatting, documentation, etc. [(Wilson et al. 2016)](https://paperpile.com/c/InAwES/zOsY) [(Wilson et al. 2014)](https://paperpile.com/c/InAwES/v1X7) [(Artaza et al. 2016)](https://paperpile.com/c/InAwES/YEpt) [(Leprevost et al. 2014)](https://paperpile.com/c/InAwES/ozy6) [(Perez-Riverol et al. 2016)](https://paperpile.com/c/InAwES/mEWk) ([10 Best Practices for Quality Software Development](http://shop.oreilly.com/product/0636920055570.do)). This manuscript also aims to encourage organisations, projects, journals and funders not just to endorse the principles but to drive compliance through software policies. The principles are also accompanied by a list of arguments addressing common questions and fears raised by the research community when considering open sourcing their software.

In this manuscript, software is widely defined to include command line software like R scripts, graphical user interfaces like desktop applications, web-based services like application program interfaces (APIs) and infrastructure scripts that help to run services.

## Audience

Our target audience includes leaders and managers of organisations and projects, journal editorial bodies, as well as funding agencies concerned with the provision of products and services that rely on the development of open research software. We want to provide these stakeholders with a simple approach to drive, incentivise, and support the development of better software. Though these OSS principles have mostly been developed within, and received feedback from, the life science community, the document and its principles generally apply to all research fields.

Strategies to increase software quality usually target software developers, focusing on training and adoption of best practices [(Wilson et al. 2014)](https://paperpile.com/c/InAwES/v1X7). This approach can yield good results, but requires a significant effort as well as personal commitment from developers [(Wilson 2014)](https://paperpile.com/c/InAwES/1XuR). For an organisation employing developers and working with diverse programming languages, software projects and experience levels, it is not easy to endorse specific best practices or define a broad range of training needs. It is easier to endorse a set of basic principles that are simple to monitor, simple to comply with, and will drive the adoption of best practices and reveal training needs. The OSS principles aim to create awareness, encouraging developers to be more conscious of the extent to which they are complying with best practices, and making them more willing to collaborate and request support if needed. In other words, they define a path but still give developers freedom to choose how to implement best practices.

We encourage organisations, projects, journals, as well as funding agencies to adopt the OSS principles. We see endorsement as the first step: that is, agreeing to support the OSS principles without a formal process for implementationcommitment. Promotion is a second step: that is, actively publicising and incentivising the OSS principles within the organisation as well as globally. Compliance is the third step: to formally implement them within the organisation, with ongoing monitoring and public reporting if possible. To facilitate progress, we propose that organisations, projects, journals, as well as funding agencies include these OSS principles as part of their policies related to the development and publication of software.

## Contributions

The OSS principles have been developed by a wide range of stakeholders who are concerned with the production of quality software for research. Further information and development realted to the OSS principles can be found in the following site: [https://github.com/SoftDev4LS/open-source-software](https://github.com/SoftDev4LS/open-source-software) 

## Principles

### 1. Findable

#### Make software easy to discover by providing software metadata via a popular community registry

Facilitate the discoverability of the open source software projects by registering metadata related to the software, including information like the source code location, contributors, and license, in a popular community registry, making your source code more discoverable. Metadata registration:

* Increases the visibility of the project, the software, its use, its successes, its references, and its contributors

* Provides easy access for software packagers to deploy your software, thus increasing visibility

* Encourages software providers to think about the metadata that describes software as well as how to expose such metadata.

* Increases the chances of collaboration, reuse, and improvement.

Examples of community registries of software metadata are [bio.tools](http://bio.tools) [(Ison et al. 2016)](https://paperpile.com/c/InAwES/WPnl) and [biojs.io](https://biojs.io) [(Gómez et al. 2013)](https://paperpile.com/c/InAwES/JKMf)[(Corpas et al. 2014)](https://paperpile.com/c/InAwES/k1R2) in the life sciences and [DataCite](https://www.datacite.org) [(Brase)](https://paperpile.com/c/InAwES/Oy7X) as a generic metadata registry not just for data but software.

### 2. Accessible

#### Develop publicly accessible open source code from day one 

Start a project as open source from the very first day, in a publicly accessible, version controlled repository (e.g., github.com and bitbucket.org). The longer a project is run in a closed manner, the harder it is to open source it later [(Fogel 2005)](https://paperpile.com/c/InAwES/uCrh). Opening code and exposing the software development life cycle publicly from day one:

* Promotes trust in the software and broader project

* Facilitates the discovery of existing software development projects

* Provides a historical public record of contributions from the start of the project and helps to track recognition

* Encourages contributions from the community 

* Increases opportunities for  collaboration and reuse

* Exposes work for community evaluation, suggestions and validation

* Increases transparency through community scrutiny

* Encourages developers to think about and showcase good coding practices

* Facilitates reproducibility of scientific results generated by all prior versions of the software

* Encourages developers to provide documentation, both detailed user manual and clear in-code comments

If there is a compelling reason why the code cannot be Open Source, it is a good practice to inform the community about the software and software development process via the project website or a software registry. Some common doubts and questions about making software Open Source are discussed in the attached appendix, "[Fears of open-sourcing your software project](https://docs.google.com/document/d/1EvhqaDlC1u2iVfqGv-lvPGOgTM5Gc0zRbe70OhaBcqM/edit?usp=sharing)".

### 3. Interoperable and Reusable

#### Adopt a license and comply with the licence of third-party dependencies

Provide instructions and guidelines for other projects and software to use, modify and redistribute the software and the source code. Adopt a suitable Open Source license, include it in a publicly accessible source code repository, and ensure the software complies with the licenses of all third party dependencies. Providing a license: 

* Enables using the code in jurisdictions where "code with no license" means it cannot be used at all

* Clarifies the responsibilities and rights placed on third parties wishing to use, copy, redistribute, modify and/or reuse your source code

* Protects the software's intellectual property

* Provides a model for long-term sustainability by enabling legally well-founded contributions and reuse

* Provides primary purpose and developmental environment of the initial development and whether it has been further improved to achieve more generalized functionalities

We advise choosing a [OSI-approved Open Source License](https://opensource.org/licenses) following these [guidelines](http://choosealicense.com/) unless your institution or project requires a different license.

## Open development

Open sourcing your software does not mean the software has to be developed in a publicly collaborative manner. Although it is desirable, the OSS principles do not mandate a strategy for collaborating with the community. Ideally, projects should be clear and transparent about how to contribute to them, their governance model, and their communication channels.

# Conclusion

The OSS principles aim to positively impact the adoption of best practices and thus help to develop better and more sustainable software. These principles are designed around practical recommendations of how to make research software and its source code findable, accessible, interoperable and reusable (FAIR).  Unlike many software development best practices tailored for software developers, the OSS principles aim to target a wider audience, particularly research funders, research institutions, journals, group leaders, and managers of projects producing research software. We recommend that organisations and projects adopt the OSS principles and include these principles as part of their policies to facilitate the process of adoption. Due to their simplicity and the low barrier for adoption, we would like to see many projects and organisations joining to this initiative.

# Grant Information

# Acknowledgments

# Supplementary Material

[Fears of open-sourcing your software project](https://docs.google.com/document/d/1EvhqaDlC1u2iVfqGv-lvPGOgTM5Gc0zRbe70OhaBcqM/edit?usp=sharing)

# Competing Interests

At the time of writing MC is employee of Repositive Ltd.

# References

[Artaza, Haydee, Neil Chue Hong, Manuel Corpas, Angel Corpuz, Rob Hooft, Rafael C. Jimenez, Brane Leskošek, et al. 2016. "Top 10 Metrics for Life Science Software Good Practices." ](http://paperpile.com/b/InAwES/YEpt)*[F1000Researc*h](http://paperpile.com/b/InAwES/YEpt)[ 5 (August). doi:](http://paperpile.com/b/InAwES/YEpt)[10.12688/f1000research.9206.1](http://dx.doi.org/10.12688/f1000research.9206.1)[.](http://paperpile.com/b/InAwES/YEpt)

[Hettrick, Antonioletti, Carr, Chue Hong, Crouch, De Roure, Emsley, et al. 2016. "UK Research Software Survey 2014." Accessed November 27. doi:](http://paperpile.com/b/InAwES/bENA)[10.5281/zenodo.14809](http://dx.doi.org/10.5281/zenodo.14809)[.](http://paperpile.com/b/InAwES/bENA)

[Ince, Darrel C., Leslie Hatton, and John Graham-Cumming. 2012. "The Case for Open Computer Programs." ](http://paperpile.com/b/InAwES/Bnw2)*[Natur*e](http://paperpile.com/b/InAwES/Bnw2)[ 482 (7386): 485–88.](http://paperpile.com/b/InAwES/Bnw2)

[Leprevost, Felipe da Veiga, Valmir C. Barbosa, Eduardo L. Francisco, Yasset Perez-Riverol, and Paulo C. Carvalho. 2014. "On Best Practices in the Development of Bioinformatics Software." ](http://paperpile.com/b/InAwES/ozy6)*[Frontiers in Genetic*s](http://paperpile.com/b/InAwES/ozy6)[ 5 (July): 199.](http://paperpile.com/b/InAwES/ozy6)

[McKiernan, Erin C., Philip E. Bourne, C. Titus Brown, Stuart Buck, Amye Kenall, Jennifer Lin, Damon McDougall, et al. 2016. "How Open Science Helps Researchers Succeed." ](http://paperpile.com/b/InAwES/AIrV)*[eLif*e](http://paperpile.com/b/InAwES/AIrV)[ 5. doi:](http://paperpile.com/b/InAwES/AIrV)[10.7554/elife.16800](http://dx.doi.org/10.7554/elife.16800)[.](http://paperpile.com/b/InAwES/AIrV)

[Mulgan, Geoff, Tom Steinberg, and Omar Salem. 2005. ](http://paperpile.com/b/InAwES/130C)*[Wide Open: Open Source Methods and Their Future Potentia*l](http://paperpile.com/b/InAwES/130C)[. Demos Medical Publishing.](http://paperpile.com/b/InAwES/130C)

[Wilkinson, Mark D., Michel Dumontier, I. Jsbrand Jan Aalbersberg, Gabrielle Appleton, Myles Axton, Arie Baak, Niklas Blomberg, et al. 2016. "The FAIR Guiding Principles for Scientific Data Management and Stewardship." ](http://paperpile.com/b/InAwES/t8a5)*[Scientific Dat*a](http://paperpile.com/b/InAwES/t8a5)[ 3 (March): 160018.](http://paperpile.com/b/InAwES/t8a5)

[Wilson, Greg, D. A. Aruliah, C. Titus Brown, Neil P. Chue Hong, Matt Davis, Richard T. Guy, Steven H. D. Haddock, et al. 2014. "Best Practices for Scientific Computing." ](http://paperpile.com/b/InAwES/v1X7)*[PLoS Biolog*y](http://paperpile.com/b/InAwES/v1X7)[ 12 (1): e1001745.](http://paperpile.com/b/InAwES/v1X7)

[Wilson, Greg, Jennifer Bryan, Karen Cranston, Justin Kitzes, Lex Nederbragt, and Tracy K. Teal. 2016. "Good Enough Practices in Scientific Computing." ](http://paperpile.com/b/InAwES/zOsY)[http://arxiv.org/abs/1609.00037](http://arxiv.org/abs/1609.00037)[.](http://paperpile.com/b/InAwES/zOsY)

## Other references to bear in mind

These were mentioned during the process of creating the principles but they haven't been referenced yet.

* [Open science, open access and open source software at Open Medicine](https://www.ncbi.nlm.nih.gov/pubmed/21602946). PMID:21602946

* Open Source Software in Life Science Research: Practical Solutions to Common Challenges in the Pharmaceutical Industry and Beyond

* [If you want reproducible science, the software needs to be open source](http://arstechnica.com/science/2012/02/science-code-should-be-open-source-according-to-editorial/)

* [Managing Open Source Contributions for Software Project Sustainability](http://web.cecs.pdx.edu/~bart/papers/picmet-patch.pdf)

* [Visualizing Contribution Patterns in Open Source](http://ir.library.oregonstate.edu/xmlui/bitstream/handle/1957/57265/thesis.pdf?sequence=1)

* [Open Source Software. Australian government](http://www.finance.gov.au/policy-guides-procurement/open-source-software/)

* [Maximizing the reproducibility of your research](https://www.fosteropenscience.eu/content/maximizing-reproducibility-your-research)

* [R's role in science breakthrough: reproducibility of psychology studies](http://blog.revolutionanalytics.com/2016/01/rs-role-in-science-breakthrough-reproducibility-of-psychology-studies.html)

* [Public service coding: the BBC as an open software developer](http://www.nesta.org.uk/blog/public-service-coding-bbc-open-software-developer#sthash.uBOc2l03.dpuf)

* [The 7 principles of successful open source communities](http://www.opensourceconsortium.org/images/stories/sevenprinciples.pdf)

* [CLARIAH Guidelines for software quality & sustainability](https://github.com/CLARIAH/software-quality-guidelines)

* [Bioconductor: open software development for computational biology and bioinformatics](http://genomebiology.biomedcentral.com/articles/10.1186/gb-2004-5-10-r80)

* [Ten recommendations for creating usable bioinformatics command line software](http://gigascience.biomedcentral.com/articles/10.1186/2047-217X-2-15)

* [Carole Goble, Better software, better research, IEEE Internet Computing, 18(5), 4-8, 2014](http://ieeexplore.ieee.org/document/6886129/) 

* [Allen et al, ](http://gigascience.biomedcentral.com/articles/10.1186/2047-217X-2-15)[Lightning Talk: "I solemnly pledge" A Manifesto for Personal Responsibility in the Engineering of Academic Software](http://homepages.cwi.nl/~jurgenv/papers/WSSSPE-2016.pdf)[,4th WSSSPE 2016, Manchester, UK](http://gigascience.biomedcentral.com/articles/10.1186/2047-217X-2-15)

## Important best practices that will not be considered in this paper

### Versioned releases

It is recommended to publish proper releases of your software points in time when deemed appropriate. A release should carry a version number in an established semantic versioning scheme (e.g. v1.2). This facilitates citability, scientific reproducibility and packaging. In the source code repository, the state corresponding to the version should receive a version proper tag, clearly allowing inspection of the state at the time of the release, as well as of what has changed since then. Releases are generally accompanied by releases notes or an explicit changelog. Releases should be uploaded to more persistent repositories (e.g. Zenodo (NOTE:  https://zenodo.org/)) where they receive a Digital Object Identifier (DOI) unique to the version, again facilitating citability and reproducibility.

### Installable packages

The infrastructure surrounding a programming language or platform often offers repositories where software packages, corresponding to the versioned releases, can be deposited for easy installation by the general user base. Examples are the Python Package Index (NOTE:  https://pypi.org) for Python software, Maven (NOTE:  https://maven.org) for Java, CPAN (NOTE:  http://www.cpan.org) for Perl, CRAN (NOTE:  https://cran.r-project.org) for R, as well as the numerous package repositories specific to Linux distributions; for mobile devices there are repositories such as Google Play and F-Droid (Android) or the App Store (iOS). If the software fits inside such an ecosystem or has a dedicated target platform, it is recommended to package and publish software in the appropriate repositories whenever available and deemed worth the effort, as this greatly benefits accessibility and findability. Contributing in such a fashion also strengthens the larger open source community and benefits interoperability as it enables third party software to depend on yours more easily.

### Documentation

Provide documentation for all the intended audiences of your software (e.g. end-users, developers, system administrators), addressing each at their appropriate level. Good documentation is essential for software to be accessible and reusable.

Like the software itself, the documentation should be released under an open license. Both the documentation and its sources should be publicly available and are best stored in the version control repository alongside the source code. This provides clarity as to what version of the software is described by the documentation, though it takes manual effort to ensure the documentation is always up to date and covers all the features of the software. For certain types of documentation such as API references for developers, the source code can also be the source of documentation, as documentation can be generated from commented source code by automated tools (NOTE:  Examples of popular documentation generators today are Doxygen (http://www.stack.nl/~dimitri/doxygen/), javadoc (http://www.oracle.com/technetwork/java/javase/documentation/index-jsp-135444.html) and Sphinx (http://www.sphinx-doc.org/).
).

#### Adopt an automated deployment / distribution strategy

Provide options to allow the project to be easily deployed and distributed. This could include using Virtual Machine environments like Vagrant, containerization like Docker or Singularity, or automated deployment tools like Ansible.

Adopting a deployment/distribution strategy depends on the type of software (see RM#1) and the type of environment the software will run on. For example, containerization for a command line package that will run on a High Performance Computer (HPC) will be better supported using Singularity rather than Docker. This is due to the locked down nature of the HPC environment.

The benefits of adopting an automated deployment / distribution strategy include (NOTE: this is very similar to the benefits mentioned in the open source code):

* Facilitates the discovery and benchmarking of existing software development projects

* Encourages contributions from the community 

* Facilitates reproducibility of scientific results across environments

* Increases opportunities for collaboration and reuse

* Increases transparency through community scrutiny

* Increases the quality of the software by forcing developers to provide working examples to the community (similar to providing test data in R Bioconductor packages)

Examples are the Python Package Index (NOTE:  https://pypi.org) for Python software, Maven (NOTE:  https://maven.org) for Java, CPAN (NOTE:  http://www.cpan.org) for Perl, CRAN (NOTE:  https://cran.r-project.org) for R, as well as the numerous package repositories specific to Linux distributions; for mobile devices there are repositories such as Google Play and F-Droid (Android) or the App Store (iOS) [Taken from the "Important best practices that will not be considered in this paper" section - I think it should really be in here as exemplars of this reusable principle].

