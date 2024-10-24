# Kodeloftet_Dag7

How we can create **responsive websites** that adapt to different devices, whether it's a desktop, a tablet or a mobile phone. The goal is for our websites always to work well and look visually appealing, regardless of which device the user is using. We particularly focused on Media Queries, an important method in CSS that makes the design responsive.

**Media Queries** allows us to define which CSS Rules should be active based on screen size or orientation. This is essential in responsive web design because it allows us to adapt the layout of the website to different devices. For example, we can have a horizontal design for desktop users and a vertical design for mobile users, without requiring separate web pages for each device.

Another big part of creating responsive websites is the choice of measurement units when we set sizes for elements. Here it is important to distinguish between **fixed and responsive units**. Fixed units, such as pixels (px), give us precise control over the size of elements, but are less flexible when working with different screen sizes. Responsive units, such as percent(%), em and rem, on the other hand, adapt proportionally to the size of surrounding elements and the root element. This makes them much more flexible and useful in responsive design, as they can be scaled as needed and ensure better adaptation on different devices. We can also use entities like viewport width(vw) and viewport height(vh) to ensure that elements fill the screen properly without disturbing the design.

When we create responsive design, some several techniques and tools can help ensure that the layout and content work optimally. For example, we can use **Flexbox or Grid** (will visit later in the course) in CSS, which gives us flexibility when we adapt the placement of elements. These layout methods make it easier to adjust how the content is presented, depending on the screen size, without requiring a lot of extra CSS code. We should also remember to adapt images and other media so that they are scaled appropriately.

Finally, it is important to **test the design on different devices**. Responsive design is not only about how the website looks on a mobile or a desktop, but also about ensuring a good user experience across all devices and browsers. Browser tools like **DevTools(inspector)** allow us to simulate different devices and test the design without having to use physical equipment.

Task Description
-------------------
Your task is to create a website that adapts to different screen sizes using media queries. This involves ensuring that the layout, text and images are adjusted and look good both on small screens, such as mobile phones, and larger screens, such as tablets and computers. When you start the task, it is important to think about how you can best structure the code to make it as clear and understandable as possible, both for you who write it and for us who will evaluate it. It can be advantageous to start with a plan for how the website will be built so that you have a clear idea of ​​the content and structure before you start coding.

**Claim**:
- Use semantic HTML and external CSS.
- Set up a header and footer with appropriate links and/or information.
- Create sections in the main content that contain different information adapted to the purpose of the website.
- Consider where it is natural to use fixed or responsive target units for optimal design.
- Set up a breakpoint with a media query that changes the design of the website, so that it adapts to large screens (such as laptops) and small screens (such as mobile phones).
- Use Flexbox to adjust the position of elements on two classes at the breakpoint
**Bonus**:
- Set up multiple breakpoints with media queries to adapt the design to different screen sizes: larger screens (monitor/TV), large screens (laptop), medium screens (tablet), and small screens (mobile).
- Use CSS Grid to change the position of the elements at the various breakpoints.
- Add content that should only be displayed on either desktop or mobile, depending on the screen size.

[Edit in StackBlitz next generation editor ⚡️](https://stackblitz.com/~/github.com/sharmababita/Kodeloftet_Dag7)

