---
layout: docs
title: Account and subscriptions
---

<div id="doc-header" class="doc-header text-center">
    <h1 class="doc-title"><i class="icon fa fa-paper-plane"></i> {{ title }}</h1>
</div>
<div class="doc-body row">
    <div class="doc-content col-md-9 col-12 order-1">
        <div class="content-inner">
            <section id="pro-section" class="doc-section">
                <h2 class="section-title">Pro Subscription Payments</h2>
                <div class="section-block">
                    <p>Payments are taken by Chargebee to manage the subscription details, and ultimately Stripe for taking card data.
                    </p>
                </div>
            </section>
            <section id="trial-section" class="doc-section">
                <h2 class="section-title">Trial Subscription</h2>
                <div class="section-block">
                    <p>The Notist Free plan gives a limited set of features for speakers who do a few presentations per year. When you initially sign up you are granted a 15 day trial subscription to our Pro Plan, which enables additional features and removes limits.</p>
                    <p>After your trial ends you will be downgraded to the Free plan.
                    </p>
                </div>
            </section>
            <section id="export-section" class="doc-section">
                <h2 class="section-title">Data Export from Your Account</h2>
                <div class="section-block">
                    <p>We are very keen that your data is not locked up inside our platform. It belongs to you and you should be able to keep a backup of it, or take it somewhere else in future in an easily usable manner. So we will be offering full export of data held in Notist.
<p>
During the beta data export is not yet available, essentially because some features are in flux that would require changes to any export scripts. We also want to work with beta testers to make sure the exports are useful. We'll add this in the coming weeks.
<p>
You can already access and use a lot of the data via JSON, from publicly accessible pages. For example, you can add .json to the end of any profile page URL.
<p>
<code>https://noti.st/username.json</code>
<p>
For a presentation page, remove the slug and add .json to the presentation ID:
<p>
<code>https://noti.st/username/aAbAcC.json</code>
<p>
And similarly for an event:
<p>
<code>https://noti.st/events/aAbAcC.json</code>
                </div>
            </section>
        </div>
    </div>
    <div class="doc-sidebar col-md-3 col-12 order-0 d-none d-md-flex">
        <div id="doc-nav" class="doc-nav">  
                <nav id="doc-menu" class="nav doc-menu flex-column sticky">
                    <a class="nav-link scrollto" href="#pro-section">Pro Subscription Payments</a>
                    <a class="nav-link scrollto" href="#trial-section">Trial Subscription</a>
                    <a class="nav-link scrollto" href="#export-section">Exporting</a>
                </nav>
        </div>
    </div>
</div>