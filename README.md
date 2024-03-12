Descriptions of Tests that is done by Ayyub Mammadli
 
RetrieveSingleStudentById Test

This test verifies the functionality to retrieve a single student by their ID.
Test Steps:

    Navigate to the student's details page by providing the student ID.
    Locate the element displaying the student's name.
    Wait for the page to load.
    Ensure that the student's name is displayed on the page.

TestCourseStudent Test

This test ensures that courses are properly added to the student's course list.
Test Steps:

    Create a list of dummy courses with IDs.
    Create a student object and set the list of courses.
    Retrieve the courses associated with the student.
    Verify that the number of retrieved courses matches the expected count.
    Compare each retrieved course with the corresponding course in the original list.