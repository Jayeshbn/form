# form
mini project on html form

<!DOCTYPE html>                   INPUT , FORM
<html>
    <head>
        <title>
            payment form
        </title>
    </head>
    <body style="background-color:greenyellow">
        <h1 style="text-align:center; background-color:black;color:yellow; ">payment form</h1>
        <hr>
        <h2 style="color:black;border:1px solid black">customer details</h2>

        <form action="jayy.css" target="_blank">

        <p>first name:<br>*<input type="text" name="name" required></p>
        <p>last name:<br>&nbsp&nbsp&#128151&#128187<input type="text" name="name"></p>
        <fieldset><legend style=color:blue>GENDER</legend>
        <p>male <input type="radio" name="gender">
        female <input type="radio" name="gender">
        others<input type="radio" name="gender"></p>
        </fieldset>
        <fieldset><legend style=color:blue>GENDER</legend>
            <p>male <input type="checkbox" name="gender">
            female <input type="checkbox" name="gender">
            others<input type="checkbox" name="gender"></p>
            </fieldset>
        <P>address:<textarea placeholder="address" rows="5" cols="50"></textarea></P>
        <p>email:<input type="email"></p>
        <p>pincode:<input type="number"></p>
        <hr>
        <h2 style="border:2px solid black;">card details</h2>
        <p>card type:
            <select>
                <option value="">select the card type</option>
                <option value="debit card">debit card</option>
                <option value="visa card">visa card</option>
               <option value="master card">master  card</option>
            required</select>
        </p>
        <p>image:<input type="image" src="C:\Users\hp\Desktop\anime.jpg" name="img"></p>
        <P>card number:<input type="number" name="card number required"></P>
        <p>CVV:<input type="password" name="CVV" required></p>
        <P>expiry date:<input type="date" required></P>3
        <p>select color<input type="color" name="color"></p>
        <p>date<input type="date" name="date"></p>
        <p>time<input type="time" name="time"></p>

 
        <input type="submit" value="pay now">
        <input type="reset">
        </form>

    </body>
</html>