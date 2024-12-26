<!DOCTYPE html> 
<html lang="en"> 
<head> 
    <meta charset="UTF-8"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
    <title>Event Registration Form</title> 
    <h1 align="center"> P V Deekshitha Reddy</h1>  
    <style> 
        body { 
            font-family: Arial, sans-serif; 
        } 
        .container { 
            width: 60%; 
            margin: auto; 
            border: 1px solid #ccc; 
            padding: 20px; 
        } 
        .header { 
            display: flex; 
            justify-content: space-between; 
            align-items: center; 
            margin-bottom: 20px; 
        } 
        .header-info { 
            flex: 1; 
        } 
        .header img { 
            width: 150px;  
            height: 150px;  
            border-radius: 50%; 
            margin-left: 20px; 
        } 
        .header h1 { 
            text-align: center; 
            width: 100%; 
        } 
        .header .speaker-info { 
            text-align: center; 
            margin-top: 20px; 
        } 
        .header .speaker-info p { 
            margin-top: 10px; 
        } 
        label { 
            display: block; 
            margin-top: 10px; 
        } 
        input[type="text"], input[type="email"], input[type="date"] { 
            width: 100%; 
            padding: 8px; 
            margin-top: 5px; 
            margin-bottom: 10px; 
            border: 1px solid #ccc; 
            border-radius: 4px; 
        } 
        .radio-group, .checkbox-group { 
            margin-top: 10px; 
        } 
        .radio-group label, .checkbox-group label { 
            display: inline-block; 
            margin-right: 10px; 
        } 
        input[type="submit"] { 
            background-color: #4CAF50; 
            color: white; 
            padding: 10px 20px; 
            border: none; 
            border-radius: 4px; 
            cursor: pointer; 
        } 
        input[type="submit"]:hover { 
            background-color: #45a049; 
        } 
    </style> 
</head> 
<body> 
 
    <div class="container"> 
        <div class="header"> 
            <div class="header-info"> 
                <h1>Event Registration Form</h1> 
                <hr> 
                <p><b>About This Event</b></p> 
                <p><b>Event Name:</b> Digital Marketing Masterclass</p> 
                <p><b>Date:</b> October 15, 2028</p> 
                <p><b>Time:</b> 2:00 PM - 4:00 PM</p> 
                <p><b>Speaker:</b> Sarah Johnson (Digital Marketing Expert)</p> 
                <p><b>Organizer:</b> WebinarPros LLC</p> 
                <p><b>More Information:</b> <a 
href="http://www.webinarpros.com">www.webinarpros.com</a></p> 
            </div> 
            <div class="speaker-info"> 
                <img src="deekshi.jpg" alt="Speaker"> 
                <h4>P V Deekshitha Reddy</h4> 
            </div> 
        </div> 
 
        <div class="section"> 
            <h2>Participant Information</h2> 
            <hr> 
            <label for="name">Full Name</label> 
            <input type="text" id="name" name="name"> 
             
            <label for="dob">Date Of Birth</label> 
            <input type="date" id="dob" name="dob"> 
             
            <label>Gender</label> 
            <div class="radio-group"> 
                <label><input type="radio" name="gender" value="male"> Male</label> 
                <label><input type="radio" name="gender" value="female"> Female</label> 
            </div> 
             
            <label for="phone">Phone Number</label> 
            <input type="text" id="phone" name="phone"> 
             
            <label for="email">Email</label> 
            <input type="email" id="email" name="email"> 
             
            <label>Where did you hear about this virtual event?</label> 
            <div class="checkbox-group"> 
                <label><input type="checkbox" name="source" value="facebook"> 
Facebook</label> 
                <label><input type="checkbox" name="source" value="youtube"> 
YouTube</label> 
                <label><input type="checkbox" name="source" value="instagram"> 
Instagram</label> 
                <label><input type="checkbox" name="source" value="twitter"> Twitter</label> 
                <label><input type="checkbox" name="source" value="other"> Other</label> 
            </div> 
        </div> 
 
        <div class="section"> 
            <h2>Payment Information</h2> 
            <hr> 
            <label for="tickets">Number of Tickets</label> 
            <input type="text" id="tickets" name="tickets"> 
             
            <label>Payment Method</label> 
            <div class="radio-group"> 
                <label><input type="radio" name="payment" value="credit"> Credit Card</label> 
                <label><input type="radio" name="payment" value="debit"> Debit Card</label> 
                <label><input type="radio" name="payment" value="cash"> Cash</label> 
                <label><input type="radio" name="payment" value="check"> Check</label> 
            </div> 
        </div> 
 
        <div class="footer"> 
            <input type="submit" value="Submit"> 
        </div> 
         
        <div class="disclaimer"> 
            <p>I understand that participation in this event may involve some degree of risk. I 
release WebinarPros LLC from any liability for injury, loss, or damage to personal 
property.</p> 
            <p>Date: September 22, 2027</p> 
        </div> 
    </div> 
 
</body> 
</html> 