#Dynanimator
An animation package for the Dynamo visual programming environment, developed as part of the [Dynamo Hackathon](https://www.hackerleague.org/hackathons/autodesk-university-2014-dynamo-hackathon) at [Autodesk University 2014](http://au.autodesk.com).

![Sample Animation](sample_animations/Phases And Camera Position With Fixed Target.gif)

##Samples
Follow the links below to see some animations created using Dynanimator:
- [Sample animations for all Dynanimator nodes](https://github.com/BadMonkeysInc/Dynanimator/wiki/Sample-Animations)
- [Animate design iterations in Revit with Dynamo](http://vasshaug.net/2014/12/18/animate-design-iterations-in-revit-with-dynamo/) (First post about Dynanimator after AU2014 by Håvard Vasshaug)
- [Dynanimator released: Animating Data Changes in Revit with Dynamo](http://vasshaug.net/2015/04/22/dynanimator-released-animating-data-changes-in-revit-with-dynamo/) (Package release announcement by Håvard Vasshaug
- [Dynam(o)ite Your Design goes … D-I-S-C-O](https://revitbeyondbim.wordpress.com/2015/05/05/dynamoite-your-design-goes-d-i-s-c-o/) (User animation of parameter values by Dieter Vermeulen)
- [Dynam(o)ite Your Design with Dynanimator](https://revitbeyondbim.wordpress.com/2015/05/07/dynamoite-your-design-with-dynanimator/) (User animation of camera path by Dieter Vermeulen)

##Project Goals
This package was developed for animating several aspects of a Revit model:
- **Element parameters**
- **Element transparency**
- **Element surface color**
- **Camera (and target) position of perspective views**
- **Phases**
- [Displacement sets [under review]](https://github.com/BadMonkeysInc/Dynanimator/issues/3)
- [Sun position [planned]](https://github.com/BadMonkeysInc/Dynanimator/issues/17)
- [Design Options [planned]](https://github.com/BadMonkeysInc/Dynanimator/issues/14)
- [Family parameters [planned]](https://github.com/BadMonkeysInc/Dynanimator/issues/18)
- **Combinations of the above** [[partially done](https://github.com/BadMonkeysInc/Dynanimator/wiki/Sample-Animations#combine-multiple-techniques)] - Post wishes for other combinations [here](https://github.com/BadMonkeysInc/Dynanimator/issues/4)
- ...

The results could be exported in a number of formats:
- **Images**
- [Revit models [planned]](https://github.com/BadMonkeysInc/Dynanimator/issues/13)
- [SAT files [planned]](https://github.com/BadMonkeysInc/Dynanimator/issues/12)
- ...

We are also thinking about connecting Dynanimator with other functionalities like cloud rendering etc.
 
##Installation
This package is available through Dynamo's package manager, so installation is quite simple - just use Dynamo's built-in package manager and search for ```Dynanimator```.
Please note that this package has dependencies - currently, during installation it will also install the [Clockwork](https://github.com/CAAD-RWTH/ClockworkForDynamo) package. There may be more dependencies in the future.

##Collaborate
If you want to animate other parts of a Revit model using Dynamo, please contact us - either by [creating a feature request](https://github.com/BadMonkeysInc/Dynanimator/issues) or (better yet) by [forking this repository](https://help.github.com/articles/fork-a-repo/) and adding your code via [pull request](https://help.github.com/articles/using-pull-requests/). There's also a guide that explains how to build your own Dynanimator nodes on the [wiki](https://github.com/BadMonkeysInc/Dynanimator/wiki/How-To-Make-a-New-Dynanimator-Node).

##Team
###Original Project Team
- [Julien Benoit](https://github.com/jbenoit44)
- [Andreas Dieckmann](https://github.com/andydandy74)
- [Ian Siegel](https://github.com/IanSiegelKPF)
- [Håvard Vasshaug](https://github.com/vasshaug)

###Contributors
- [Fabian Ritter](https://github.com/redinkinc)
