# learning-hub-content
learning-hub-content repo manages .yaml files for Learning Hub section. 
We have created external github repo to allow dynamic update of contents regardless of CML releases.

There are four .yaml files
1. blogposts.yaml
2. documentation.yaml
3. feature.yaml
4. research.yaml

Each .yaml file follows the same format:

title
description
category
tags
link
imgpath
date

Github Actions validates the format of .yaml files everytime repo is pushed.
