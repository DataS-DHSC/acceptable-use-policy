# Licensing open code

We encourage publishing analytical code because it improves transparency and contributes to a wider community. 
When preparing your code, please refer to the [GDS principles on making source code open and reusable](https://www.gov.uk/service-manual/technology/making-source-code-open-and-reusable). 
[NHSX has also provided specific advice](https://healthtech.blog.gov.uk/2019/04/23/what-does-it-mean-for-nhsx-to-be-an-open-source-organisation/) on doing this in the health space. 

However, for open source code to be useful, users have to know how they can re-use and adapt it. The license specifies this. 
On Github, you can add a license when creating a new repository, or later on by adding a LICENSE.md file. 

## Deciding your license

For DHSC work, the default license is the [OGLv3.0, as published by the national archives](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/). 
However, there may be reasons other licenses are more appropriate.
These are the steps to work out what license your code should have.

1. Make a list of all package dependencies of your code, and the licenses those packages were published under. The package's PyPi (Python) or CRAN (R) page should list this. For example, [dplyr is published under the MIT license](https://cran.r-project.org/web/packages/dplyr/index.html).
2. Check the licenses of the packages you depend on [against this list](https://choosealicense.com/appendix/). You're making sure that none of them have a tick under the 'Same license' column. If any of your dependencies are published under a license that requires 'Same license', you must publish your package under the same license as that one. For example, scripts that depend on packages published under GPL-3 (a GNU license), must also be published under GPL-3. If none of the licenses on your list are listed under the 'same license' column, you can move onto the next steps.
3. Would there be a technical benefit to publishing your code under a license other than the OGLv3? [The National Archives sets specific tests](https://www.nationalarchives.gov.uk/information-management/re-using-public-sector-information/uk-government-licensing-framework/open-government-licence/open-software-licences/) to allow you to do this. For example, using a different license may help promote adoption by the software community or promote adoption to benefit UK industry and consumers. 
4. If there would be a technical benefit from publishing your code under a license other than OGLv3, you may choose an [alternative OSI approved license](https://opensource.org/licenses). You probably want to consider the MIT license. It is the most common, least restrictive license that still provides sufficient protection to crown copyright, and [it is used by GDS for this reason](https://www.gov.uk/service-manual/technology/making-source-code-open-and-reusable#licensing-your-code).
5. If there would be no technical benefits, you must publish your code [under OGL](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/). 


