# wordpress-shortcode-year-month
Shortcode for wordpress display year and month

Here's the PHP code to create a WordPress shortcode that displays the current year and month

**
// Create shortcode to display current year
function current_year_shortcode() {
    $current_year = date('Y');
    return $current_year;
}
add_shortcode('year', 'current_year_shortcode');

// Create shortcode to display current month
function current_month_shortcode() {
    $current_month = date('F');
    return $current_month;
}
add_shortcode('month', 'current_month_shortcode');

**

-- To use this shortcode, simply add [year] to display the current year and [month] to display the current month on any page or post in WordPress.

-- To use this shortcode in Gutenberg, you can follow these steps:

Create a new post or edit an existing post in WordPress.

Click on the "+" button to add a new block.

In the search bar, type "shortcode" and select the "Shortcode" block.

In the "Shortcode" block, enter the shortcode you want to use, such as "[year]" or "[month]".

Preview the post to see the current year or month displayed in place of the shortcode.

Alternatively, you can also use the "Code" block in Gutenberg to directly insert the PHP code that defines the shortcode. To do this:

Add a new "Code" block in Gutenberg.

Paste the PHP code provided earlier in the block.

Save the block and preview the post to see the shortcode in action.

Note that using the "Code" block requires a bit more technical knowledge, so it's recommended for users who are comfortable with coding and understand the potential risks of adding custom code to their website.


# To combine a shortcode with a Gutenberg heading in WordPress, you can follow these steps:

Add a new post or edit an existing post in WordPress.

Add a new "Heading" block by clicking the "+" button and selecting "Heading" from the block menu.

Type in the text you want to display in the heading.

After the text, add the shortcode you want to use, such as "[year]" or "[month]".

Preview the post to see the heading and shortcode displayed together.

Here's an example of what the code might look like:
