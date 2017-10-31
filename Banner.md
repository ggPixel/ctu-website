# Banners

[CTU Banners](https://ctutraining.ac.za/career-campus/) display on certain pages and can be easily managed from the Wordpress Editor screen.
You need to add custom fields to the page you would like to create a banner for.

This makes it easier to add/remove banners without having to remember to remove them!

## Banner image
Before you can create a banner you will need to set a Featured Image for the page you are working on.

Banner Dimensions: 2148 x 405 (72 DPI)

## Required Custom Fields

### Banner Title
`banner_title` *(Optional)* By default the page title will be used as the banner title but if you would like to use a custom title, use this custom field.

### Banner Text
`banner_text` *(Required)* Sub text displayed on the banner below the title.

### Banner Button Text
`banner_btn` *(Required)* The text dispaly for the button. Good idea to use a catchy phrase :)

### Banner Style
`banner_style` *(Optional)* All text on the banners are white. In some cases the image might be too light making it hard to read the text. This field is used to add a black overlay ontop of the banenr image to make text more readble. Current the only accepted value is `light`


## Next step
As soon as you have followed these steps, the page will be added to an administration page where you can add/remove it from specific pages on the frontend. The Top Banner (the area right at the top of the website where events/notices are displayed) can also be managed from there. Note that only one Top Banner can be dispalyed at a time.

## Side Note
If you are using a banner for a page that uses the `date` custom field, the banner will automatically be removed when the date has passed.
