# build-a-checkout-page
little project
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <title>Checkout Page</title>
</head>

<body>
<h1>Checkout</h1>
<section>
    <h2>Your Cart</h2>
    <img src="https://cdn.freecodecamp.org/curriculum/labs/cube.jpg" alt="Three multicoloured dice">
    </section>
<section>
<h2>Payment Information</h2>
<form>
    <label for="card-name">Card Name<span aria-hidden="true">*</span></label>
    <input type="text" id="card-name" name="card-name" required>

    <label for="card-number">Card Number<span aria-hidden="true">*</span></label>
    <input type="text" id="card-number" name="card-number" required aria-describedby="card-number-help">
    <p id="card-number-help">Please input correct card Number and card name should be thesame with your profile</p>
    </form>
 </section>
</body>

</html>
