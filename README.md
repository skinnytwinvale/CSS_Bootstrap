# CSS_Bootstrap

Twitter Bootstrap is a CSS framework built and maintained for free by Twitter. It's a collection of style rules and additional tools to help build responsive layouts faster.

Twitter Bootstrap offers a responsive grid, many default styles for buttons, typography, tables, forms, and much more. It also has a small JavaScript library for interactive components like dropdowns, carousels and more.

You can include Bootstrap by:
copy and paste the CDN link tag into your HTML file and you will have Bootstrap right away!

You've probably noticed that the link tag you copy from the Bootstrap site has some attributes we haven't seen before: integrity and crossorigin. These attributes provide a layer of security when
requesting files from a CDN, through a feature called Subresource Integrity. 

CDN stands for Content Delivery Network, and it's essentially a network of servers that are used to deliver content to users around the globe. Having a network of servers makes that delivery faster, because you can deliver content from whichever server is geographically closest to the user. It also provides a safeguard in case one of the servers goes down.

## Layout

The most commonly used feature of Bootstrap is its grid system. With the right combination of CSS classes, you can build sophisticated grids (based on 12 columns) to lay out your page. Bootstrap will handle the responsive design based on the classes that you choose.

### Containers

Any layout that you build with Bootstrap should begin with a container. 
Containers are the most basic layout element in Bootstrap and are required when using our default grid system

A container is just a div with one of two classes: 
container elements have fixed widths that change at a finite number of break points
container- fluid elements always take up 100% of the available width

### The Grid System

A grid system is a way to organize the content on your page in terms of rows and columns.

Bootstrap's grid system uses a twelve-column grid layout. This means that when you're using the system, you can specify to bootstrap how many columns you want your content to take up, out of a possible maximum of twelve columns.

In order to make use of the grid system, you first need to have a container, created with either the container or container-fluid class. After that, you can create a row for the grid using the row class. Inside of the rows, you should only place columns classes, and finally, your content will live inside of the columns.



<img width="613" alt="Screenshot 2023-03-25 at 3 05 25 PM" src="https://user-images.githubusercontent.com/101606295/227736573-c2f9c679-03fe-45da-96ec-aff1a9a4a015.png">

<img width="853" alt="Screenshot 2023-03-25 at 3 22 47 PM" src="https://user-images.githubusercontent.com/101606295/227737348-a9bd214f-750e-4e66-8495-be5fe7771e64.png">

### Margin and Padding

Bootstrap comes with a number of classes to help add space between elements on the page. These elements all come in the form {property}{sides}-{size} or {property}{sides}-{breakpoint}-{size}, where property, sides, breakpoint, and size are one of the following:

- property: m (margin) or p (padding)
- sides: t (top), b (bottom), l (left), r (right), x (left and right), or y (top and bottom). You can also leave this value blank to target all directions.
- breakpoint: sm, md, lg, or xl. You can also leave this value blank to target xs.
- size: a number from 0 to 5. Larger numbers indicate more space.

### Typography and buttons


