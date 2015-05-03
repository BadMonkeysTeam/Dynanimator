#Dynanimator
An animation package for the Dynamo visual programming environment, developed as part of the [Dynamo Hackathon](https://www.hackerleague.org/hackathons/autodesk-university-2014-dynamo-hackathon) at [Autodesk University 2014](http://au.autodesk.com). Find more information and some nice animations in [this blog post](http://vasshaug.net/2014/12/18/animate-design-iterations-in-revit-with-dynamo/) by [Håvard Vasshaug](https://github.com/vasshaug).

﻿![Image](samples/rac_basic_sample_project/From%20Yard.gif)

##Project Goals
This package was developed for animating several aspects of a Revit model:
- Element parameters [done]
- Element transparency [done]
- Element surface color [done]
- Camera (and target) position of perspective views [done]
- Sun position [planned]
- Displacement sets [under review]
- Phases [done, but unpublished]
- Combinations of the above [partially done]
- Design Options [planned]
- ...
 
##Installation
This package is available through Dynamo's package manager, so installation is quite simple - just use Dynamo's built-in package manager and search for ```Dynanimator```.
Please note that this package has dependencies - currently, during installation it will also install the package [Clockwork](https://github.com/CAAD-RWTH/ClockworkForDynamo). There may be more dependencies in the future.

##Collaborate
If you want to animate other parts of a Revit model using Dynamo, please contact us - either by [creating a feature request](https://github.com/andydandy74/Dynanimator/issues) or (better yet) by [forking this repository](https://help.github.com/articles/fork-a-repo/) and adding your code via [pull request](https://help.github.com/articles/using-pull-requests/). There's also a guide that explains how to build your own Dynanimator nodes on the [wiki](https://github.com/BadMonkeysInc/Dynanimator/wiki/How-To-Make-a-New-Dynanimator-Node).

##Original Project Team
- [Julien Benoit](https://github.com/jbenoit44)
- [Andreas Dieckmann](https://github.com/andydandy74)
- [Ian Siegel](https://github.com/IanSiegelKPF)
- [Håvard Vasshaug](https://github.com/vasshaug)
