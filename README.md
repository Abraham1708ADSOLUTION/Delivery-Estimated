# Estimated Delivery
--------------------- STEP 1 --------------------------
Open the file in this repository with the name "estimated-delivery.liquid"

--------------------- STEP 2 --------------------------
Copy all the code that appears in the file


--------------------- STEP 3 --------------------------
Open your Shopify code editor

--------------------- STAGE 4 --------------------------
Create a new file with the name "estimated-delivery.liquid"

--------------------- STEP 5 --------------------------
paste all the code you copied before

--------------------- STEP 6 --------------------------
Go to customize your Shopify code and then go to the product page


--------------------- STEP 7 --------------------------
select the custom liquid and type {% render 'estimated delivery' %}


If you want to change the values of the days, just change the numbers 3 and 6 to your estimated delivery days.

<script>
  document.getElementById("earliest-day").innerHTML = dayjs().add(3, 'days').format("MMM D");
  document.getElementById("latest-day").innerHTML = dayjs().add(6, 'days').format("MMM D");
</script>
