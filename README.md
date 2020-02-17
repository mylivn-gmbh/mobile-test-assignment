# Test assignment

### About

This coding challenge should help Mylivn to evaluate your coding and problem-solving skills.

### Summary

Create an iOS App to display a feed similar to the feed we have in our current Mylivn application.

The feed is the entry point of our application where we operate data from plenty of channels and display them in a beautiful UI to the users.
 
According to our application, users will see the feed immediately after logging in, so we want to impress them with a relevant, beautiful and high-performing feed feature.

### High-level requirements:

1. Fetch the data from the REST API: developer.marvel.com.
2. The top component of feed should have horizontal scroll direction and support loading page by page. This component should show Marvel heroes with their names and images. Tapping on hero should load proper information in the bottom component.
3. The bottom component of the feed should have vertical scroll direction and support loading page by page. This component should show all comics where this hero has participated.
4. For visual inspiration, you can refer to our Mylivn application.

### Details:

1. Load data only once a day and store it for offline use. Use Codable to encode/decode the data.
2. If data can't be loaded but offline data is available from a previous day, use that cached data.
3. UI should look nice for any device.
4. No iPad support needed.
5. You can choose the architecture which you familiar with.
6. The app should be production-ready. It means that UI should be polished and performance should be optimized.
7. The app must have good unit-test coverage.

### Technical restrictions: 

No 3rd party libraries are allowed - you should do it by yourself. However, if you want to use some frameworks for Unit-testing, dependency injection or reactive programming - it’s up to you.

### Quality

The purpose of this test assignment is to check applicant's real-world skills in developing mobile applications. When we review applicant's solution, we expect to see production ready code, which does not break in any real-world scenario (handles all important corner cases). Ability to predict corner cases for the problem an applicant solves is one of the most important engineering skills that we check. Unfortunately, it is not always possible to approximate skills of an applicant based on incomplete or crashing application.

### Submission

After you finished your test assignment, please send us a link to download it to hr@mylivn.com. Please do not put your solution to any publicly available place on the internet (like GitHub, BitBucket). Best way to share files with us is to put them to any private cloud storage and provide us a private link.
Also please provide a short description containing:
* How to build and run your application
* Short description of your solution
* Assumptions you made while planning and structuring your solution
