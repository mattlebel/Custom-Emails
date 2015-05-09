# Tilt/Open Pre-Orders

## Email customization guide

We're looking forward to helping you customize your Pre-Order emails! Below you'll find some tips & tricks to get you going.

## General info

You can choose to use our default emails (which prominently feature the logo you upload in your admin panel under "Site Settings") or choose to use completely custom emails.

Each pre-order campaign has three emails:

### Payment confirmation email

This email is sent upon completion of a successful pre-order.

**Available email variables:**

* Customer name {{ customer_name }}
* Quantity {{ quantity }}
* Subtotal {{ subtotal }}
* Shipping {{ shipping }}
* Total charged (required) {{ total_charged }}
* Date charged (required) {{ date_charged }}
* Name on card (required) {{ name_on_card }}
* Billing statement text (required) {{ billing_statement_text }}
* Transaction ID (required) {{ transaction_id }}
* Card type {{ card_type }}
* Card last four {{ card_last_four }}
* Shipping address {{ shipping_address }}
* Additional info {{ additional_info }}
* Social sharing URL {{ social_sharing_url }}
* Referral link {{ referral link }}

### Referral email email

This email is sent to your customer when another customer purchases through their unique referral link.

**Available payment variables:**

* Referral amount {{ referral_amount }}
* Referral link {{ referral_link }}

### Refund confirmation email

This email is sent to your customer should their refund be refunded.

**Available email variables:**

* Transaction ID (required) {{ transaction_id }}
* Amount refunded (required) {{ amount_refunded }}
* Refund billing statement text (required) {{ refund_billing_statement_text }}
* Date of charge {{ date_of_charge }}
* Date refunded {{ date_refunded }}

## Recommended setup (MailChimp)

Using MailChimp to generate your custom email templates allows for the best of both worlds: a friendly, WYSIWYG editor paired with the ability to export your template to solid email HTML with a single click.

There's no cost to use MailChimp to design and generate your custom email HTML, but you'll need to [sign up for an account](https://login.mailchimp.com/signup?) before getting started.

Once you're signed up, you can follow the step-by-step instructions below to create your custom email HTML:

1. Click ```Templates``` from the top navigation bar
2. Click the ```Create Template``` button in the top right of the page
3. Brose the various available template themes. Once you find that fits your needs, select it and you'll be taken to a screen where you can further customize the look and feel of the email.
4. Once you've customized the email with your desired styling and copy, click on ```Save and Exit``` in the bottom right corner to complete the customization process.
5. To download the email HTML, click on the select ```Export as HTML``` from the drop down menu as shown below. That's it!

![Export as HTML button](https://s3-us-west-2.amazonaws.com/custom-checkout/html-export.png)

## Advanced setup (Custom email HTML)

Email HTML is tricky to work with, so we suggest that most people use MailChimp (or a similar service) to generate their email HTML.

If you'd like to venture into the wide world of completely custom email HTML, we suggest using some of the following open source resources as a starting point:

* [Open Source Email Templates from sendwithus](https://www.sendwithus.com/resources/templates)
* [Email Blueprints from MailChimp](http://templates.mailchimp.com/)
* [Transactional email templates from Mailgun](https://github.com/mailgun/transactional-email-templates)


## Delivery of your custom HTML


Once your HTML is ready, please attach the ```.html``` files to an email and send them our way via lebel@tilt.com. Unfortunately, we're unable to work with forwarded emails, so please make sure to attach your email as an html file to ensure the quickest possible turnaround time.

When we receive them, we'll fill in any applicable custom variables, add them to your campaign, and send you a reply when they're live!