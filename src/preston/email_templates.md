<mjml>
    <mj-body mj-class="body">
        <mj-spacer height="25px"></mj-spacer>
        <mj-section mj-class="section">
            <mj-column width="100%">
                <mj-text mj-class="title">${{ lang.hi_firstname_lastname }}$</mj-text>
            </mj-column>
        </mj-section>
        <mj-section mj-class="section">
            <mj-column mj-class="background-hero">
                <mj-text mj-class="title">${{ lang.order_order_name }}$ - ${{ lang.in_transit }}$</mj-text>
                <mj-divider mj-class="title-divider-hero"></mj-divider>
                <mj-text>${{ lang.your_order_with_the_reference_order_name_is_currently_in_transit }}$</mj-text>
                <mj-spacer height="20px"></mj-spacer>
                <mj-text>${{ lang.you_can_track_your_package_using_the_following_link }}$</mj-text>
                <mj-text padding-bottom="15px"><a href="${{ lang.tracking_link }}$" target="_blank">${{ lang.tracking_link }}$</a></mj-text>
            </mj-column>
        </mj-section>
    </mj-body>
</mjml>
```

## Password Query Template

The `password_query.mjml` template is used to send a password reset request to customers. It includes the following sections:

```mjml
<mjml>
    <mj-body mj-class="body">
        <mj-spacer height="25px"></mj-spacer>
        <mj-section mj-class="section">
            <mj-column width="100%">
                <mj-text mj-class="title">${{ lang.hi_firstname_lastname }}$</mj-text>
            </mj-column>
        </mj-section>
        <mj-section mj-class="section">
            <mj-column mj-class="background-hero">
                <mj-text mj-class="title-hero">${{ lang.password_reset_request_for_shop_name }}$</mj-text>
                <mj-divider mj-class="title-divider-hero"></mj-divider>
                <mj-text>${{ lang.you_have_requested_to_reset_your_shop_name_login_details }}$</mj-text>
                <mj-spacer height="20px"></mj-spacer>
                <mj-text>${{ lang.please_note_that_this_will_change_your_current_password }}$</mj-text>
                <mj-spacer height="20px"></mj-spacer>
                <mj-text>${{ lang.to_confirm_this_action_please_use_the_following_link }}$</mj-text>
                <mj-text padding-bottom="15px"><a href="{url}">{url}</a></mj-text>
            </mj-column>
        </mj-section>
    </mj-body>
</mjml>
