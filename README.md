<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="assignment.css" />
</head>
<body>
    <div class="title-container">
        <h2 class="ubuntu-font">Admission Form For Geekster</h2>
    </div>
    <div class="form-container">
        <form>
            <h4 class="roboto-font">Personal Info</h4>
            <input type="text" class="inline m-4" name="f_name" placeholder="First Name" autocomplete="off" required/>
            <input type="text" class="inline m-4" name="l_name" placeholder="Last Name" autocomplete="off"/>
            <br />
            <input type="email" class="inline m-4" name="mail" placeholder="Email ID" autocomplete="off" required/>
            <br />
            <input type="tel" class="inline m-4" name="phone" placeholder="Phone Number" autocomplete="off" required pattern="[0-9]{4}-[0-9]{3}-[0-9]{3}" title="Please enter in the format 1111-111-111"/>
            <br />
            <input class="inline m-4" type="date" name="date_of_birth" max="2022-01-01" />
            <br />
            <select class="inline m-4" name="gender">
                <option selected disabled>Select Gender</option>
                <option>Male</option>
                <option>Female</option>
                <option>Other</option>
            </select>
            <br />
            <textarea name="address" placeholder="Address" class="m-4"></textarea>
            <hr />
            <h4 class="roboto-font">Education Info</h4>
            <select name="degree" class="inline m-4">
                <option selected disabled>Select Degree</option>
                <optgroup label="Bachelors">
                    <option>B. Tech</option>
                    <option>B.E.</option>
                    <option>B. Sc.</option>
                </optgroup>
                <optgroup label="Masters">
                    <option>M. Tech</option>
                    <option>M.E.</option>
                    <option>M. Sc.</option>
                </optgroup>
            </select>
            <br />
            <input type="text" name="college" class="inline m-4" placeholder="College Name" />
            <br />
            <input type="text" name="graduation_year" class="inline m-4" placeholder="Year of graduation" min="2010" max="2022" />
            <br />
            <input type="text" name="percentage" class="inline m-4" placeholder="Percentage" min="0" max="100" step="0.1" />
            <br />
            <h4 class="roboto-font">class X Details</h4>
            <input type="text" name="classX_BOARD" class="inline m-4" placeholder="School Name" />
            <br />
            <input type="text" name="classXPassout_year" class="inline m-4" placeholder="Year of Passout" min="2010" max="2018" />
            <br />
            <input type="text" name="percentage" class="inline m-4" placeholder="Percentage" min="0" max="100" step="0.1" />
            <br />
            <h4 class="roboto-font">class XII Details</h4>
            <input type="text" name="classXII_BOARD" class="inline m-4" placeholder="School Name" />
            <br />
            <input type="text" name="classXIIPassout_year" class="inline m-4" placeholder="Year of Passout" min="2010" max="2018" />
            <br />
            <input type="text" name="percentage" class="inline m-4" placeholder="Percentage" min="0" max="100" step="0.1" />
            <br />




            <h5 class="inline roboto-font">Upload Resume: </h5>
            <input type="file" class="inline m-4" />
            <hr />
            <h4 class="roboto-font">Course Details</h4>
            <p class="roboto-font">Which level do you want to enroll?</p>
            <input type="radio" class="m-4" name="course_type" /><span class="roboto-font">Fundamentals</span>
            &emsp;&emsp;
            <input type="radio" class="m-4" name="course_type" /><span class="roboto-font">Advanced</span>
            <br />
            <br />
            <p class="roboto-font">Which course do you want to enroll?</p>
            <input type="checkbox" class="m-4" name="course_name" /><span class="roboto-font">Web</span>
            &emsp;&emsp;
            <input type="checkbox" class="m-4" name="course_name" /><span class="roboto-font">DSA</span>
            <hr />
            <input type="submit" value="Apply for Admission" />
            <input type="reset" />
        </form>
    </div>
