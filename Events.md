# CTU Events Management

Events are created by adding a new page (Events are not yet a custom post type although it is in the pipeline). All events are automatically pulled to [this page](https://ctutraining.ac.za/upcoming-events/).
When creating a new event you need to ensure the parent page is set to "Upcoming Events" otherwise the event will NOT show up on this page.

## Custom fields

Events use custom fields (found at the bottom of the Wordpress edit screen [ensure you have Custom Fields selected in the Screen Options tab, otherwise you will not see the custom fields section])
Custom fields make it easier to manage events are ensure that when an event has passed that it does not show up on the Events page and gets removed from search results.

### Guide to setting up an event.

1. Create a new page and add your content. An event usually contains a booking form (Contact Form 7) so add this if necessary.

#### Required custom fields

##### DATE

Format: DD-MM-YYYY HH:ii

The date field is used to determine whether it should be displayed on the website and in search results.
If the events spans over a couple of hours you can use the date like so: 11 November 2017 09:00-13:00. The last part will automatically be stripped to determine the start date.
