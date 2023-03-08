# Bootstrap

## **Core concepts**

- **Breakpoints are the building blocks of responsive design.** Use them to control when your layout can be adapted at a particular viewport or device size.
- **Use media queries to architect your CSS by breakpoint.** Media queries are a feature of CSS that allow you to conditionally apply styles based on a set of browser and operating system parameters. We most commonly use `min-width` in our media queries.
- **Mobile first, responsive design is the goal.** Bootstrap’s CSS aims to apply the bare minimum of styles to make a layout work at the smallest breakpoint, and then layers on styles to adjust that design for larger devices. This optimizes your CSS, improves rendering time, and provides a great experience for your visitors.

# Containers

- .containers //with padding and margin
- .container-fluid // no padding and margin

# Basic Grid

- It has 12 total columns.
- class of the columns include .col-sm-NO , -md , -lg , -xl , -xxl assendingly.
- for equal columns use .col for all

# Text

- Headers .h1 - .h6
- <mark> Text <mark> //highlights txt.
- blockquote // for quotation

# Colors

- Text color // .text-muted,primary,success,info,warning,danger,secondary,white,dark,body,light.
- Background Colors // .bg-muted,primary,success,info,warning,danger,secondary, white,dark,body,light.

# Basic Tables

- First set .table class for the table tag.
- .table-responsive // for responsive table
- .table-striped // for zebra strip table
- .table-border// for bordered table
- .table-hover // for hovering bg colors table
- .table-dark// for bg color dark table
- .table-borderless // for borderless table

# Images

- Shapes .rounded .rounded-circle .img-tumbnail
- .float-start .float-end // but not very adviseable
- mx-auto (margin auto) .d-block(display block) // to make center
- .img-fluid to make image responsive
- width=”..px” // to set max width.

# Alerts

- First define class of div as alert.
- .alert-colors // to specify type.
- .alert-dismissible // to make it dismissible.
- <strong>Success</strong> // to make the success message bolder.
- /*To close alert message include a button inside the div with  */  class=”btn-close” and

      data-bs-dismiss=”alert”. 

# Buttons

- First assign the .btn to class of button div.
- .btn-colors // for bg colors.
- Types in button tag -button  -submit   -reset.
- .btn-outline-color // for border and text color.
- .btn-lg,sm for size of button
- .d-grid // in the top div for block size div
- .gap // in upper div for gap b/n buttons.
- disabled // for disabled button.
- span .spinner-border .spinner-border-sm for spinning button.
- span .spinner-grow .spinner-grow-sm for blinking button.

# Button Groups

- .btn-group // in top div
- btn-group-vertical // for vertical

# Badges

- Notifies of new things.
- .badge with a span.
- can add color.

# Pagination

- First add .pagination class to ui element.  .
- Then add .page-item class to li element.
- Then add .page-link class to a element. //for a better understanding.
- align with justify-content-…..

# Cards

- .card for the main div.
- .card-header for header
- .card-body for content.
- .card-footer for footer
- ..card-title for title inside body with <h>.
- .card-img-top,bottom for image position.
- .card-img-overlay for overlaid pic.

# Dropdown buttons

- .dropdown for the main div.
- .dropdown-menu for the ul.
- .dropdown-item for the a in side li.
- .dropdown-divider for horizontal line with in <hr>.
- .dropdown-header for header with <h> inside <li>
- .dropup for change in upwards.
- for a text use <span> instade of <a> in <li>.
- can also use button groups.

# Collapse

- First set a button / link inside a card/ and set data-bs-toggle=”collapse”  ,

data-bs-target=”#id”.

- Then set a div with class .collapse and with id=”id” // same with the above id.
- .collapse-show First show then collapse on click.

# Navs

- .nav in ul
- .nav-item for li
- .nav-link for a
- .flex-colum in ul for vertical
- nav + nav-tabs for tabs.
- nav + nav-pills for pills.

To make dynamic / changeable tabs/pills

- First add data-bs-toggle=”tab/pills”. for each a
- Then set herf with unique id for each a.
- then arp them inside a div with .tab/pill-content

# Nav bars

- .navbar inside nav tag
- navbar-expand-size.
- navbar-brand for logo.
- navbar-text for simple txt in a span

# Collapse navbar

- use a button with .navbar-toggler , set data-bs-toggel=”collapse” and data-bs-target=”#ID”.
- use span with .navbar-toggler-icon for the button inside button.
- create a div with .collapse nabar-colllapse id=”ID”.
- .fixed-top .sticky-top.