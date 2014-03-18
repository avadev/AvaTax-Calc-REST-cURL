AvaTax-REST-cURL
=====================

This is a set of cURL sample requests and expected responses demonstrating the [AvaTax REST API](http://developer.avalara.com/api-docs/rest) methods:
 [tax/get POST](http://developer.avalara.com/api-docs/rest/tax/post/), [tax/get GET](http://developer.avalara.com/api-docs/rest/tax/get), [tax/cancel POST](http://developer.avalara.com/api-docs/rest/tax/cancel), and [address/validate GET](http://developer.avalara.com/api-docs/rest/address-validation).
 
 For more information on the use of these methods and the AvaTax product, please visit our [developer site](http://developer.avalara.com/) or [homepage](http://www.avalara.com/)
 
Contents:
----------
 
<table>
<th colspan="2" align=left>Sample Files</th>
<tr><td>CancelTaxTest.txt</td><td>Demonstrates the <a href="http://developer.avalara.com/api-docs/rest/tax/cancel">CancelTax</a> method used to <a href="http://developer.avalara.com/api-docs/api-reference/canceltax">void a document</a>.</td></tr>
<tr><td>EstimateTaxTest.txt</td><td>Demonstrates the <a href="http://developer.avalara.com/api-docs/rest/tax/get">EstimateTax</a> method used for product- and line- indifferent tax estimates.</td></tr>
<tr><td>GetTaxTest.txt</td><td>Demonstrates the <a href="http://developer.avalara.com/api-docs/rest/tax/post">GetTax</a> method used for product- and line- specific <a href="http://developer.avalara.com/api-docs/api-reference/gettax">calculation</a>.</td></tr>
<tr><td>PingTest.txt</td><td>Uses a hardcoded EstimateTax call to test connectivity and credential information.</td></tr>
<tr><td>ValidateAddressTest.txt</td><td>Demonstrates the <a href="http://developer.avalara.com/api-docs/rest/address-validation">ValidateAddress</a> method to <a href="http://developer.avalara.com/api-docs/api-reference/address-validation">normalize an address</a>.</td></tr>
<th colspan="2" align=left>Other Files</th>
<tr><td>.gitattributes</td><td>-</td></tr>
<tr><td>.gitignore</td><td>-</td></tr>
<tr><td>LICENSE.md</td><td>-</td></tr>
<tr><td>README.md</td><td>-</td></tr>
</table>

Dependencies:
-----------
- Ruby 1.9.2 or later

Requirements:
----------
- Make sure to install any required gems by navigating to the root directory in the command line and running "bundle install".
- Authentication requires an valid **Account Number** and **License Key**, which should be entered in the test file (e.g. GetTaxTest.rb) you would like to run.
- If you do not have an AvaTax account, a free trial account can be acquired through our [developer site](http://developer.avalara.com/api-get-started)


AvaTax-REST-cURL
=====================

Set of cURL sample requests and expected responses for the AvaTax tax calcluation REST API

You will need an AvaTax account to run these samples - you can sign up for a free trial account here: http://developer.avalara.com/api-get-started

These samples cover the following REST resources:

address/validate (http://developer.avalara.com/api-docs/rest/address-validation)

tax/get GET (http://developer.avalara.com/api-docs/rest/tax/get)

tax/get POST (http://developer.avalara.com/api-docs/rest/tax/post)

tax/cancel (http://developer.avalara.com/api-docs/rest/tax/cancel)


For more information on calculating tax with AvaTax and recommended use cases, please see our developer documentation at http://developer.avalara.com/
