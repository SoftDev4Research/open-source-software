# open-source-software
Open Source Software guidelines recommended by the SoftDev4LS working group

## The basics

1. Open source your project if you can  
  a. Work to mitigate fears from others in your project about open-sourcing  
    i . See “Fears of open sourcing & some ways to handle those (which we came up with and should publish somewhere)”  
2. Software must have an attached license.  
  a. Never write your own license.  
  b. Unless there is a very good reason not to, you should use an OSI-approved Open Source License.  
    i. If your institution or project already has license policy, use that one.  
    ii. Otherwise we advise choosing one of the license here (link needed - Apache 2, BSD, MIT??), depending of your preferences  
3. Open development should be enforced from the start of the project, if possible  
  a. Development should be done in a publicly visible version-controlled repository  
    i. This can be an institutionally hosted repository or externally hosted at e.g. GitHub, BitBucket  
    ii. You should use [semantic versioning](http://semver.org/)  
  b. You should make it clear what is being communicated via which channels “Channels should be well documented”  
    i. For guidance of what channels are useful see:  
  c. All decision-making should be transparent and on the recognised project communication channels  
    i. Avoid “private” decisions (e.g. discussing with your co-developer in the coffee room without then recording the decision publicly)  
    ii. Have a public roadmap  
    iii. Strive to include the community in decision-making, where possible  
  d. Be clear how people can contribute to your project  
    i. Make it clear how to setup your development environment and build the software  
    ii. Create guidelines for common contribution tasks  
    iii. Have a code “style guide” and build enforcement into your development workflow  
      1. For examples: https://github.com/google/styleguide/  
    iv. Make sure contributions are allowed and compatible  
      1. Contributions should be in scope  
      2. Contributions should be checked for [license compatibility](http://www.gnu.org/licenses/license-list.html)  
      3. Contributors should have the right to contribute (see copyright)  
    v. Decide if you need a formal Contributor Agreement  
    v. Consider labelling issues by “ease of engagement” to encourage new contributors  
  e. Your project should have a Code of Conduct in your repository and linked from your website (“Be nice”)  
    i. Make people feel appreciated for their contributions  
    ii. Don’t assume you know why someone did something, check why  
    iii. Examples are here: TBD  
  f. Use [existing tools](http://oss-watch.ac.uk/resources/communitytools) to help manage your software, rather than creating your own  

## Developing the community

4. Work to build a community around your software  
  a. Document what your software does!  
    i. Publish use cases  
  b. Publicise your software through conventional and non-conventional means  
    i. Consider nominating “evangelists” from your community  
    ii. Use videos to help. Consider getting recognised scientists to record / appear in these  
  c. Create opportunities for participation  
    i. For instance hackathons, tutorials, workshops  
  d. “Piggy-back” on existing events that your community attends  
    i. e.g. BOSC, ISBE  
5. Publish your software in a DOI-issuing repository  
  a. You should publish under the same license  
  b. You should get a DOI for each major release  
    i. And versions associated with publications coming from your project  
  c. Zenodo and FigShare both enable DOIs for [software citation](https://guides.github.com/activities/citable-code/)  

##Striving for the meritocratic bazaar

6. Become more open as your project matures  
  a. Be transparent about your current governance model  
  b. Formalise your communication channels for your contributors  
  c. Open up your decision-making  
    i. See examples of different [open source governance models](http://oss-watch.ac.uk/resources/governancemodels)  
  d. Formalise roles in the project and the “promotion path”  
    i. How do people become associated with key roles?  
  e. Recognise that “you are not your code”  
    i. Be able to separate criticism of your software from criticism about yourself  

## Fears of open sourcing & some ways to handle them
(See Victoria Stodden’s work on [identifying fears](http://stanford.edu/~vcs/papers/SMPRCS2010.pdf))

* “My software is such a bunch of hacks that no-one will want to contribute to it”  
  *If it’s closed, no-one can contribute to it anyway. If it’s useful and open, then people could still contribute, even if the code quality is not great  
* Someone takes my software and sets it up as a service, but wrongly. This would reflect badly on my original software (e.g. they used the wrong data).  
  *You can use trademark enforcement of the name to make it clear that this is not your or your software’s responsibility  
* “Other people need the ‘right data’ to be able to use my software, and I can’t give this to them because it’s protected/confidential/etc so my software is no use”  
  * You can provide simulated/reference data which you should have in any case to help with testing  
* “I am the expert in this field. I am the best person to build this software and don’t see how letting other people contribute will help my software”  
  * You may be the expert in your field, but the software is just a tool you are building. You are probably not the expert in all aspects of the software you are creating.  
  * peer review of the software code, not the science  
* “It’ll be impossible to open source software which we have developed in collaboration with companies / industry because it will be too complicated to resolve the legal issues”  
  *You could consult an IP specialist such as OSS-Watch  
  *Using an OSI-approved license will make it easier as commercial IP legal departments recognise them  
*“Getting my code ready to open source will take a lot of time and effort”  
  * The expected time benefits often outweigh the initial investment (See: Taverna move to Apache incubator process)  
  * It will help your internal development team  
  * Enhances skills and CV  
* “An open source license will put off life sciences companies”  
  *Many life sciences companies use open source software - they care about functionality and support. Examples: TBD  
* “I’ll have to support users” / “I’ll have to support users who are not in my field”  
  * it’ll foster collaboration and reputation in related fields, which can lead to new scientific collaborations and funding  
  * Research funders want to see impact outside of your specific field  
* “I will be liable if something bad happens when someone uses my software”  
  *A good OSI-approved license will disclaim/waive liability better than having no license or an untested academic license  
* “I should be doing science, not open-sourcing software”  
  *Science is fundamentally based on accuracy and trust in results. Open source code can be more trusted (cf security community) than black box solutions (see Shining light into black boxes paper)  
* “I won’t receive any credit for my work”  
  *Open-sourcing has been shown to improve citation and research impact in certain communities (reference needed)  
* “People will scoop me”  
  * Open-sourcing will tend to lead to more collaborations (leading to more publications) than other people scooping you (reference needed)  
* “I won’t be able to publish a paper about my research / about my software”  
  * There are now many avenues for publishing software papers, and many encourage open source licenses (examples needed)  
* “I’ll have to pay for the cost of infrastructure”  
  *There are many providers who allow you to use their resources for free if you are an open source project (examples)  
