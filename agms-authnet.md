## Agms Authorize.net Bridge Mapping

### Request

| Agms				| Authnet 			| Remarks 						|
| ----------------	| -----------------	| ----------------------------- |
| 					| x_fp_hash 		| Not present in Agms 			|
| 					| x_fp_sequence		| Not present in Agms 			|
|					| x_fp_ timestamp	| Not present in Agms			|
| GatewayUserName 	| x_login			| Mapped Directly				|
| TransactionType	| x_type			| Mapped Modified				|
| Amount			| x_amount			| Mapped Directly				|
