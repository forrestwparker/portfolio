### Coding Portfolio for Forrest Parker
***

[BlueRibbonsReview.com](http://www.blueribbonsreview.com/) is a sales aggregator that features discounted products at a number of popular online retailers.

My two main contributions to the site include:
- Greatly expanding the number of affiliate retailers on the site, including eBay, Walmart, Etsy, and others.
- Designing and implementing a feature to automatically update prices and send notifications to site administrators in certain circumstances.
- Designing and implementing a new system to standardize the categories for products from all retailers across the site.

On a technical level, my contributions required:
- Consuming RESTful APIs to access retail product information.
- Parsing JSON and XML data provided by the APIs.
- Modifying the site database using Entity Framework code-first migrations to allow for handling product data from multiple retailers. (The database had originally been designed for storing product data only from Amazon. The changes required modifying fields in multiple tables to enable universal retailer support.)
- Writing code in HTML, CSS, JavaScript, jQuery, and C# (including C# Razor syntax) using an MVC architectural pattern to enable front-end utilization of the new features in a user-friendly manner (both for site users and administrators).
