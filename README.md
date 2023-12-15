# Survey_Form_Javascript_Ajax_jQuery_jQueryUI

This is an project i did for my university.

## Project Overview

This assignment extends the tudent_CS_Department_Webpage from the previous repository project, incorporating JavaScript functionality. The enhancements include the use of cookies for personalized greetings, the addition of a Data field for average and maximum computation, form validation using jQuery UI modal windows, and Ajax/JSON integration for populating City and State fields based on the entered Zipcode.

## Assignment Details

### 1. Cookie and Greetings Implementation

- Utilize a cookie to store user information.
- Display a greeting with the user's name based on the time of the day.
- Allow users to update their name through a hyperlink if different from the stored cookie.
- Set an expiration time for the cookie.

### 2. Survey Form Extension and Average & Maximum Computation

- Add a "Data" text box and output fields for Average and Maximum on the Student Survey Form.
- User must enter ten comma-separated numbers between 1 and 100.
- JavaScript functions calculate Average and Maximum automatically.
- Display an error message if the entered values are not valid.

### 3. Form Validation Event Handling

- Develop an onclick event handler for the submit button.
- Validate:
  - Name should contain only alphabets.
  - Address fields should contain appropriate characters.
  - At least two checkboxes must be checked.
  - A radio button option must be selected.
  - Validate email address format.
- Display error messages using jQuery UI modal windows.
- Only clear fields with errors upon alert, not all fields.
- Include a Reset button that clears the form contents.

### 4. Ajax, JSON, jQuery

- Implement Ajax and JSON to auto-populate City and State based on entered Zipcode.
- Capture personal information: Name, Address, Telephone Number, and Email.
- Use a placeholder for City and State.
- Display "invalid zip" message if the entered Zipcode is not valid.
- Implement an event handler for the "onblur" event associated with the Zipcode element.
- Make an Ajax call to the server to get a list of valid Zipcodes and corresponding City and State from a JSON file.
- Populate City and State fields based on the entered Zipcode.

### 5. Additional Requirements

- Add a link on the homepage that leads to a simplified version of https://volgenau.gmu.edu/ using jQuery UI tabs.
- Demonstrate the use of jQuery UI tabs by swapping content when clicking on tabs.
- Include the CSS file that comes with the jQuery UI download in addition to your application's CSS file.

## Hosting

Hosted on gmu servers asscesible by a link . Post the link on your [class home page](http://mason.gmu.edu/~your_username/). (Not working anymore since access revoked).

