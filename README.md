<!-- only for core API change here, DONT add the client-specific changes. -->
<p class="changelog-title"><span><strong>NEW API CHANGELOG INFORMATION for</strong></span><span class="pull-right"> November 2023</span></p>

---
<p class="changelog-title"><span><strong>Added Wish list / Favorite Api </strong></span><span class="pull-right"> April 2022</span></p>

---
<p class="changelog-title"><span><strong>Single Sign on For Enterpise Clients and Event Triggers</strong></span><span class="pull-right"> January 2022</span></p>

---

<p class="changelog-title"><span><strong>Added support for meta items</strong></span><span class="pull-right"> December 2021</span></p>

---

<p class="changelog-title"><span><strong>Bug fixes</strong></span><span class="pull-right"> September 2021</span></p>

---

<p class="changelog-title"><span><strong>Added Support for Merchant Sub Accounts</strong></span><span class="pull-right"> July 2021</span></p>

---

<p class="changelog-title"><span><strong>Added User Groups at permission profile Api</strong></span><span class="pull-right"> June 2021</span></p>

---


<p class="changelog-title"><span><strong>Merhant Info Api update to include user profile media</strong></span><span class="pull-right"> January 2021</span></p>

---


<p class="changelog-title"><span><strong>Items with translations to show the correct data when called via GET Item APIs and cart item partial refunds</strong></span><span class="pull-right"> Feb 2021</span></p>


---


<p class="changelog-title"><span><strong>Items with translations to show the correct data when called via GET Item APIs</strong></span><span class="pull-right"> December 2020 </span></p>

---


<p class="changelog-title"><span><strong>System enhancement of ‘read’ flag to recognize the action of a sub-account after reading a new message</strong></span><span class="pull-right"> November 2020 </span></p>


---


<p class="changelog-title"><span><strong>Added Country Level and User Location Settings</strong></span><span class="pull-right"> September 2020 </span></p>

---


<p class="changelog-title"><span><strong>Added Partial Refund</strong></span><span class="pull-right"> August 2020</span></p>

---


<p class="changelog-title"><span><strong>URL shortening APIs added</strong></span><span class="pull-right"> 4 May 2020</span></p>

A new API has been made available to shorten URL slugs of your choice on your marketplace.
* Details are in the API documentation [here](https://apiv2.arcadier.com/?version=latest#4b934939-cd65-4ed0-aee9-3b15de47904b).

---

<p class="changelog-title"><span><strong>Webhook & Event Triggers APIs added</strong></span><span class="pull-right"> 24 April 2020</span></p>

New APIs have been made available to set up event triggers on your marketplace. These event triggers can be hooked to your own webhooks.
* Details are in the API documentation [here](https://apiv2.arcadier.com/?version=latest#cda751b9-e7a4-4d50-b660-72ec9cd4d4f0).

---

<p class="changelog-title"><span><strong>PageSize limitation to 500</strong></span><span class="pull-right">25 February 2020</span></p>

To improve the speed and efficiency of our APIs, the maximum value of pageSize has been limited to 500. 
* [More details here.](https://apiv2.arcadier.com/?version=latest#pagination)
* It is advised to use extra filters when doing searches.
* If the intention is to get 100% of Records, where the number of Records exceeds 500, combine `pageSize` with `pageNumber` and do a couple of API calls.

---

<p class="changelog-title"><span><strong>Item Creation API</strong></span><span class="pull-right">25 February 2020</span></p>

Both Admin and Merchant can use this API:
* [Item Create](https://apiv2.arcadier.com/?version=latest#03d18078-0f46-4c84-b9ff-c464c7853580)
* The Admin can create items on behalf of other merchants.

---

<p class="changelog-title"><span><strong>Transaction History APIs</strong></span><span class="pull-right">7 February 2020</span></p>

Added time filtering query parameters to:
* [Get Transactions History of the marketplace](https://apiv2.arcadier.com/?version=latest#fd876791-d71f-43bd-be02-bfe6bf17747a)

---

<p class="changelog-title"><span><strong>Item Search APIs</strong></span><span class="pull-right">6 February 2020</span></p>

Added sorting query parameters to:
* [Get All Items](https://apiv2.arcadier.com/?version=latest#c06e85df-93f9-446c-a9b2-426296185d0d)
* [Search for items - Params in URL](https://apiv2.arcadier.com/?version=latest#c6d3c581-2556-4cb0-a7f1-daed8733f9fd)
* [Search for items - Params in JSON body](https://apiv2.arcadier.com/?version=latest#61b718db-2d07-4af1-992d-520c0fe259c0)

---
