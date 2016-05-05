# DRAFT: Open source policy 0.2
March 08, 2016

Scope? System developer that want to convince managers or PIs? 

## The basics
1. Open source your project unless you cannot (open by default)
    1. Work to mitigate fears from others in your project about open-sourcing
        1. See "[Fears of open sourcing & some ways to handle those](#heading=h.gewa6vf90ds1) (which we came up with and should publish somewhere)"
2. Software must have an attached license.
    2. Unless there is a very good reason not to, you should use an [OSI-approved Open Source License](https://opensource.org/licenses). 
        2. If your institution or project already has license policy, use that one. 
        3. Otherwise we advise choosing one of the license here ([link](http://choosealicense.com/)), depending of your preferences
    3. If you cannot use an OSI-approved Open Source License, at least adhere to template of [OSI-approved Open Source License](https://opensource.org/licenses) or [Free for academic use Licence](https://opensource.org/licenses/artistic-license-2.0).
3. Open development should be enforced from the start of the project, if possible
    4. Development should be done in a publicly visible version-controlled repository
        4. This can be an institutionally hosted repository or externally hosted at e.g. GitHub, BitBucket
        5. You should use semantic versioning (see [http://semver.org/](http://semver.org/))
    5. You should make it clear what is being communicated via which channels "Channels should be well documented"
        6. For guidance of what channels are useful [see this document](http://producingoss.com/en/getting-started.html#communications-channels) 
    6. All decision-making should be transparent and on the recognised project communication channels
        7. Avoid "private" decisions (e.g. discussing with your co-developer in the coffee room without then recording the decision publicly) 
        8. Have a public roadmap
        9. Strive to include the community in decision-making, where possible
    7. Be clear how people can contribute to your project
        10. Make it clear you really want people to contribute
        11. Make it clear how to setup your development environment and build the software
        12. good practice is to create CONTRIBUTING file, that describes how to contribute ([some more details on GitHub docs](https://github.com/blog/1184-contributing-guidelines))
        13. Create guidelines for common contribution tasks
        14. Have a code "style guide" and build enforcement into your development workflow
            1. For examples: [https://github.com/google/styleguide/](https://github.com/google/styleguide/)
            2. Use linters to enforce adherence to the style guide (example: [eslint](http://eslint.org/))
        15. Make sure contributions are allowed and compatible
            3. Contributions should be in scope
            4. Contributions should be checked for license compatibility (see: [http://www.gnu.org/licenses/license-list.html](http://www.gnu.org/licenses/license-list.html))
            5. Contributors should have the right to contribute (see copyright)
        16. Decide if you need a formal Contributor Agreement
        17. Consider labelling issues by "ease of engagement" to encourage new contributors
    8. Your project should have a Code of Conduct in your repository and linked from your website ("Be nice")
        18. Make people feel appreciated for their contributions - thank them
        19. Don't assume you know why someone did something, check why
        20. Examples are here: [contributor covenant](http://contributor-covenant.org/)
    9. Use existing tools to help manage your software, rather than creating your own (see link on OSS-Watch website, [http://oss-watch.ac.uk/resources/communitytools](http://oss-watch.ac.uk/resources/communitytools))

## Developing the community
4. Work to build a community around your software
    10. Document what your software does!
        21. Publish use cases 
    11. Publicise your software through conventional and non-conventional means
        22. Consider nominating "evangelists" from your community
        23. Use videos to help. Consider getting recognised scientists to record / appear in these
        24. Consider the types of users you wish to attract when presenting your software at conferences, meetings, etc. to grow its community - e.g. end-users, developers, user/developers
    12. Create opportunities for participation
        25. For instance hackathons, tutorials, workshops
    13. "Piggy-back" on existing events that your community attends
        26. e.g. BOSC, ISBE
5. Publish your software in a DOI-issuing repository
    15. You should publish under the same license
    16. You should get a DOI for each major release
        27. And versions associated with publications coming from your project
    17. Zenodo and FigShare both enable DOIs for software [https://guides.github.com/activities/citable-code/](https://guides.github.com/activities/citable-code/) 
    18. Advertise the DOI at the top level of your repository and in a CITATION file
    
## Striving for the meritocratic bazaar
6. Become more open as your project matures 
    19. Be transparent about your current governance model
    20. Formalise your communication channels for your contributors
    21. Open up your decision-making
        28. For examples of different open source governance models see: [http://oss-watch.ac.uk/resources/governancemodels](http://oss-watch.ac.uk/resources/governancemodels)
    22. Formalise roles in the project and the "promotion path"
        29. How do people become associated with key roles?
    23. Recognise that "you are not your code"
        30. [Be able to separate criticism of your software from criticism about yourself](http://www.goodreads.com/quotes/33711-don-t-take-anything-personally-nothing-others-do-is-because-of)
# Fears of open sourcing & some ways to handle them
(See Victoria Stodden's work on identifying fears: [http://stanford.edu/~vcs/papers/SMPRCS2010.pdf](http://stanford.edu/~vcs/papers/SMPRCS2010.pdf) )
* "My software is such a bunch of hacks that no-one will want to contribute to it"
    * If it's closed, no-one can contribute to it anyway. If it’s useful and open, then people could still contribute, even if the code quality is not great
    * Even inspiration (*how things were done once*) is worth sharing
* Someone takes my software and sets it up as a service, but wrongly. This would reflect badly on my original software (e.g. they used the wrong data).
    * Way #1: You can use trademark enforcement of the name to make it clear that this is not your or your software's responsibility
    * Way #2: Document your setup [better], automate it (use Docker or similar tools); keep communication channels in order
* "My group's software (unique methodology, specificity, knowledge) gives our research a competitive edge that will be lost if we released our code in the open."
    * Research is way more than the software that facilitates it, and the software usually lags the ideas
    * If your edge is only the software, it's just a matter of time until you're no longer competitive
    * Your research is probably held back by the bugs you haven't found yet that others would
* "Other people need the 'right data' to be able to use my software, and I can’t give this to them because it’s protected/confidential/etc so my software is no use"
    * You can provide simulated/reference data which you should have in any case to help with testing
* "I am the expert in this field. I am the best person to build this software and don't see how letting other people contribute will help my software"
    * You may be the expert in your field, but the software is just a tool you are building. You are probably not the expert in all aspects of the software you are creating.
    * Providing open code and (open) training might help others to become experts as well 
    * Documentation should help train new contributors: code comments, usage, development setup
* "It'll be impossible to open source software which we have developed in collaboration with companies / industry because it will be too complicated to resolve the legal issues"
    * You could consult an IP specialist such as OSS-Watch
    * Using an OSI-approved license will make it easier as commercial IP legal departments recognise them
* "Getting my code ready to open source will take a lot of time and effort"
    * The expected time benefits often outweigh the initial investment
        * You 
        * (See: Taverna move to Apache incubator process)
    * It will help your internal development team
        * Enhances skills and CV
* "An open source license will put off life sciences companies"
    * Many life sciences companies use open source software - they care about functionality and support
        * Examples:
* "I'll have to support users" / “I’ll have to support users who are not in my field”
    * it'll foster collaboration and reputation in related fields, which can lead to new scientific collaborations and funding
    * Research funders want to see impact outside of your specific field
* "I will be liable if something bad happens when someone uses my software"
    * A good OSI-approved license will disclaim/waive liability better than having no license or an untested academic license be it open or not, software will be distributed and used by people
* "I should be doing science, not open-sourcing software"
    * Science is fundamentally based on accuracy and trust in results. Open source code can be more trusted (cf security community) than black box solutions (see [Shining light into black boxes paper](https://www.sciencemag.org/content/336/6078/159.summary))
* "I won't receive any credit for my work"
    * Open-sourcing has been shown to improve citation and research impact in certain communities 
* "People will scoop me"
    * Open-sourcing will tend to lead to more collaborations (leading to more publications) than other people scooping you
* "I won't be able to publish a paper about my research / about my software"
    * There are now many avenues for publishing software papers, and many encourage open source licenses
* "I'll have to pay for the cost of infrastructure"
    * There are many providers who allow you to use their resources for free if you are an open source project
