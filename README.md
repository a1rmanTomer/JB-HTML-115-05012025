# Exercise: Create a Car Rental Order Page in HTML

<!-- Only Styling TBD -->

## Instructions

1.  **Set Up Your HTML File:**

    - Create a new file named `car_rental_order.html`.
    - Use the standard HTML structure (DOCTYPE declaration, `<html>`, `<head>`, and `<body>` tags).
    - create a new file named `order_submitted.html` with h1 contains `Ordered Successfully`

2.  **Add a Title and Heading:**

    - Include a `<title>` in the `<head>` section, e.g., "Car Rental Order".
    - Add a `<h1>` heading at the top of the page with the text "Car Rental Order Form".

3.  **Create the Form:**

    - Use the `<form>` tag to define the form.
    - Set the `action` attribute to `"/order_submitted.html"` (or any placeholder) and the `method` attribute to `POST`.

4.  **Add the Following Fields:**

    1. **Name**

       - Input type: text
       - Label: "Full Name"
       - Placeholder: "Enter your full name"

    2. **Email**

       - Input type: email
       - Label: "Email Address"
       - Placeholder: "Enter your email"

    3. **Phone Number**

       - Input type: tel
       - Label: "Phone Number"
       - Placeholder: "Enter your phone number"

    4. **Pickup Date**

       - Input type: date
       - Label: "Pickup Date"

    5. **Return Date**

       - Input type: date
       - Label: "Return Date"

    6. **Car Type**

       - Input type: radio buttons
       - Options: "Sedan", "SUV", "Truck", "Convertible"

    7. **Extras**

       - Input type: checkboxes
       - Options: "GPS", "Child Seat", "Additional Driver"

    8. **Rental Duration**

       - Input type: number
       - Label: "Number of Days"

    9. **Pickup Location**

       - Input type: text
       - Label: "Pickup Location"
       - Placeholder: "Enter pickup location"

    10. **Comments**

        - Input type: textarea
        - Label: "Special Requests"
        - Placeholder: "Enter any special requests"

    11. **Pick up from**

        - Input type: select
        - Label: "Pick up location"
        - Options: "Airport", "City", "Mall"

5.  **Add a Submit Button:**

    - Use the `<button>` or `<input>` tag with the type set to `submit`.
    - Label the button as "Submit Order".

6.  **Style the Form (Optional):**
