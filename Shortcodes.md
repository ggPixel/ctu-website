# CTU Website Administration & Maintenance

## Shortcodes

### List pages
`[listpages]`

This shortcode generates a list of pages.

#### Arguments
`pages` 
*(Required)*
Should it link through to the page? This argument only accepts two values: "disabled" or "enabled"

`link` 
*(Required)*
This argument accepts a list of comma separated page IDs

### Campus Staff
`[ctustaff]`

This shortcode displays a staff member and their job title

#### Arguments
`staff` 
*(Required)*
This argument accepts a list of comma separated names & surnames

`title` 
*(Required)*
This argument accepts a list of comma separated job titles. Note that the title list should match the amount of staff

`campus` 
*(Required) (lowercase)*
Name of the campus

### Career/Full Time courses list
`[fullcourses]`

This shortcode generates a list of full time courses

#### Arguments
`courses` 
*(Required)*
This argument accepts only 4 values. 'Business', 'IT', 'Design' or 'All'. Based on the value it will generate all courses under the faculty name. *Default: All*

### Career/Full Time courses dropdown
`[cfinder]`

This shortcode generates a full list of courses in a dropdown menu.

#### Arguments
`float` 
*(Optional)*
Float the element left or right *Default: Right*

### Countdown timer
`[counter]`

This shortcode generates a countdown timer.

#### Arguments
`date` 
*(Required)*
This argument accepts a date in the following format: DD-MM-YYYY HH:ii. 

`style` 
*(Optional)*
If this argument is empty it will simply output the number of days left until the event starts or the promotion if over.
If it is set to `box` it will display a counter in days, hours & seconds

`text` 
*(Required)*
The text used to display before/after the countdown timer

### Page Title
`[coursetitle]`

This shortcode is strictly used in Contact Form 7 emails to dynamically output the name of the page the enquiry was made.

#### Arguments
None

### Page ID
`[pageid]`

This shortcode is strictly used for the webinar booking form (Contact Form 7) to determine the ID of the webinar

#### Arguments
None

### Current Year
`[curr_year]`

This shortcode simply outputs the current year (e.g. 2017). Very handy when working with static pages in which the enrollment year needs to change every year.

#### Arguments
None

### Next Year
`[nxt_year]`

This shortcode simply outputs the follow year (e.g. 2018). Very handy when working with static pages in which the enrollment year needs to change every year.

#### Arguments
None

### Token generator
`[graduatetoken]`

This shortcode generates a 40 character token to be used for CVs created from the website.

#### Arguments
None

### HTML Clear All 
`[clear]`

A quick way to output `<div class='clear'></div>`. Can only be used inside the WordPress editor.

#### Arguments
None

#### Arguments
None
