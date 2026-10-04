<<<<<<< HEAD:docs/Overview/overview.md
# Overview

## Become an Integration Partner

Become a partner to gain access to our APIs. You can then begin developing your Commerce integration.

<HTMLBlock>{`
<a href="https://www.deliverect.com/en/become-a-partner" target="_blank" class="doc-button">▶ Sign up</a>
`}</HTMLBlock>

***

## Build a Commerce Integration

Below are the general steps to integrating our Commerce API

<HTMLBlock>{`
<div class="step-list">
  <div class="step-list-item">
    <div class="step-list-marker step-list-marker--green">1</div>
    <div class="step-list-content">
      <p class="step-list-title">Get an Access Token — <a href="https://developers.deliverect.com/reference/access-token" target="_blank">Get Access Token</a></p>
      <p class="step-list-desc">Retrieve a token granting you access to our endpoints.</p>
    </div>
  </div>
  <div class="step-list-item">
    <div class="step-list-marker step-list-marker--green">2</div>
    <div class="step-list-content">
      <p class="step-list-title">Retrieve Linked Customer Accounts — <a href="https://developers.deliverect.com/v1.1-restaurants/reference/get-linked-accounts" target="_blank">Get Linked Accounts</a></p>
      <p class="step-list-desc">Retrieve the customer accounts linked to your partner account.</p>
    </div>
  </div>
  <div class="step-list-item">
    <div class="step-list-marker step-list-marker--green">3</div>
    <div class="step-list-content">
      <p class="step-list-title">Get Stores — <a href="https://developers.deliverect.com/v3.0-ordering-experience/reference/commerce-get-stores" >Get Stores</a></p>
      <p class="step-list-desc">Retrieve the <code>channelLinkId</code> for a customer account.</p>
    </div>
  </div>
  <div class="step-list-item">
    <div class="step-list-marker step-list-marker--green">4</div>
    <div class="step-list-content">
      <p class="step-list-title">Get Store Menu(s) — <a href="https://developers.deliverect.com/v3.0-ordering-experience/reference/commerce-get-menus" >Get Store Menu(s)</a></p>
      <p class="step-list-desc">Retrieve menus for a given store.</p>
    </div>
  </div>
  <div class="step-list-item">
    <div class="step-list-marker step-list-marker--green">5</div>
    <div class="step-list-content">
      <p class="step-list-title">Create Basket — <a href="https://developers.deliverect.com/v3.0-ordering-experience/reference/commerce-create-basket" >Create Basket</a></p>
      <p class="step-list-desc">Create a basket to begin building the order.</p>
    </div>
  </div>
  <div class="step-list-item">
    <div class="step-list-marker step-list-marker--green">6</div>
    <div class="step-list-content">
      <p class="step-list-title">Update Basket (optional)</p>
      <p class="step-list-desc">Update the basket as needed using the following endpoints:</p>
      <ul class="step-list-sublist">
        <li><a href="https://developers.deliverect.com/v3.0-ordering-experience/reference/update-basket-customer" >Update Customer</a></li>
        <li><a href="https://developers.deliverect.com/v3.0-ordering-experience/reference/update-basket-items" >Update Items</a></li>
        <li><a href="https://developers.deliverect.com/v3.0-ordering-experience/reference/commerce-update-basket-discounts" >Update Discounts</a></li>
        <li><a href="https://developers.deliverect.com/v3.0-ordering-experience/reference/update-basket-fulfillment" >Update Fulfillment</a></li><li><a href="https://developers.deliverect.com/v3.0-ordering-experience/reference/update-basket-charges" >Update Charges</a></li>
        <li><a href="https://developers.deliverect.com/v3.0-ordering-experience/reference/update-basket-payments" >Update Tips</a></li>
        <li><a href="https://developers.deliverect.com/v3.0-ordering-experience/reference/update-donations" >Update Donations</a></li>
      </ul>
    </div>
  </div>
  <div class="step-list-item">
    <div class="step-list-marker step-list-marker--green">7</div>
    <div class="step-list-content">
      <p class="step-list-title">Request Payment (optional) — <a href="https://developers.deliverect.com/v3.0-ordering-experience/reference/request-payment" >Request Payment</a></p>
      <p class="step-list-desc">Only applies for DPAY (Deliverect Pay) payment type.</p>
    </div>
  </div>
  <div class="step-list-item">
    <div class="step-list-marker step-list-marker--green">8</div>
    <div class="step-list-content">
      <p class="step-list-title">Checkout — <a href="https://developers.deliverect.com/v3.0-ordering-experience/reference/commerce-checkout" >Basket Checkout</a></p>
      <p class="step-list-desc">Proceed to checkout and specify the payment method.</p>
    </div>
  </div>
  <div class="step-list-item">
    <div class="step-list-marker step-list-marker--green">9</div>
    <div class="step-list-content">
      <p class="step-list-title">Checkout Status Webhook — <a href="https://developers.deliverect.com/v3.0-ordering-experience/reference/commerce-api-checkout-update" >Basket Checkout Status Webhook</a></p>
      <p class="step-list-desc">Monitor the status of the checkout.</p>
    </div>
  </div>
</div>
`}</HTMLBlock>
=======
---
title: Welcome to readme_sync
hidden: false
privacy:
  view: public
---
<Callout icon="📘" theme="info">
  **Template:**  Delete this callout and edit this page with your content and links.
</Callout>

<Cards>
  {/* Edit the props below to customize these components */}
  <Card title="Quick Start" href="#" icon="fa-duotone fa-rocket-launch">Learn how to get started with our product</Card>

  <Card title="API Reference" href="#" icon="fa-duotone fa-code-simple">Explore endpoints and build your integration</Card>

  <Card title="Build with AI" href="#" icon="fa-duotone fa-sparkles">Use LLM features to automate your workflow</Card>
</Cards>

<br />

## Recent Releases

<Cards>
  <Card isNew kind="tile" title="v2.0 Migration" href="#" icon="fa-duotone fa-magnifying-glass">Everything you need to upgrade</Card>

  <Card kind="tile" title="Webhooks" href="#" icon="fa-duotone fa-bullhorn">Real-time events are now available</Card>

  <Card kind="tile" title="Android SDK" href="#" icon="fa-duotone fa-robot">Our native Android library is out of beta</Card>
</Cards>

<br />

## The Basics

<Cards>
  <Card kind="tile" title="Customize" href="#" icon="fa-duotone fa-brush">Style the widget to match your brand</Card>

  <Card kind="tile" title="Integrations" href="#" icon="fa-duotone fa-arrow-down-left-and-arrow-up-right-to-center">Connect with third-party services</Card>

  <Card kind="tile" title="CLI" href="#" icon="fa-duotone fa-terminal">Manage resources from your terminal</Card>

  <Card kind="tile" title="Security" href="" icon="fa-duotone fa-shield-dog">Learn how we secure your data</Card>

  <Card kind="tile" title="Common Issues" href="" icon="fa-duotone fa-file-circle-info">Troubleshoot common issues</Card>

  <Card kind="tile" title="Sync" href="#" icon="fa-duotone fa-code-compare">Connect to a storage provider</Card>
</Cards>

<br />
>>>>>>> 7e2fcc59add1e763fe2e69625c8b3e60fb695ef4:docs/Getting Started/overview.md
