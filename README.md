<!DOCTYPE html>

<html>

<head>

<style>
body{
background-color:pink;
}
div{

width:700px;

margin:0 auto;

padding:20px;

background-color: darkgrey; border-radius:10px;

border:20px blue;

}
table{
 border-spacing:10px;
 } 
<title>EMPLOYMENT REGISTRATION FORM</title>

</style>

</head>

<body>

<hr>

<center>

<h1>EMPLOYMENT REGISTRATION FORM</h1>

<div>

<form>

<table>

<tr>

<td><label for="cname">Candidate name </label></td>

<td><input type="text" id="cname" placeholder="Name of Candidate" size="30px"required></td>

</tr>

<tr>

<td><label for="mail ID"> Email ID </label></td>

<td><input type="email id" id="Email ID" placeholder="Enter your mail ID"size="30px"required></td> </tr>

<tr>

<td><label for="DOB">DOB </label></td>

<td><input type="date" id="DOB" placeholder="Enter your Date of Birth "size="30px" required></td>

</tr>

<tr>

<td><label for="DOJ ">DOJ </label></td>

<td><input type="date" id="DOJ" placeholder="Enter your Date Of Joining "size="30px" required></td>

</tr>

<tr>

<td><label for ="Address">Address </label></td> <td><textarea cols="20" rows="3" id="Address"> </textarea></td>

</tr>

<tr>

<td><label for="gender">Gender</label></td>

<td><input type="radio" Name="gender"> Male

 <input type="radio" Name="gender">Female </td>

</tr>

<tr>

<td><label>Education qualification</label></td> 
<td><select>
 <option>Course</option>

<option>BCA</option>

<option>BBA</option>

<option>B. Tech</option>

<option>MBA</option> <option>MCA</option>

<option>M.Tech</option>

</select>

</td>

</tr>

<tr>

<td><label>Experience</label> </td>

<td><select>

<option>0</option>

<option>1</option>

<option>2</option>

<option>3</option>

<option>4</option>

<option>5</option>

<option>6</option>

</select>

</td>

</tr>

<tr>

<td><label for="phone">Phone number</label></td>

<td><input type="tel" id="phone" value="+91" size="10" required></td>
</tr>

<tr>

<td><lable for "skills">Skillsets</label></td>

<td><input type="checkbox" id="skills">ARTIFICIAL INTELLIGENCE<br>

<input type="checkbox" id="skills">MACHINE LEARNING<br>
 <input type="checkbox" id="skills">CYBER SECURITY</td>

</tr>

<tr>

<td><label for="my file">Upload your Resume</label> </td> <td><input type="file" id="my file"></td>

</tr>

</table>

<center>

<input type="SUBMIT" value="SUBMIT">

<input type="RESET" value="RESET">

</center>

</form>

</div>

</center>

</body>

</html>
