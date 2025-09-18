    <!DOCTYPE html>
    < lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>example of div</title>
    </head>
    <body>  <h2> contact form</h2>
        <div> 
            <lable for ="name">Name:</lable>
            <input type="text" id="name" name="name"placeholder="enter your name">
        </div>
        <br>
        <div>
            <lable for ="email">Email:</lable>
            <input type="email" id="email" name="email" placeholder="enter your email">
        </div>
        <br>
        <div>
            <lable for ="phone">phone Number:</lable>
            <input type="tel" id="phone" name="phone" placeholder="enter your 10 digit num">
        </div>
            <lable for ="phone">phone number:</lable>
            <input type="tel" id="phone" name ="phone"
            placehold="enter your phone number" pattern="[0-9]{10}"
            inputmode="numeric" required aria-required="true"
            aria-describedby="phone-error"
            onkeypress="restricAlphabets(event)">
            

        
    </body>

