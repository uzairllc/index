# index <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form action="#" method="post">
        <h2>Registation Form</h2>
        <input type="text" name="userName" placeholder="Enter Your Name" required />
        <br />
        <br />
        <input type="month" name="email" placeholder="Enter Your Email" required />
        <br />
        <br />
        <input type="password" name="password" placeholder="Enter Your Password" required />
        <br />
        <br />
        <textarea name="message" required placeholder="Enter Your Message"></textarea>
        <br />
        <h5>Gender</h5>
        <input type="radio" name="gender" checked /> Male
        <input type="radio" name="gender" disabled /> Female
        <br />
        
        <h5>Languages</h5>
        <input type="checkbox"  name="language"  /> Urdu
        <input type="checkbox" name="language" draggable="true" checked /> English
        <select name="course" >
            <option value=""></option>
            <option selected value="Web Designing">Web Designing</option>
            <option value="Web Development">Web Development</option>
            <option value="Application Development">Application Development</option>
        </select>
        <br />
        <br />
        <input type="file" multiple />
        <br />
        <br />
        <button draggable="true" type="submit">Submit</button>
    </form>
</body>
</html>
