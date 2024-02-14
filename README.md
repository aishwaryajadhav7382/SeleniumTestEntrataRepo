# SeleniumTestEntrataRepo
Coding Solution

Instructions to run the solution:

1.Double click on testng.xml file under BEGINNING folder to execute all three tests I have written in this solution.

Test Scripts walkthrough
1. First Test is to verify Sign In functionality for Property Manager. With Invalid data set this test will verify error message saying "Please enter valid Username and Password" on SignIn click.

2. Second Test is developed to Verify Schedule Demo functionality for "Resident Pay" Product. Keeping Last name field on the form  Blank and verifying the error message(This Field is required) after clicking on Schedule Demo button. Handled Unit Count dropdown using Select Class concept in this Test.
   
3. The third test is developed to Verify Careers Functionality. Test will click on Careers link on the entrata website. The flow of Search Jobs is automated applying Location and Work Type filters. The very first job is selected for Applying with required details. This test will Upload Resume file(Located under src/test/resources/resorcesfiles/AishwaryaResume.pdf) for selected job. Test is also Verifying resume upload success notification on UI.
   
-This solution is equipped with maven and testNg dependencies.
-Used POM concept to achieve abstraction. Created three page classes(PropertyManagerlogin.java, ScheduleDemoPage.java, ApplyCareerPage.java) and imported those in main test class(PositiveTest.java).
-Also Used Implicit and explict waits whenever required.
-Used Test, afterMthod, Beforemthod annotations provided by TestNG.