</body>
  <style>
    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="assignment.css" />
</head>
<body>
    <div class="title-container">
        <h2 class="ubuntu-font">Admission Form For Geekster</h2>
    </div>
    <div class="form-container">
        <form>
            <h4 class="roboto-font">Personal Info</h4>
            <input type="text" class="inline m-4" name="f_name" placeholder="First Name" autocomplete="off" required/>
            <input type="text" class="inline m-4" name="l_name" placeholder="Last Name" autocomplete="off"/>
            <br />
            <input type="email" class="inline m-4" name="mail" placeholder="Email ID" autocomplete="off" required/>
            <br />
            <input type="tel" class="inline m-4" name="phone" placeholder="Phone Number" autocomplete="off" required pattern="[0-9]{4}-[0-9]{3}-[0-9]{3}" title="Please enter in the format 1111-111-111"/>
            <br />
            <input class="inline m-4" type="date" name="date_of_birth" max="2022-01-01" />
            <br />
            <select class="inline m-4" name="gender">
                <option selected disabled>Select Gender</option>
                <option>Male</option>
                <option>Female</option>
                <option>Other</option>
            </select>
            <br />
            <textarea name="address" placeholder="Address" class="m-4"></textarea>
            <hr />
            <h4 class="roboto-font">Education Info</h4>
            <select name="degree" class="inline m-4">
                <option selected disabled>Select Degree</option>
                <optgroup label="Bachelors">
                    <option>B. Tech</option>
                    <option>B.E.</option>
                    <option>B. Sc.</option>
                </optgroup>
                <optgroup label="Masters">
                    <option>M. Tech</option>
                    <option>M.E.</option>
                    <option>M. Sc.</option>
                </optgroup>
            </select>
            <br />
            <input type="text" name="college" class="inline m-4" placeholder="College Name" />
            <br />
            <input type="text" name="graduation_year" class="inline m-4" placeholder="Year of graduation" min="2010" max="2022" />
            <br />
            <input type="text" name="percentage" class="inline m-4" placeholder="Percentage" min="0" max="100" step="0.1" />
            <br />
            <h4 class="roboto-font">class X Details</h4>
            <input type="text" name="classX_BOARD" class="inline m-4" placeholder="School Name" />
            <br />
            <input type="text" name="classXPassout_year" class="inline m-4" placeholder="Year of Passout" min="2010" max="2018" />
            <br />
            <input type="text" name="percentage" class="inline m-4" placeholder="Percentage" min="0" max="100" step="0.1" />
            <br />
            <h4 class="roboto-font">class XII Details</h4>
            <input type="text" name="classXII_BOARD" class="inline m-4" placeholder="School Name" />
            <br />
            <input type="text" name="classXIIPassout_year" class="inline m-4" placeholder="Year of Passout" min="2010" max="2018" />
            <br />
            <input type="text" name="percentage" class="inline m-4" placeholder="Percentage" min="0" max="100" step="0.1" />
            <br />




            <h5 class="inline roboto-font">Upload Resume: </h5>
            <input type="file" class="inline m-4" />
            <hr />
            <h4 class="roboto-font">Course Details</h4>
            <p class="roboto-font">Which level do you want to enroll?</p>
            <input type="radio" class="m-4" name="course_type" /><span class="roboto-font">Fundamentals</span>
            &emsp;&emsp;
            <input type="radio" class="m-4" name="course_type" /><span class="roboto-font">Advanced</span>
            <br />
            <br />
            <p class="roboto-font">Which course do you want to enroll?</p>
            <input type="checkbox" class="m-4" name="course_name" /><span class="roboto-font">Web</span>
            &emsp;&emsp;
            <input type="checkbox" class="m-4" name="course_name" /><span class="roboto-font">DSA</span>
            <hr />
            <input type="submit" value="Apply for Admission" />
            <input type="reset" />
        </form>
    </div>
</body>
</html>
  
  
