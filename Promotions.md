# CTU Promotions Management

Promotions are created by adding a new page (Promotions are not yet a custom post type although it is in the pipeline). All Promotions are automatically pulled to [this page](https://ctutraining.ac.za/promotions/).
When creating a new Promotion you need to ensure the parent page is set to "Promotions" otherwise the Promotion will NOT show up on this page.

## Custom fields

Promotions use custom fields (found at the bottom of the Wordpress edit screen [ensure you have Custom Fields selected in the Screen Options tab, otherwise you will not see the custom fields section])
Custom fields make it easier to manage Promotions are ensure that when a Promotion has passed that it does not show up on the Promotions page and gets removed from search results.

### Guide to setting up an Promotions.

1. Create a new page and add your content. 

#### Required custom fields

##### DATE
`date`
Format: DD-MM-YYYY HH:ii

The date field is used to determine whether the promotion has passed.

##### DESCRIPTION
`short_description`

Text that will be displayed on the All Promotions page.
