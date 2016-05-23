Alerts v2
=========

Alerts for nib pages. There are two types of alerts - with and without a title.

Alerts with a title:

    <div class="alert alert--error">
      <div class="alert__title">We're sorry, due to too many invalid login attempts your account is locked</div>
      <div class="alert__message">You will be able to try again in 00:30 minutes.</div>
    </div>

Alerts without a title:
    <div class="alert alert--error">
      <div class="alert__message--single">Alert message without title 18pt light Roboto</div>
    </div>

This component contains the following modifiers:

    alert--error       // Error message
    alert--success     // Success message
    alert--warning     // Alert message
    alert--info        // Information message

Always use both the base and modifier classes:

    alert alert--error

## Dependencies

nibdings icon font from [nib-styles/v2-icons](https://github.com/nib-styles/v2-icons)
