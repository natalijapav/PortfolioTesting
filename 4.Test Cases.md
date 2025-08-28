## Test Cases - Farmit
# Test Case 1: Verify default state on homepage - UI/UX elements 

- **Priority:** [High]  
- **Preconditions:** User is on the homepage.

## Steps  

| Step | Test Steps | Test Data | Expected Results |
|------|------------|-----------|------------------|
| 1 | Verify header elements: Logo, Navigation Menu, Language Switch, Profile button, Cart icon | / | All elements are visible and aligned according to design |
| 2 | Verify body sections: Text, Images, CTA buttons, Animations | / | All elements display correctly without overlap or distortion |
| 3 | Scroll down and verify footer elements: Logo, Links, Social Media buttons | / | Footer elements are visible and correctly aligned|
| 4 | Hover over profile icon | / | Appearance or color changes according to design|
| 3 | Hover over cart icon | / | Appearance or color changes according to design|


# Test Case 2: Verify default state on homepage - navigation and interactive elements 

- **Priority:** [High]  
- **Preconditions:** User is on the homepage.

## Steps  

| Step | Test Steps | Test Data | Expected Results |
|------|------------|-----------|------------------|
| 1 | Scroll through all sections | / | Sections scroll smoothly and content is accessible |
| 2 | Check "Najčešća pitanja" (FAQ) section | / | All questions expand/collapse correctly when clicked |
| 3 | Click Farmit logo in nav menu and footer | / | Page scrolls back to top |


# Test Case 3: Check ''Postani partner'', ''Prijavi se'' buttons are visible and clickable and redirect correctly


- **Priority:** [High]  
- **Preconditions:** Go to the website 

## Steps  

| Step | Test Steps | Test Data | Expected Results |
|------|------------|-----------|------------------|
| 1 | Check if the button "Postani partner" is visible | / | The button "Postani partner" is displayed |
| 2 | Click on the button "Postani partner" | / | User is redirected to the correct page (check that the URL matches expected) |
| 3 | Navigate back to the homepage | / | Homepage loads successfully |
| 4 | Check if the button "Prijavi se" is visible | / | The button "Prijavi se" is displayed |
| 5 | Click on the button "Prijavi se" | / | User is redirected to the correct page (check that the URL matches expected) |


# Test Case 4: Check ''Pocetna'', ''O nama'', ''Paketi'' tabs are visible and clickable and redirects correctly


- **Priority:** [High]  
- **Preconditions:** Go to the website https://fitgarden-qa.vercel.app/


## Steps  

| Step | Test Steps | Test Data | Expected Results |
|------|------------|-----------|------------------|
| 1 | Check if the button "Pocetna" is visible | / | The button "Pocetna" is displayed |
| 2 | Click on the button "Pocetna" | / | User is redirected to the correct page (check that the URL matches expected) |
| 3 | Navigate back to the homepage | / | Homepage loads successfully |
| 4 | Check if the button "O nama" is visible | / | The button "O nama" is displayed |
| 5 | Click on the button "O nama" | / | User is redirected to the correct page (check that the URL matches expected) |
| 6 | Navigate back to the homepage. | / | Homepage loads successfully |
| 7 | Check if the button "Paketi" is visible | / | The button "Paketi" is displayed |
| 8 | Click on the button "Paketi" | / | User is redirected to the correct page (check that the URL matches expected) |


# Test Case 5: Verify selecting ENG/SRB changes language correctly and displays content accordingly

- **Priority:** [High]  
- **Preconditions:** Default language is SRB.

## Steps  

| Step | Test Steps | Test Data | Expected Results |
|------|------------|-----------|------------------|
| 1 | Click on language selection | / | Language dropdown opens |
| 2 | Select the English language | / | Page content updates and displays in English |
| 3 | Pay attention to the language | / | Confirm all visible text is in English |
| 4 | Click on language selection and select SRB | / | Page content updates and displays in Serbian |
| 5 | Pay attention to the language | / | Confirm all visible text is in Serbian |


# Test Case 6: Verify button functionality on User’s Homepage

- **Priority:** [High]  
- **Preconditions:** The user is logged in. User is on the homepage.

## Steps  

| Step | Test Steps | Test Data | Expected Results |
|------|------------|-----------|------------------|
| 1 | Locate and click the button “Saznaj kako” | / | The user is redirected to the corresponding page |
| 2 | Click on the tab “Početna” or use back arrow to return | / | The user is on the homepage |
| 3 | Locate and click the button “Pogledaj gajbice” | / | The user is redirected to the corresponding page |
| 4 | Click on the tab “Početna” or use back arrow to return | / | The user is on the homepage |


# Test Case 7: Verify that social media links are working correctly

- **Priority:** [High]  
- **Preconditions:** User is on the page containing social media buttons.

## Steps  

