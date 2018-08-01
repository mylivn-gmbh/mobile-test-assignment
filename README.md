# Test assignment

### Summary

You need to implement an image loading library for user avatars. Implement as many of these requirements as you can given the time you allow yourself to have. 

### Minimum requirements:
Your avatar loading class should provide an interface for load image by URL string. It should be supported by an optional placeholder, showing it during the loading process. The loading progress should be shown in the form of a colored border around the image.
You should also make a simple screen with a demonstration of this work. The demonstration should show an avatar image and button to load the next image from the network.

### Optional requirements (you can choose any of them):
- Add image caching library: It should save loaded images on the phone’s hard drive and support 2 parameters: maximum number of objects in the cache and maximum disk storage space. 
- Support a 2-color gradient for the image’s progress bar. 
- After loading, an image should be cropped in a circle shape and resized to the size of the current image on the screen.

### Technical restrictions: 
No 3rd party libraries for performing these operations with images are allowed - you should do it by yourself. However, if you want to use some frameworks for dependency injection or reactive programming - it’s up to you.

### Quality
The purpose of this test assignment is to check applicant's real-world skills in developing mobile applications. When we review applicant's solution, we expect to see production ready code, which does not break in any real-world scenario (handles all important corner cases). Ability to predict corner cases for the problem an applicant solves is one of the most important engineering skills that we check. Unfortunately, it is not always possible to approximate skills of an applicant based on incomplete or crashing application.

### Visual example:
![](https://raw.githubusercontent.com/mylivn-gmbh/mobile-test-assignment/master/assets/cat.gif)
