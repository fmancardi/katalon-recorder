# katalon-recorder
first steps, lesson learned and tricks trying to do test recording

# Dealing with Select2
All tests I've done during May 2018, provides me no answer regarding
how to be able to record tests when the web page under test uses
select2 (https://select2.org/) instead of the standard select.  
I was not able to find a solutions no matter how many searches I've tried in google.  
Then I switch my searches to understand how to drive the select2, 
and eureka! the solution (may be the obvious one) was found:

(https://ghostinspector.com/docs/common-testing-scenarios/#select2)

Then my choice was to use the JavaScript API.

folder select2-poc contains a simple HTML page to display a select2 and the test suite that can be runned using katalon recorder.
Surelly there are better ways to write the code, but this one works and can be used as an starting point.

## Useful links
(https://ghostinspector.com/docs/common-testing-scenarios/#select2)

(https://stackoverflow.com/questions/3744289/how-to-select-an-option-by-its-text)


