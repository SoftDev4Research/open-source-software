# DRAFT: Fears of open sourcing & some ways to handle them - publication annex - 1.0
Dec 22, 2016

# Fears of open sourcing & some ways to handle them

Although the scientific community is used to collaboration, competition is an established practice and drives many decisions on how to share information. It has been a trend to keep data and any other research artefact like software private even after research results get published. Thus it is not surprising many developers involved in research are victims of the fears of releasing software as Open Source [(Stodden, n.d.)](https://paperpile.com/c/Gzhyvy/EYsB). Though part of the fear might be justified we believe Open Source Software comes with more advantages than disadvantages, and some fears arise from a misunderstanding of the risks involved. In this appendix we aim to expose some of the common fear scenarios related to open sourcing and some ways to handle them.

## Principal Investigator Perspective

**My group's software (unique methodology, specificity, knowledge) gives our research a competitive edge that will be lost if we released our code in the open.**

* Research is far more than the software that facilitates it, and the software usually lags behind the underlying research ideas

* If your edge is only the software, it's just a matter of time until you're no longer competitive

* Open sourcing your software gives others the opportunity to identify issues and improvements, and addressing these may make you more competitive.

**It'll be impossible to Open Source software which we have developed in collaboration with companies / industry because it will be too complicated to resolve the legal issues**

* You could consult an IP specialist such as OSS-Watch [("OSS Watch - Independent Expert Advice on Open Source Software" 2016)](https://paperpile.com/c/Gzhyvy/WdPz), or a service resident at your institution that deals with IP issues, if your institution has one

* Using an OSI-approved license will make it easier as commercial IP legal departments recognise them

**Getting my code ready as Open Source will take a lot of time and effort**

* The expected time benefits often outweigh the initial investment. e.g. Taverna transition to the Apache Incubator [("Apache Taverna - Apache Taverna (incubating)" 2016)](https://paperpile.com/c/Gzhyvy/UNCc)

* It will help your internal development team in their adoption of best practices

* If your software provides value and others use it, that will strengthen your case for more funding, which will sponsor that time and effort

**An open source license will put off life sciences companies**

* Many life sciences companies use Open Source software - they care about functionality and support. Examples: Python, Perl, RDKit, OpenBabel, Linux, Docker, Apache Webserver, BioPython …

**I'll have to support users perhaps who are not in my field**

* You are not obligated to support users, although doing so can help foster collaboration and reputation in related fields, which can lead to new scientific collaborations and funding

* Having an impact outside of your own  field can prove valuable to research funders

* You are likely being affected by the same issues those users would want fixed

* You can resolve issues early that may affect your own research in the future

**I will be liable if something bad happens when someone uses my software**

* A good OSI-approved license will disclaim/waive liability better than having no license or an unexamined academic license

**My reputation will suffer if someone uses my software incorrectly, e.g. if someone publishes a paper based on results that use my software, but then if the paper must be withdrawn or retracted, my software may be blamed**

* Whether it's open or not, software is often distributed and used by people

* Improve your documentation to help avoid misuse in the first place.  This will also  help manuscript reviewers and the rest of the research community identify inappropriate use.

* If your software is not used, it will not be cited.

**I'll have to pay for the cost of infrastructure**

* There are many providers who allow you to use their resources for free if you are an open source project

* Continuous Integration testing, hosting of documentation, test coverage calculation, DOI are all given for free to Open Source projects. Hosting your own infrastructure is expensive, also in human resources. 

* Opening your source code does not require infrastructure on your part, you can just upload it to a repository hosting site like GitHub and BitBucket.

**People will scoop us**

* Open-sourcing will tend to lead to more collaborations (leading to more publications) than other people scooping you

* If your work is online and has a time step you can always prove that this is actually your idea/work. If you can state that literature/software mining (through community usage) in a beginning of a project could not have missed your project even better. 

* Just because your software is used by others, it doesn't mean you will be scooped. Software Projects like BioPython, OpenBabel are big players even in Industry and they published their work up years after the first public release.

## Developer Perspective

**My software is such a bunch of hacks that no-one will want to contribute to it**

* If it's closed, no-one can contribute to it anyway. If it’s useful and open, then people could still contribute, even if the code quality is not great

* Even inspiration (*how things were done once*) is worth sharing

* If your software is useful, others will convert these bunch of hacks into proper code

**I am the expert in this field. I am the best person to build this software and don't see how letting other people contribute will help my software**

* You may be the expert in your field, but the software is just a tool you are building. You are probably not the expert in all aspects of the software you are creating.

* Providing open code and (open) training might help others to become experts as well 

* Documentation should help train new contributors: code comments, usage, development setup

**Someone takes my software and sets it up as a service, but wrongly. This would reflect badly on my original software (e.g. they used the wrong data).**

* You can use trademark enforcement of the name to make it clear that this is not your or your software's responsibility

* Document your setup [better], automate it (use Docker or similar tools); keep communication channels in order

**Other people need the 'right data' to be able to use my software, and I can’t give this to them because it’s protected/confidential/etc so my software is of no use**

* You can provide simulated/reference data which you should have in any case to help with testing

**I should be doing science, not open-sourcing software**

* Science is fundamentally based on accuracy and trust in results. Open Source code can be more trusted (cf security community) than black box solutions (see [Shining light into black boxes paper](https://www.sciencemag.org/content/336/6078/159.summary))

* Don't overdo it if you don’t have time, just get what you have out there, it takes very little time

* You can do more science if you reuse software from others, to do so someone needs to open up their software stack - play well with the community and do the same to increase the "doing science" aspect.

**I won't receive any credit for my work**

* Open-sourcing has been shown to improve citation and research impact in communities

* Consider publishing your work in [The Journal of Open Source Software](http://joss.theoj.org/), see [http://joss.theoj.org/about](http://joss.theoj.org/about) for more information  

**I won't be able to publish a paper about my research / about my software**

* There are now many avenues for publishing software papers, and many encourage Open Source licenses.

# References

["Apache Taverna - Apache Taverna (incubating)." 2016. Accessed November 28. ](http://paperpile.com/b/Gzhyvy/UNCc)[https://taverna.incubator.apache.org/](https://taverna.incubator.apache.org/)[.](http://paperpile.com/b/Gzhyvy/UNCc)

["OSS Watch - Independent Expert Advice on Open Source Software." 2016. Accessed November 28. ](http://paperpile.com/b/Gzhyvy/WdPz)[http://oss-watch.ac.uk/](http://oss-watch.ac.uk/)[.](http://paperpile.com/b/Gzhyvy/WdPz)

[Stodden, Victoria. n.d. "The Scientific Method in Practice: Reproducibility in the Computational Sciences." ](http://paperpile.com/b/Gzhyvy/EYsB)*[SSRN Electronic Journa*l](http://paperpile.com/b/Gzhyvy/EYsB)[. doi:](http://paperpile.com/b/Gzhyvy/EYsB)[10.2139/ssrn.1550193](http://dx.doi.org/10.2139/ssrn.1550193)[.](http://paperpile.com/b/Gzhyvy/EYsB)

