# SlicerMorph Tutorials for VMM
SlicerMorph Tutorial for Virtual Morpho Meetup organized by Ian Dworking
May 6th, 2020

## What is 3D Slicer and SlicerMorph

[3D Slicer](https://www.slicer.org) is an open-source, extendible biomedical visualization suite that has been collaboratively developed for almost 20 years. It is based on robust, open-source image processing and visualization libraries like ITK and VTK. Functionality of 3D Slicer can be expanded by developing custom modules with C++, or importing existing Python3 libraries and building onto them. 

SlicerMorph is an extension of 3D Slicer. It can be installed either using the Extension Manager mechanism of 3D Slicer (e.g., first install a [4.11 preview version of 3D Slicer](https://download.slicer.org), and then install SlicerMorph extension) or by downloading a pre-customized SlicerMorph application from [http://download.slicermorph.org for Mac or Windows PCs](http://download.slicermorph.org).

The only difference between the extension version and the customized SlicerMorph package is auto3Dgm. As of March 4/27/2020, auto3Dgm is only available through the custom SlicerMorph application, which we will soon become separate extension of 3D Slicer. Another benefit of custom SlicerMorph applications is that it is portable (ie., you can run it from a USB stick).

[This link summarizes some of the key capabilities of 3D Slicer and SlicerMorph relevant to 3D morphometrics](https://docs.google.com/document/d/1VdsYQzhjEh9tT5WQQjb1GUdn5Hmnq8cK3yLzjYeVv5M/edit)

## What SlicerMorph is not?
SlicerMorph is designed to help you with all the steps associated with working 3D morphology data: Importing data, visualizing, segmenting, measuring and analyzing. However, it is not a replacement for statistical shape analysis packages like R/geomorph or Morpho. In fact, it is our expectation that once you generate and vet your data, you will use one of those packages to do your domain specific statistical analysis. We are working on approaches that will help you transition easily between working with SlicerMorph and R packages. 
