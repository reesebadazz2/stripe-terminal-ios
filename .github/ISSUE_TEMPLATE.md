<!--
Please only file issues here that you believe represent actual bugs or feature requests for the Stripe Terminal iOS SDK.

If you're having general trouble with your Stripe integration, please reach out to support using the form at https://support.stripe.com/ (preferred) or via email to support-terminal@stripe.com.

Otherwise, to make it easier to diagnose your issue, please fill out the following:
-->

## Summary
<!-- A simple summary of the problems you're having. -->

## Code to reproduce
<!-- If possible, please include a brief piece of code (or ideally, a link to an example project) demonstrating the problem you're having. -->

## iOS version
<!-- //
//  PKPaymentAuthorizationViewController+Stripe_Blocks.swift
//  StripeiOS
//
//  Created by Ben Guo on 4/19/16.
//  Copyright © 2016 Stripe, Inc. All rights reserved.
//

import ObjectiveC
import PassKit

typealias STPApplePayPaymentMethodHandlerBlock = (STPPaymentMethod, @escaping STPPaymentStatusBlock)
    -> Void
typealias STPPaymentCompletionBlock = (STPPaymentStatus, Error?) -> Void
typealias STPPaymentAuthorizationBlock = (PKPayment) -> Void

typealias STPApplePayShippingMethodCompletionBlock = (
    PKPaymentAuthorizationStatus, [PKPaymentSummaryItem]?
) -> Void
typealias STPApplePayShippingAddressCompletionBlock = (
    PKPaymentAuthorizationStatus, [PKShippingMethod]?, [PKPaymentSummaryItem]?
) -> Void

typealias STPPaymentAuthorizationStatusCallback = (PKPaymentAuthorizationStatus) -> Void


## Installation method
<!-- How did you install our SDK? -->

## SDK version
<!--
What version of our SDK are you using? You can find this by either looking at your `Podfile.lock` (if you're using Cocoapods), your `Cartfile.resolved` (if you're using Carthage).
 -->

## Other information
<!-- Anything else you can include that'll make it easier for us to help you! -->
