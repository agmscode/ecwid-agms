## Agms Authorize.net Bridge Mapping

### Request

| Agms				| Authnet 				| Remarks 						|
| ----------------	| --------------------- | ----------------------------- |
| 					| x_fp_hash 			| Not present in Agms 			|
| 					| x_fp_sequence			| Not present in Agms 			|
|					| x_fp_ timestamp		| Not present in Agms			|
| GatewayUserName 	| x_login				| Mapped Directly				|
| TransactionType	| x_type				| Mapped Modified				|
| Amount			| x_amount				| Mapped Directly				|
|					| x_show_form			| Not present in Agms			|
| 					| x_relay_ response 	| Not present in Agms			|
| 					| x_recurring_billing	| Not Mapped					|
| 					| x_currency_code		| Added default value of USD	|
| OrderID			| x_invoice_num			| Mapped Directly				|
| OrderDescription	| x_description			| Mapped Directly				|
| FirstName			| x_first_name			| Mapped Directly				|
| LastName			| x_last_name			| Mapped Directly				|
| Company			| x_company				| Mapped Directly				|
| Address			| x_address				| Mapped Directly				|
| City				| x_city				| Mapped Directly				|
| State				| x_state				| Mapped Directly				|
| Zip				| x_zip					| Mapped Directly				|
| Country			| x_country				| Mapped Directly				|
| Phone				| x_phone				| Mapped Directly				|
| Fax				| x_fax					| Mapped Directly				|
| Email				| x_email				| Mapped Directly				|
|					| x_cust_id				| Not Mapped					|
| ShippingFirstName	| x_ship_to_first_name	| Mapped Directly				|
| ShippingLastName	| x_ship_to_last_name	| Mapped Directly				|
| ShippingCompany	| x_ship_to_company		| Mapped Directly				|
| ShippingAddress	| x_ship_to_address		| Mapped Directly				|
| ShippingCity		| x_ship_to_city		| Mapped Directly				|
| ShippingState		| x_ship_to_state		| Mapped Directly				|
| ShippingZip		| x_ship_to_zip			| Mapped Directly				|
| ShippingCountry	| x_ship_to_country		| Mapped Directly				|
| Tax				| x_tax					| Mapped Directly				|
| Shipping			| x_freight				| Mapped Directly				|
| 					| x_duty				| Not Mapped					|
| 					| x_tax_exempt			| Not Mapped					|
| PONumber			| x_po_num				| Mapped Directly				|
| PaymentType		| x_method				| Mapped Modified				|
| IPAddress			| x_customer_ip			| Mapped Directly				|


### Response

| Agms				| Authnet 				| Remarks 						|
| ----------------	| --------------------- | ----------------------------- |
| STATUS_CODE		| x_response_code		| Mapped Modified				|
| 					| x_response_reason_code| Not Mapped					|
| STATUS_MSG		| x_response_reason_text| Mapped Directly				|
| AUTH_CODE			| x_auth_code			| Mapped Directly				|
| AVS_CODE			| x_avs_code			| Mapped Directly				|
| TRANS_ID			| x_trans_id			| Mapped Directly				|
|					| x_invoice_num			| Not Mapped					|
|					| x_description			| Not Mapped					|
| 					| x_amount				| Not Mapped					|
| 					| x_method				| Not Mapped					|
| 					| x_type				| Not Mapped					|
| 					| x_account_number		| Not Mapped					|
| 					| x_card_type			| Not Mapped					|
| 					| x_split_tender_id		| Not Mapped					|
| 					| x_prepaid_requested_amount| Not Mapped				|
| 					| x_prepaid_balance_on_card| Not Mapped					|
| 					| x_cust_id				| Not Mapped					|
| 					| x_first_name			| Not Mapped					|
| 					| x_last_name			| Not Mapped					|
| 					| x_company				| Not Mapped					|
| 					| x_address				| Not Mapped					|
| 					| x_city				| Not Mapped					|
| 					| x_state				| Not Mapped					|
| 					| x_zip					| Not Mapped					|
| 					| x_country				| Not Mapped					|
| 					| x_phone				| Not Mapped					|
| 					| x_fax					| Not Mapped					|
| 					| x_email				| Not Mapped					|
| 					| x_ship_to_first_name	| Not Mapped					|
| 					| x_ship_to_last_name	| Not Mapped					|
| 					| x_ship_to_company		| Not Mapped					|
| 					| x_ship_to_address		| Not Mapped					|
| 					| x_ship_to_city		| Not Mapped					|
| 					| x_ship_to_state		| Not Mapped					|
| 					| x_ship_to_zip			| Not Mapped					|
| 					| x_ship_to_country		| Not Mapped					|
| 					| x_tax					| Not Mapped					|
| 					| x_freight				| Not Mapped					|
| 					| x_duty				| Not Mapped					|
| 					| x_tax_exempt			| Not Mapped					|
| 					| x_po_num				| Not Mapped					|
| 					| x_MD5_Hash			| Not Mapped					|
| 					| x_cvv2_resp_code		| Not Mapped					|
| 					| x_cavv_response		| Not Mapped					|




