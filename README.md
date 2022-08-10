# learning-hub-content
learning-hub-content repo manages .yaml files for Learning Hub section. 
We have created external github repo to allow dynamic update of contents regardless of CML releases.

There are four .yaml files
1. blogposts.yaml
2. documentation.yaml
3. feature.yaml
4. research.yaml

Each .yaml file follows the same format:

  -title: Representation Learning 101 for Software Engineers  
   description:
    " Good representations of data (e.g., text, images) are critical for
    solving many tasks (e.g., search or recommendations). Deep representation learning
    yields state of the art results when used to create these representations. In
    this article, we review methods for representation learning and walk through an
    example using pretrained models."  
   category: Blogpost  
   tags:  
     - cml   
     - ffl   
     - ml   
   link: https://blog.fastforwardlabs.com/2020/11/15/representation-learning-101-for-software-engineers.html     
   imgpath: https://blog.fastforwardlabs.com/images/hugo/representationlearning.png  
   date: "2020-11-15T00:00:00Z" 

Github Actions validates the format of .yaml files everytime repo is pushed.
