# Architecture
The main AngelECU website architecture.
Before I start to write any source code or create any UI designs, I want to codify some more details regarding the website's organization (sitemap), content (persistent website components), and users (actors).  To start with, I've come up with the following list:
Actors
New Customer: A person requiring assistive technologies who is considering purchasing an ECU/EADL for personal use.
Returning Customer: A person who has already purchased an ECU/EADL and is looking to purchase additional modules or is looking for technical support or additional information.
Advocate: A person acting on behalf of an aforementioned customer.
Reseller: A person acting on behalf of a company interested in reselling your products.
Organization (Sitemap) & Content (of some of the pages)
All old URLs will be forwarded to the new ones.
Landing Page: same as Root URL aka Home Page
Embedded general flagship commercial advertisement video
Feature images
Overall tagline of Angel ECU
A little more details about Angel ECU, but not too much
An accompanying Learn More Button/Link
Testimonials
Product Details Page: /products/product-name/
Product Name
Feature image of product
Other photos of product
Brief description or tagline of product
Technical Specifications
Link to Warranty page
Link to Downloads page
Link to Compare page
Product Features Comparison Page
Offers you to view all or select multiple products to be compared in a Product Comparison Chart
A very elaborate example of this can be found here: https://www.productchart.com 
Product Downloads Page: /products/product-name/downloads/
Password-protected access to User Manuals and Software/Firmware
Users have to register with their name, purchased product serial/warranty number, and email address to get access.
Become A Reseller Page: /reseller/
About Page: /about/
Contact Page: /contact/
Testimonials Page: /testimonials/
Resources Page: /resources/
Warranty Page: /warranty/
Privacy Policy: /privacy/
Terms of Service: /terms-of-service/
Persistent Website Components 
Root URL: https://angelecu.com 
Need an SSL CA-Signed Certificate
Consult your hosting provider or this list: https://ccadb-public.secure.force.com/mozilla/IncludedCACertificateReport  
Header
Logo
When clicked, if the actor is currently on the Landing Page, nothing happens.  Alternatively, when clicked, if the actor is not currently on the Landing Page, they are redirected to the Landing Page.
Navigation Menu
Products
FX ECU
EX ECU
GT ECU
I/OPod
A-Pod
R-Pod
Uni-Com
VR-2
SSV-4
Downloads (password protected)
Same list as Products section
About Us
Testimonials
Resources
Quick Contact Section
Customer Service Phone Number
Contact Button
Footer 
Same content as in the Header with a few additional items.
Copyright Notice
Privacy Policy
Terms of Service
Commercial Credibility Emblems/Badges (think Angie's List)
Website Security Emblems/Badges (this website is secured by DigiCert)
In future iterations, with shopping cart functionality, we would want something about PCI Compliance
That's all for now.  Let me know if you think of anything else or have any changes that need to be made.  Perhaps, if we discover that we need to come up with some more detailed user stories to help us design specific features of the website, I will create another list for those as well.  Not to mention accessibility and SEO concerns (even more lists; I guess I should have started with a list of lists.  Heh.).
