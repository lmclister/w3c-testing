Perceived Problem Areas for people new W3C test development and Possible Solutions 
-------------

**Note:** _Many of the possible solutions below would benefit testing efforts in general, not just newcomers._

***
### Getting set up to contribute ####
***
##### Difficulties #####

1. Most newcomers don't have Mercurial set up and configured.  It is difficult and time consuming to set up so it is a barrier to entry.

2. If you have never used Mercurial, it is confusing. "What is the HG equivalent of git fetch?" was a frequent question at TestTWF SF.

3. WGs have different test repo locations, different rules for gaining access (specifiaclly write access) to source control (I beleive some require you to be a WG member) and it can take some time to get access to a repo.

4. In addition to Mecurial access, one must create a W3C account & sign the license agreement.

##### Possible Solutions ######

1. For test source control, consider using a system that has little to no barrier to entry for new comers.  This could possibly be a popular source control system like git or maybe it is some sort of web app that makes the process dead simple to contribute and track tests and test status.  Maybe some combination of both.

2. Standardize test repo locations and/or document repo locations, owners & access policies in one central place that people can easily locate that information.

3. Provide information for newcomers on how to get set up.  Presentation, articles, videos, etc.  Put it in a central location.
4. Move tests repos to GitHub ([as the HTML WG has done](https://twitter.com/robinberjon/status/281751093220896768?uid=482516382&iid))

***
### Understanding specs ###
***
##### Difficulties #####

1. Specs are hard to read / digest for newcomers and in order to make worthwhile tests, you need to understand the spec.

2. Not really any documentation on W3C and/or web docs sites about how to read a spec.

3. Normative language must be learned.  Also, not all specs / WGs use normative language.

##### Possible Solutions ######

1. In a central place, provide information for newcomers on how to read and digest specs.  Presentation, articles, videos, etc.

2. Provide information on normative language as part of the above mentioned content. (probably goes w/o saying)

3. ?

***
### Getting started with test development ###
***
##### Difficulties #####

1. It is unclear where & how one can get started. 

2. Not m(any) sample tests.

3. No clear indication of what tests have been written or need to be written for a particular spec.

4. Not always clear on where to go for help.
        
##### Possible Solutions ######

1. In a central place, have a detailed description of how the tests/test harnesses work and provide walkthroughs for creating various types of tests.  

2. Provide an easy to find list of specs/WGs that need/want help developing tests.  Each spec in the list would have assigned test development contacts/leads.

3. Provide sample tests per spec and have them in the test repo.

4. <a href="gs1"></a>For all specs, add test widgets, per a section[[1]](http://dev.w3.org/csswg/css3-transforms/) that indicate which tests have been written and which tests are passing/failing per platform. 

5. <a href="gs2"></a>Spec editors / test contributors outline what tests need to be written for each spec section.  The list is then somehow mapped to the test repo and the spec widgets (see above) are updated so that they reflect what tests need to be written, what tests have been written and if the list of required tests is incomplete, complete or not defined.

6. Move to test driven spec development.

7. Get experts in an irc.w3c.org channel, hangout or otherwise and centrally document how to use it so that newcomers and experienced testers can ask questions.

8. Hold virtual [Test the Web Forward](http://www.testthewebforward.org) events to onboard new test developers.

***
### Getting tests submitted & approved and related to specs ###
***
##### Difficulties #####

1. Not always clear where to submit
2. OK, so now that I submitted my test(s), when will it be approved?
3. Need a more efficient way to track the review process.
3. Only the CSS WG has a test tracking system (AFAIK)
4. There are any clearly documented guidelines/requirements for reviewing a test.
5. It is unclear how one becomes a reviewer.
6. Specs do not contain references to or results of tests.
7. I only have one UA and my test was not approved because it is not suitable for a UA that is not available to me.

##### Possible Solutions ######

1. Document WG repo info and contacts (as mentioned above)
2. Create or buy a central test suite/case managment system or scale/reuse sheperd[[3]](http://test.csswg.org/shepherd/) so that tests can easily be tracked.
3. Use issue tracking in git, code collaborator or something else to do/track reviews rather than email.
4. Centrally document requirements and guidelinse for tests (part of the 'getting started' docs above), so reviewers are more efficient.
5. In one place, have WGs publish requirements for being a reviewer.
6. Embed test info into spec sections (see [4](#gs1) & [5](#gs2) above).
7. Hold (virtual) [Test the Web Forward](http://www.testthewebforward.org) events that focus on getting tests reviewed for specific specs.
8. Leverage open device labs to broaden coverage [http://lab-up.org/](http://lab-up.org/).

***
### References ###
***
- [1] <a id="ref1"></a>[http://dev.w3.org/csswg/css3-transforms/](http://dev.w3.org/csswg/css3-transforms/)
- [2] <a id="ref2"></a>[http://lab-up.org/](http://lab-up.org/)
- [3] <a href="ref3"></a>[http://test.csswg.org/shepherd/](http://test.csswg.org/shepherd/)
