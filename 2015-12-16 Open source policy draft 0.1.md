# DRAFT: Open source policy 0.1
December 16, 2015

## The basics

1. Open source your project if you can  
    * Work to mitigate fears from others in your project about open-sourcing
        - See “Fears of open sourcing & some ways to handle those (which we came up with and should publish somewhere)”
2. Software must have an attached license.
    * Never write your own license.
    * Unless there is a very good reason not to, you should use an OSI-approved Open Source License.
        - If your institution or project already has license policy, use that one.
        - Otherwise we advise choosing between [Apache 2.0](https://en.wikipedia.org/wiki/Apache_License),
        [BSD](https://en.wikipedia.org/wiki/BSD_licenses) or [MIT](https://en.wikipedia.org/wiki/MIT_License)),
        depending of your preferences
3. Open development should be enforced from the start of the project, if possible
    * Development should be done in a publicly visible version-controlled repository
        - This can be an institutionally hosted repository or externally hosted at e.g. [GitHub](https://github.com/),
        [BitBucket](https://bitbucket.org/)
        - You should use [semantic versioning](http://semver.org/)
    * You should make it clear what is being communicated via which channels “Channels should be well documented”
        - For guidance of what channels are useful see [relevant chapter in "Producing Open Source Software](http://producingoss.com/en/getting-started.html#communications-channels)
    * All decision-making should be transparent and on the recognised project communication channels
        - Avoid “private” decisions (e.g. discussing with your co-developer in the coffee room without then recording the decision publicly)
        - Have a public roadmap
        - Strive to include the community in decision-making, where possible
    * Be clear how people can contribute to your project
        - Make it clear how to setup your development environment and build the software
        - Create guidelines for common contribution tasks
        - Have a code “style guide” and build enforcement into your development workflow
            * For examples: https://github.com/google/styleguide/
        - Make sure contributions are allowed and compatible
            * Contributions should be in scope
            * Contributions should be checked for [license compatibility](http://www.gnu.org/licenses/license-list.html)
            * Contributors should have the right to contribute (see copyright)
        - Decide if you need a formal Contributor Agreement
        - Consider labelling issues by “ease of engagement” to encourage new contributors (need examples)
    * Your project should have a Code of Conduct in your repository and linked from your website (“Be nice”)
        - Make people feel appreciated for their contributions
        - Don’t assume you know why someone did something, check why
        - Examples are here: [contributor covenant](http://contributor-covenant.org/), [bundler](http://bundler.io/conduct.html),
        [CocoaPods](https://github.com/CocoaPods/CocoaPods/blob/master/CODE_OF_CONDUCT.md),
        [Django](https://www.djangoproject.com/conduct/), [rust](https://www.rust-lang.org/conduct.html)
    * Use [existing tools](http://oss-watch.ac.uk/resources/communitytools) to help manage your software,
    rather than creating your own  

## Developing the community

4. Work to build a community around your software  
    * Document what your software does!
        - Publish use cases
    * Publicise your software through conventional and non-conventional means
        - Consider nominating “evangelists” from your community
        - Use videos to help. Consider getting recognised scientists to record / appear in these
    * Create opportunities for participation
    * For instance hackathons, tutorials, workshops
    * “Piggy-back” on existing events that your community attends
        - e.g. BOSC, ISBE
5. Publish your software in a DOI-issuing repository
    * You should publish under the same license
    * You should get a DOI for each major release
        - And versions associated with publications coming from your project
    * Zenodo and FigShare both enable DOIs for [software citation](https://guides.github.com/activities/citable-code/)

## Striving for the meritocratic bazaar

6. Become more open as your project matures
    * Be transparent about your current governance model
    * Formalise your communication channels for your contributors
    * Open up your decision-making
        - See examples of different [open source governance models](http://oss-watch.ac.uk/resources/governancemodels)
    * Formalise roles in the project and the “promotion path”
    * How do people become associated with key roles?
    * Recognise that “you are not your code”
        - Be able to separate criticism of your software from criticism about yourself

## Fears of open sourcing & some ways to handle them
(See Victoria Stodden’s work on [identifying fears](http://stanford.edu/~vcs/papers/SMPRCS2010.pdf))

* “My software is such a bunch of hacks that no-one will want to contribute to it”
  *If it’s closed, no-one can contribute to it anyway. If it’s useful and open, then people could still contribute, even if the code quality is not great
* Someone takes my software and sets it up as a service, but wrongly. This would reflect badly on my original software (e.g. they used the wrong data).
    - You can use trademark enforcement of the name to make it clear that this is not your or your software’s responsibility
* “Other people need the ‘right data’ to be able to use my software, and I can’t give this to them because it’s protected/confidential/etc so my software is no use”
    - You can provide simulated/reference data which you should have in any case to help with testing
* “I am the expert in this field. I am the best person to build this software and don’t see how letting other people contribute will help my software”
    - You may be the expert in your field, but the software is just a tool you are building. You are probably not the expert in all aspects of the software you are creating.
peer review of the software code, not the science
* “It’ll be impossible to open source software which we have developed in collaboration with companies / industry because it will be too complicated to resolve the legal issues”
    - You could consult an IP specialist such as OSS-Watch
    - Using an OSI-approved license will make it easier as commercial IP legal departments recognise them
* “Getting my code ready to open source will take a lot of time and effort”
    - The expected time benefits often outweigh the initial investment (See: [Taverna move to Apache incubator process](http://www.taverna.org.uk/2014/10/20/taverna-has-been-accepted-as-an-apache-incubator-project/))
    - It will help your internal development team
  * Enhances skills and CV
* “An open source license will put off life sciences companies”
    - Many life sciences companies use open source software - they care about functionality and support. Examples: TBD
* “I’ll have to support users” / “I’ll have to support users who are not in my field”
    - it’ll foster collaboration and reputation in related fields, which can lead to new scientific collaborations and funding
    - Research funders want to see impact outside of your specific field
* “I will be liable if something bad happens when someone uses my software”
  *A good OSI-approved license will disclaim/waive liability better than having no license or an untested academic license
* “I should be doing science, not open-sourcing software”
    - Science is fundamentally based on accuracy and trust in results. Open source code can be more trusted (cf security community)
    than black box solutions (see [Shining light into black boxes paper](http://hkl.hms.harvard.edu/uploads/image/pdfs/sliz2012science.pdf))
* “I won’t receive any credit for my work”
    - Open-sourcing has been shown to improve citation and research impact in certain communities (reference needed)
* “People will scoop me”
    - Open-sourcing will tend to lead to more collaborations (leading to more publications) than other people scooping you (reference needed)
* “I won’t be able to publish a paper about my research / about my software”
    - There are now many avenues for publishing software papers, and many encourage open source licenses (examples needed)
* “I’ll have to pay for the cost of infrastructure”
    - There are many providers who allow you to use their resources for free if you are an open source project (examples)
