# index.html<!DOCTYPE html>
<html lang="en" >
    <head>
        <meta charset="UTF-8">
        <meta name="viewport"
        content="width=device-width,initial-scale=1.0">
       <title>HTML Form</title>  
    </head>
    <body>
     <h2>
        User Regisration Form
     </h2>
     <h3>Personal Information</h3>
     <form action="submit_form.php"method="post">
        <label for="fname">First Name:</label>
        <input type="fname" id="fname" name="fname">
        <form action="submit_form.php"method="post"><br><label for="lname"><br>Last Name:</label>
        <input type="lname" id="lname" name="lname"></form>
        <br><label for="Date of Birth" id="Date of Birth"><br>Date of Birth:</label>
        <input type="date" id="Date of Birth" name="Date of Birth">
        <br><label for="age" id="age"><br>Age:</label>
        <input type="text" id="age" age="age">
        <h5>Gender:</h5>
        <input type="radio" id="Male" name="Gender" value="Male">
        <label for="Male">Male</label>
        <input type="radio" id="Female" name="Gender" value="Female">
        <label for="Female">Female</label>
        <br><label for="Profile photo" id="Profile photo"><br>Profile photo:</label>
        <input type="file" id="profile photo " name="Profile photo">
        <h3>Contact & Address Information</h3>
        <Label for="Email Address" id="Email Address">Email Address:</Label>
        <input type="email" id="email" name="email">
        <br><label for="Phone Number" id="Phone Number"><br>Phone Number:</label>
        <input type="number" id="number" name="Number">
        <br><label for="Personal Website" id="Personal Website"><br>Personal Website:</label>
        <input type="text" id="Personal Website" name="Personal Website">
        <br><label for="Street Address" id="Street Address"><br>Street Address:</label>
        <input type="text" id="Street Address" name="Street Address">
        <br><label for="city" id="city"><br>City:</label>
        <input type="text" id="City" name="City">
        <br><label for="Country:" id="Country"><br>Country:</label>
        <input type="text" id="Country" name="Country">
        <br><label for="Zip/Postal Code" id="Zip/Postal Code"><br>Zip/Postal Code</label>
        <input type="number" id="Zip/Postal Code" name="Zip/Postal Code">
    <br><label for="Preffered Contact time"><br>Preffered Contact time:</label>
    <input type="time" id="Preffered Contact time" name="Preffered Contact time">
    <h3>Preference & Interests</h3>
    <label for="Favorite color" id="Favorite color">Favorite Color:</label>
    <input type="color" id="Favorite color" name="Favorite Color">
    <br><label for="Experience level" id="Experience level"><br>Experience Level (1-10)</label>
    <input type="range" id="Experience Level" name="Experience Level">
    <br><label for="Birth Month" id="Birth Month"><br>Birth Month</label>
    <input type="month" id="Birth Month" name="Birth Month">
    <br><label for="Avaialable Week" id="Avaialable Week"><br>Avaialable Week</label>
    <input type="week" id="Avaialable week" name="Avaialable Week">
    <br><label for="Search Keywords" id="Search Keywords"><br>Search Keywords</label>
    <input type="search" id="Search Keywords" name="Search Keywords">
    <h4>Interests (Select all that apply):</h4>
    <br><label for="Technology" id="Technology">Technology</label>
    <input type="checkbox" id="Technology" name="Interests" value="Technology">
    <br><label for="sports" id="sports"><br>Sports</label>
    <input type="checkbox" id="sports" name="sports">
    <br><label for="music" id="music"><br>music</label>
    <input type="radio" id="music" name="music">
    <br><label for="Travel" id="Travel"><br>Travel</label>
    <input type="checkbox" id="Travel" name="Travel">
    <br><label for="Reading" id="Reading"><br>Reading</label>
    <input type="checkbox" id="Reading" name="Reading">
    <br><label for="cooking" id="cooking"><br>Cooking</label>
    <input type="checkbox" id="Cooking" name="cooking">
    <br><label for="Education Level" id="Education Level"><br>Education Level:</label>
    <input type="checkbox" id="Education Level" name="Education Level">
    <br><label for="Create Password" id="Create Password"><br>Create Password:</label>
    <input type="text" id="Create Password" name="Create Password">
    <br><label for="Confirm Password" id="Confirm Password"><br>Confirm Password:</label>
    <input type="text" id="Confirm Password" name="Confirm Password">
    <h5>Feedback & Additional Information</h5>
    <br><label for="tell us about yourself" id="tell us about yourself"><br>Tell us about yourself</label>
    <input type="text" id="tell us about yourself" name="tell us about yourself">
    <br><label for="suggestion for improvement" id="suggestion for improvement"><br>Suggestion For Improvement</label>
    <input type="text" id="Suggestion for Improvement" name="Suggestion for Improvement">
    <br><label for="Regisration Date & time" id="Regisration Date & time"><br>Registration Date & Time</label>
    <input type="date" id="Regisration date & time" name="Regisration date & time">
    <br><label for="how did you hear about us?" id="How did you hear about us?"><br>How did you hear about us?</label>
    <input type="source" id="how did you hear about us?" name="How did you hear about us?">
    <br><label for="Upload Resume (optional):" id="Upload Resume (optional)"><br>Upload Resume (optional):</label>
    <input type="file" id="Upload Resume (optional)" name="Upload Resume (optional)">
    <br><label for="subscribe to our newsletter" id="subscribe to our newsletter"><br>Subscribe to our newsletter</label>
    <input type="checkbox" id="subscribe to our newsletter" name="Subscribe to our newsletter">
    <br><label for="i agree to the term and conditions" id="i agree to the term and conditions"><br>I Agree to the term and conditions</label>
    <input type="checkbox" id="I agree to the term and conditions" name="I agree to the term and conditions">
    <br><label for="I agree to the privacy policy" id="I agree to the privacy policy"><br>I agree to the privacy policy</label>
    <input type="checkbox" id="I agree to the privacy policy" name="I agree to the privacy policy">
    <br><button type="button" onclick="alert('hello world!')"><br>Register</button>
    <button type="button" onclick="alert('hello world!')">Clear form</button>
     </form>
    </body>
</html>