| Step | Test Steps | Test Data | Expected Results |
|------|------------|-----------|------------------|
| 1 | Locate the Facebook button and click it | / | The link opens in a new tab and navigates to Facebook page |
| 2 | Locate the Instagram button and click it | / | The link opens in a new tab and navigates to Instagram page |
| 3 | Locate the LinkedIn button and click it | / | The link opens in a new tab and navigates to LinkedIn page |
| 4 | Locate the TikTok button and click it | / | The link opens in a new tab and navigates to TikTok page |


# Test Case 8: Verify email subscription functionality ''Prijavi se i budi u toku''

- **Priority:** [High]  
- **Preconditions:** User is on the page containing the subscription section.

## Steps  

| Step | Test Steps | Test Data | Expected Results |
|------|------------|-----------|------------------|
| 1 | Scroll down to the ''Prijavi se i budi u toku'' section | / | The subscription section is visible |
| 2 | Enter a valid email in the subscription box | / | Email is entered correctly in the input field |
| 3 | Click on ''Prijavi se'' button | / | ''Uspešno ste se prijavili.'' notification is displayed |


# Test Case 9: Verify default UI/UX elements on homepage

- **Priority:** [High]  
- **Preconditions:** User is on the homepage.

## Steps  

| Step | Test Steps | Test Data | Expected Results |
|------|------------|-----------|------------------|
| 1 | Verify header elements: Logo, Navigation Menu, Language Switch, Profile button, Cart icon | / | All elements are visible and aligned according to design |
| 2 | Verify body sections: Text, Images, CTA buttons, Animations | / | All elements display correctly without overlap or distortion |
| 3 | Scroll down and verify footer elements: Logo, Links, Social Media buttons | / | Footer elements are visible and correctly aligned |
| 4 | Hover over profile icon. | / | Appearance or color changes according to design |
| 5 | Hover over cart icon. | / | Appearance or color changes according to design |

---

# Test Cases - Benefiti.rs
# Test Case 1: Verify that the Name and Surname fields does not accept input longer than 30 characters

- **Priority:** [High]  
- **Preconditions:** The user is logged in with an account.

## Steps  

| Step | Test Steps | Test Data | Expected Results |
|------|------------|-----------|------------------|
| 1 | Click on the Employee section from the sidebar | / | Employee section is displayed |
| 2 | Click on the "+ Add Employee" button | / | User is redirected to “Add Employee” page |
| 3 | Fill in the ‘’Name’’ field | ‘’testtesttesttesttesttesttesttest’’ | Added name is displayed |
| 4 | Fill in the ‘’Surname’’ field | ‘’testtesttesttesttesttesttesttest’’ | / |
| 5 | Click on ‘’Add’’ button | / | ValidationError is shown: "firstName" must be shorter than/or equal to 30 characters |


# Test Case 2: Verify Name and Surname fields does not accept empty input

- **Priority:** [High]  
- **Preconditions:** The user is logged in with an account.

## Steps  

| Step | Test Steps | Test Data | Expected Results |
|------|------------|-----------|------------------|
| 1 | Click on the Employee section from the sidebar | / | Employee section is displayed |
| 2 | Click on the "+ Add Employee" button | / | User is redirected to “Add Employee” page |
| 3 | Leave the Name field empty | / | / |
| 4 | Leave the Surname field empty | / | / |
| 5 | Click on "Add" button | / | *is required is displayed above the field Name, Surname |


# Test Case 3: Verify the email field accepts a properly formatted email address

- **Priority:** [High]  
- **Preconditions:** The user is logged in with an account.

## Steps  

| Step | Test Steps | Test Data | Expected Results |
|------|------------|-----------|------------------|
| 1 | Click on the Employee section from the sidebar | / | Employee section is displayed |
| 2 | Click on the "+ Add Employee" button | / | User is redirected to “Add Employee” page |
| 3 | Enter valid email address into Email field | test@gmail.com | Email is displayed and accepted |
| 4 | Fill in all other required fields with valid data | Test Test ... | All data is displayed correctly |
| 5 | Click on "Add" button | / | ‘’Employee successfully added!’’ Message is shown, Redirected to ‘’Employees’’ page |


# Test Case 4: Verify "Contact" list only accepts numeric input

- **Priority:** [High]  
- **Preconditions:** The user is logged in with an account.

## Steps  

| Step | Test Steps | Test Data | Expected Results |
|------|------------|-----------|------------------|
| 1 | Click on the Employee section from the sidebar | / | Employee section is displayed |
| 2 | Click on the "+ Add Employee" button | / | User is redirected to “Add Employee” page |
| 3 | Enter valid numeric phone number | +123456 | Number is displayed correctly |
| 4 | Fill in all other required fields with valid data | Test Test ... | All data is displayed correctly |
| 5 | Click on "Add" button | / | "Employee successfully added!" Message is shown |









