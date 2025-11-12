 **Homework: Requirements**
 The Software
**Webshop site** with the following existing functionalities:  
- Register and login functionality  
- Searching for products, sorting by price, and browsing product categories  
- Add products to favorites  
- Add products to basket  
- Checkout process: billing and shipping information in a form, choose payment method, and calculate total price  

---

1. Product Rating System**

**Requirement:**  
Users should be able to rate products with a 5-star system and have the option to add written feedback.  

**Questions:**  
1. Do users need to be logged in to rate a product, or can guests also submit ratings?  
2. Can users edit or delete their rating after submitting it?  
3. Are ratings limited to whole stars (1–5), or can half-star ratings be used?  

**Detailed Requirements:**  
1. Rating is available only for logged-in users.  
2. Each user can rate a product once and may edit their rating later.  
3. Ratings must be whole numbers from 1 to 5 (no half stars).  

---

2. Age Verification for Alcoholic Products**

**Requirement:**  
Alcoholic products require age verification. A modal should appear when navigating to the alcoholic products category asking if the user is 18+. Users must input their age before accessing the alcoholic products.  

**Questions:**  
1. Does the age verification modal appear only when entering the Alcohol category, or also when searching for alcoholic products?  
2. If the user is under 18, should they be blocked from viewing the page entirely or just from purchasing?  
3. Will there be a second age check during checkout if the cart includes alcoholic products?  

**Detailed Requirements:**  
1. An age verification modal appears automatically when entering or searching in the Alcohol category.  
2. If the user is under 18, they are blocked from viewing or buying alcoholic products.  
3. A second verification check appears during checkout if the cart includes alcoholic items.  

---

3. Shipping Cost Changes**

**Requirement:**  
Free shipping for orders above a certain amount. Orders below this amount will incur a shipping fee.  

**Questions:**  
1. What is the exact minimum order amount required for free shipping?  
2. Is the free-shipping threshold calculated before tax or after discounts are applied?  
3. If a product is returned and the total drops below the free-shipping threshold, should shipping fees be charged retroactively?  

**Detailed Requirements:**  
1. Orders above €50 (after discounts) qualify for free shipping.  
2. Orders below €50 will be charged a flat €5 shipping fee.  
3. If an item is returned and the order total drops below €50, €5 will be deducted from the refund amount.  
