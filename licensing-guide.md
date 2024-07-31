# Licensing open code

We encourage publishing analytical code because it improves transparency and contributes to a wider community. 
When preparing your code, please refer to the [GDS principles on making source code open and reusable](https://www.gov.uk/service-manual/technology/making-source-code-open-and-reusable). 
[NHSX has also provided specific advice](https://healthtech.blog.gov.uk/2019/04/23/what-does-it-mean-for-nhsx-to-be-an-open-source-organisation/) on doing this in the health space. 

However, for open source code to be useful, users have to know how they can re-use and adapt it. The license specifies this. 
On Github, you can add a licence when creating a new repository, or later on by adding a LICENCE.md file. 

## Deciding your license

For DHSC work, the default license is the [OGLv3.0, as published by the national archives](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/). 
However, there may be reasons other licenses are more appropriate.
These are the steps to work out what license your code should have.

1. Make a list of all package dependencies of your code, and the licenses those packages were published under. The package's PyPi (Python) or CRAN (R) page should list this. For example, [dplyr is published under the MIT license](https://cran.r-project.org/web/packages/dplyr/index.html).
2. For each package license, check whether the licence requires publishing of new or modified code under the same licence. You should carefully read the conditions of the licences for the packages which are being depended on before publishing your code.  Please note that the licences may place more obligations on DHSC than a simple requirement to use the same licence and it’s important to check for these.       
3. Would there be a technical benefit to publishing your code under a license other than the OGLv3? We suggest looking at latest tests set out by [The National Archives](https://www.nationalarchives.gov.uk/information-management/re-using-public-sector-information/uk-government-licensing-framework/open-government-licence/open-software-licences/). For example, using a different license may help promote adoption by the software community or promote adoption to benefit UK industry and consumers. 
4. If there would be a technical benefit from publishing your code under a license other than OGLv3, you may choose an [alternative OSI approved license](https://opensource.org/licenses). You probably want to consider the MIT license. 
5. If there would be no technical benefits, you must publish your code [under OGL](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/). 

## Seeking further legal advice

This step-by-step plan is likely sufficient. However, in some cases you should go back to the department's legal team for further advice. A non-exhaustive list include:

- Where part(s) of the code has been obtained under a licence and you are unclear, having considered the terms of the licence, as to whether you will be required to publish the new / modified code under that same licence;
- Where legal advice is required in relation to the terms of any other open source licence;
- Where intellectual property advice is required.
- Where the National Archives have issued a new version of the Open Government Licence and further consideration needs to be given to whether this should be used as a default option;
- Where the licence is required to include patents, trademarks and / or design rights; or
- Where a more restrictive licence than MIT or OGL might be required.     

Moreover, whenever in doubt, please go back to get legal advice.


