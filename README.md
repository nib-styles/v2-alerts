# @nib-styles/alerts

Alerts for nib pages.

## Installation

    npm install --save @nib-styles/alerts

## Usage

There are four types of alerts:
- Error
- Success
- Warning
- Info

Alerts have a title and may also have a message:

alert with a title:

    <div class="alert alert--error">
      <div class="alert__title">We're sorry, due to too many invalid login attempts your account is locked</div>
    </div>

alert with a title and a message:

    <div class="alert alert--error">
      <div class="alert__title">We're sorry, due to too many invalid login attempts your account is locked</div>
      <div class="alert__message">You will be able to try again in 00:30 minutes.</div>
    </div>

## Changelog

3.0.0 - updated breaking version of @nib-styles/v2-icons