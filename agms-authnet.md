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



