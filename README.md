# Sharetribe Flex customize features

### Wishlist

A guest can store their favorite cottages in their wishlist, so they can easily find
them later. If guest is not logged in when clicking Add to Wishlist button, it should be required to
log in first.

Time works: 5 hours

### Sorts result by review average

Firstly, we can run an event polling in a separate Node.js app to update review average to listings.
This review average is stored on metadata of each listing. Then, we can use it on front-end page

Script file: events-api-script/notify-new-rating.js

Time work: 3 hours

### Instant booking

Customize the `flex-default-process` transaction default of Sharetribe by remove pre-authorization.
And add three actions: stripe-confirm-payment-intent, stripe-capture-payment-intent and accept-booking

Time work: 6 hours


