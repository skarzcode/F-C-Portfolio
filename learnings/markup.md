## 1. Structure a site using semantic HTML to aid accessibility
![Screenshot of First Project](https://user-images.githubusercontent.com/85761315/220893516-69588970-14de-4071-a69f-cac7c0887028.png)

This screenshot shows that we incorporated semantic elements in our HTML, including demarcating each section so that it can be tabbed through by the user, as well as H1 and H2 headings in the correct order, which ensured that they would be read out by a screen reader (see below). In addition, we used alt-tags on each image. Being able to tab through the site is especially important for those with sight access requirements, our goal was to minimise the use of div unless we really needed to and utilise other semantic HTML which i believe we achieved but definitely belive we can go back and refactor some of those divs.

## 2. Ensure a web page is readable for screen readers
We aimed to make the website usable by all, including those with disabilities, and to achieve this goal, we employed various techniques to enhance the content's readability for screen readers, thus improving the site's accessibility.
![Screenshot of First accessibility methods](https://user-images.githubusercontent.com/85761315/220909788-26117c77-1805-47c7-8f0d-f3e6518efe95.png)

- We used appropriate <b>"alt"</b> attributes for images to provide a brief and clear descriptions, <br />
allowing screen readers to communicate the content to users who are unable to see the image.<br /> <br />

- Additionally, we used <b>*"Tab Index"*</b> attributes to allow users to tab throught content and reveal <br />
information that otherwise would not have been seen due to css hover animations.<br />

- Finally, we used descriptive class names and id values, which can also help screen readers understand the structure <br />
and content of the page. This makes it easier for users to navigate the page using their screen reader and find the <br />
information they need more quickly and efficiently.


## 3. Ensure our UI has sufficient colour contrast so that everyone can perceive it comfortably

For each section of the page, we selected complementary colors that had a sufficient contrast ratio. We made sure that the background color contrasted well with the text color, as well as with the foreground.

## 4. Use various tools to check that our website meets accessibility criteria
- Throughout the development process, we consistently used Google Chrome's Lighthouse tool to audit and improve the quality and performance of the page. By doing so, we were able to identify areas for improvement. Our accessibility rating currently stands at 98% and got a Best practise rating of 100%.

- We conducted keyboard testing to verify that all website functionality could be accessed solely through keyboard navigation. This involved manually navigating all sections of the web page using only our keyboards.

- We utilized the screen reader tools available on both Windows and Mac systems to simulate how the web page would be read aloud to users with visual impairments. This allowed us to identify areas that required improvement and address them during development.

## 5. Use CSS media queries to ensure our content is always presented effectively on screens of different sizes
[![Screenshot of media queries](https://user-images.githubusercontent.com/85761315/220918561-f9be69ec-6c88-4a2e-bd77-12428cfd29c9.png)

To guarantee that users can easily read and navigate the content on any screen size, we utilized media queries to adjust the layout, font size, and other styles. Our aim was to ensure that the page is always presented effectively on screens of varying sizes, delivering an optimal user experience for all.

## 6. Use CSS variables to apply repeated colours to HTML elements
![Screenshot of CSS variables](https://user-images.githubusercontent.com/85761315/220921630-13a1e477-32e5-45da-8d96-5abb1699d6ca.png)

We utilized coordinated colors throughout our page and leveraged CSS variables to improve code readability, manageability, and maintainability.<br>

By using CSS variables for our colors, we could update them in a single place, rather than making changes to multiple instances throughout our stylesheet. This streamlined the process of maintaining consistent colors across the site and made it easier to make updates in the future.

## 7. Use CSS Flexbox/CSS Grid to style children in a single-direction layout (ie a row or a column)
![Screenshot of Flexbox](https://user-images.githubusercontent.com/85761315/220924015-bb08a17d-89c1-4e6e-908a-77bc33a48c0f.png)

We established fundamental flex layout classes in our CSS to style children in a singular direction, and we applied these classes to our HTML elements. This allowed us to manage the alignment of flex items along both the main and cross axes.

## 8. Ensure our Git commit history tells a coherent story

## 9. Use the appropriate input types in HTML forms for gathering different types of information
