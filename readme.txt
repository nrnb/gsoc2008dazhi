Before you build, please drop the CDK jar file into the lib directory, and check out cytoscape source code and put them into this path: ../../../../cytoscape (relative to where this file is). If you want to put it in a different place, please edit build.xml accordingly.

You can check out the cytoscape source code from 
> svn co svn+ssh://grenache.ucsd.edu/cellar/common/svn/cytoscape/trunk cytoscape

CDK can be downloaded from http://cdk.sourceforge.net

To build, please run 
> ant jar

To test it with the test file, please run
> ant run

Please email dazhi.jiao@gmail.com if you have any questions.



