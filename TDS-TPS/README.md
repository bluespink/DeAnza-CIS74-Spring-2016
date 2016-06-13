##Writing a Test Design Specification & Modified Test Procedure Specification
####Instructions from the instructor:

Write a formal **Test Design Specification** that follows the outline on pages 192-193 of your textbook:

1. **Test design specification identifier**. Use this naming scheme: *yyyymmdd-LastnameFirstname-TDS*.
2. **Features to be tested**. Provide the URL and overlay name if applicable. (For example, ResumeSmarts needs the latter, since it appears to be a Single Page App.) 
3. **Approach refinements**. You only need this if your tests would be best executed with the aid of some tool (such as BrowserStack's Screenshots for a TDS about rendering), or if they need to be executed on a specific browser or mobile device.
4. **Test identification**. This is the most important part of your TDS--a one-liner describing as succinctly as possible what each test case would test.

Once your TDS is complete, write a **Test Procedure Specification** (TPS) for just *one* of the test cases specified in your TDS. Use the slightly modified version of TPS outline given in your book on pages 193-194 to include the input and output specifications from the Test Case Specification from page 193. 

1. Test procedure specification identifier. Use this naming scheme: *yyyymmdd-LastnameFirstname-TPS-nn*, where nn is the number of the test case from your TDS which you are expanding in this TPS. 
2. Purpose. Copy/paste the test case's one-line summary from your TDS here.
3. Special requirements. Again, if your test would be best executed with the aid of some tool (such as BrowserStack's Screenshots for a TDS about rendering), or if it needs to be executed on a specific browser or mobile device, detail that here. 
4. Procedure steps. This is the meat of the TPS. Specify every step that the user must take in order to execute the test case. Include any inputs right in the steps. End with an **EXPECTED RESULTS** paragraph, just as you would do with a bug report. However, do not include an **ACTUAL RESULTS** paragraph as this is a test case, to be reused many times, not a bug report or test report of any type.

**Grading criteria for this assignment:**

- Coverage completeness of test cases
- Clarity of test case summaries in TDS
- Clarity of steps to execute in TPS
- Absence of errors!
- Adherence to formal outlines of TDS and TPS
