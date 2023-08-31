#portfolio-thumbnail-carousel

This is a sample of code I wrote using for the Laut Design company website lautdesign.com. This code uses a javascript library called Isotope and jQuery. Isotope is a pagination and sorting library that was already being used on the website on the portfolio page. I decided to use this library due to my familiarity with it, as well as the control over transitions and modifications.

The portion of JS that I wrote handles the initiation of the carousel, the timing of the loop, and user interactions. One subtle interaction that is used is that the loop is skipped any time the user is hovering over the grid. If you visit the Laut Design home page you will notice that while the portfolio section of the carousel is paused the client logos will continue. Once the user is done hovering over the portfolio that carousel will resume its loop on the same relative time as before. This ensures that the cascading animation doesn't align poorly.

The html that goes into this section is templated using a WordPress plugin called pods.io. Using the admin portal of the wordpress site a user can add portfolio items by filling in custom fields and those fields are used to generate the portfolio items you see on the website. I have attached images of what that template code looks like.

The Css for this section was also written to allow user interactions and revealing information when the user hovers over a portfolio thumbnail. This example uses randomly generated colors to make it each grid item easily distinguishable.
