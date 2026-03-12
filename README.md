# CYBS

## Tables

- [pay_v_cybs_miscellaneous_detail](#pay_v_cybs_miscellaneous_detail)
- [pay_v_cybs_miscellaneous_detail_exception](#pay_v_cybs_miscellaneous_detail_exception)
- [pay_v_cybs_reconciliation_abnormal](#pay_v_cybs_reconciliation_abnormal)
- [pay_v_cybs_reconciliation_detail](#pay_v_cybs_reconciliation_detail)
- [pay_v_cybs_reconciliation_detail_exception](#pay_v_cybs_reconciliation_detail_exception)
- [pay_v_cybs_reconciliation_normal](#pay_v_cybs_reconciliation_normal)

---

## pay_v_cybs_miscellaneous_detail

<small>79 columns</small>

| Column | Description |
| --- | --- |
| `id` |  |
| `record_id` |  |
| `record_date` |  |
| `record_type` |  |
| `dispute_amount_indicator` | Standardized monetary amount for financial reporting. |
| `record_reference_number` |  |
| `record_reason_code` |  |
| `record_reference_information` |  |
| `acquirer_id` |  |
| `acquirer_name` |  |
| `psp_id` |  |
| `psp_name` |  |
| `group_id` |  |
| `group_name` |  |
| `merchant_id` |  |
| `merchant_name` |  |
| `store_id` |  |
| `store_name` |  |
| `store_mcc` |  |
| `terminal_id` |  |
| `merchant_nation` |  |
| `merchant_city` |  |
| `merchant_txn_time` |  |
| `system_txn_time` |  |
| `txn_pay_time` |  |
| `api_type` |  |
| `txn_type` |  |
| `payment_brand` |  |
| `payment_method_variant` |  |
| `merchant_txn_id` |  |
| `merchant_order_reference` |  |
| `system_txn_id` |  |
| `psp_txn_id` |  |
| `original_merchant_txn_id` |  |
| `original_system_txn_id` |  |
| `original_psp_txn_id` |  |
| `card_number` |  |
| `funding_type` |  |
| `product_id` |  |
| `product_type_id` |  |
| `issuer_country` |  |
| `merchant_local_amt` |  |
| `local_tips_amt` |  |
| `local_surcharge_fee_amt` |  |
| `local_capture_amt` |  |
| `merchant_local_curr` |  |
| `rateof_localto_txn` |  |
| `merchant_txn_amt` |  |
| `tips_amount` | Standardized monetary amount for financial reporting. |
| `surcharge_fee_amt` |  |
| `merchant_capture_amt` |  |
| `merchant_txn_curr` |  |
| `user_billing_amt` |  |
| `user_billing_curr` |  |
| `eci` |  |
| `txn_initiation_mode` |  |
| `linkpay_order_id` |  |
| `txn_status` |  |
| `system_result_code` |  |
| `psp_result_code` |  |
| `psp_authorization_code` |  |
| `crossborder_flag` |  |
| `psp_arn` |  |
| `psp_settlement_date` |  |
| `psp_txn_amt` |  |
| `psp_txn_curr` |  |
| `direct_fx_rate` |  |
| `psp_sttl_amt` |  |
| `psp_discount_amt` |  |
| `acquirer_discount_amt` |  |
| `psp_sttl_curr` |  |
| `ratefor_psp_txnto_sttl` |  |
| `psp_interchange_fee` |  |
| `psp_vat_amount` | Standardized monetary amount for financial reporting. |
| `psp_wht_amount` | Standardized monetary amount for financial reporting. |
| `psp_net_sttl_amt` |  |
| `created_at` |  |
| `updated_at` |  |
| `batch_date` |  |


---

## pay_v_cybs_miscellaneous_detail_exception

<small>8 columns</small>

| Column | Description |
| --- | --- |
| `id` |  |
| `record_id` |  |
| `raw_content` |  |
| `error_message` |  |
| `line_number` |  |
| `created_at` |  |
| `updated_at` |  |
| `batch_date` |  |


---

## pay_v_cybs_reconciliation_abnormal

<small>40 columns</small>

| Column | Description |
| --- | --- |
| `id` |  |
| `batch_id` |  |
| `transaction_id` |  |
| `transaction_amount` | Standardized monetary amount for financial reporting. |
| `transaction_currency` | Standardized ISO 3-letter currency code. |
| `transaction_status` |  |
| `transaction_type` |  |
| `transaction_created_at` |  |
| `transaction_request_id` |  |
| `transaction_request_amount` | Standardized monetary amount for financial reporting. |
| `transaction_request_currency` | Standardized ISO 3-letter currency code. |
| `acquirer_settlement_id` |  |
| `acquirer_settlement_merchant_txn_id` |  |
| `acquirer_settlement_merchant_txn_time` |  |
| `acquirer_settlement_system_txn_time` |  |
| `acquirer_settlement_txn_type` |  |
| `acquirer_settlement_merchant_txn_amt` |  |
| `acquirer_settlement_merchant_txn_curr` |  |
| `acquirer_settlement_txn_status` |  |
| `acquirer_settlement_merchant_sttl_amt` |  |
| `acquirer_settlement_merchant_sttl_curr` |  |
| `acquirer_settlement_funding_type` |  |
| `acquirer_settlement_crossborder_flag` |  |
| `acquirer_settlement_payment_brand` |  |
| `psp_reconciliation_id` |  |
| `psp_reconciliation_merchant_txn_id` |  |
| `psp_reconciliation_merchant_txn_time` |  |
| `psp_reconciliation_system_txn_time` |  |
| `psp_reconciliation_txn_type` |  |
| `psp_reconciliation_merchant_txn_amt` |  |
| `psp_reconciliation_merchant_txn_curr` |  |
| `psp_reconciliation_txn_status` |  |
| `psp_reconciliation_funding_type` |  |
| `psp_reconciliation_crossborder_flag` |  |
| `psp_reconciliation_payment_brand` |  |
| `error_message` |  |
| `completion_time` |  |
| `created_at` |  |
| `updated_at` |  |
| `batch_date` |  |


---

## pay_v_cybs_reconciliation_detail

<small>73 columns</small>

| Column | Description |
| --- | --- |
| `id` |  |
| `record_id` |  |
| `acquirer_id` |  |
| `acquirer_name` |  |
| `psp_id` |  |
| `psp_name` |  |
| `group_id` |  |
| `group_name` |  |
| `merchant_id` |  |
| `merchant_name` |  |
| `store_id` |  |
| `store_name` |  |
| `store_mcc` |  |
| `terminal_id` |  |
| `merchant_nation` |  |
| `merchant_city` |  |
| `merchant_txn_time` |  |
| `system_txn_time` |  |
| `txn_pay_time` |  |
| `api_type` |  |
| `txn_type` | Transaction type:Payment/Refund | |
| `payment_brand` | Card Scheme:Visa/Mastercard | |
| `payment_method_variant` |  |
| `merchant_txn_id` |  |
| `merchant_order_reference` |  |
| `system_txn_id` |  |
| `psp_txn_id` |  |
| `original_merchant_txn_id` |  |
| `original_system_txn_id` |  |
| `original_psp_txn_id` |  |
| `card_number` | Masked card number | |
| `funding_type` | Card funding type:Debit/Credit | |
| `product_id` |  |
| `product_type_id` |  |
| `issuer_country` | Card issuer country (3-letter country code) | |
| `merchant_local_amt` |  |
| `local_tips_amt` |  |
| `local_surcharge_fee_amt` |  |
| `local_capture_amt` |  |
| `merchant_local_curr` |  |
| `rateof_localto_txn` |  |
| `merchant_txn_amt` |  |
| `tips_amount` | Standardized monetary amount for financial reporting. |
| `surcharge_fee_amt` |  |
| `merchant_capture_amt` |  |
| `merchant_txn_curr` |  |
| `user_billing_amt` |  |
| `user_billing_curr` |  |
| `eci` |  |
| `txn_initiation_mode` |  |
| `linkpay_order_id` |  |
| `txn_status` |  |
| `system_result_code` |  |
| `psp_result_code` |  |
| `psp_authorization_code` |  |
| `crossborder_flag` | Indicates whether the card is domestic or international:Domestic / International | |
| `psp_arn` |  |
| `psp_settlement_date` |  |
| `psp_txn_amt` |  |
| `psp_txn_curr` |  |
| `direct_fx_rate` |  |
| `psp_sttl_amt` |  |
| `psp_discount_amt` |  |
| `acquirer_discount_amt` |  |
| `psp_sttl_curr` |  |
| `ratefor_psp_txnto_sttl` |  |
| `psp_interchange_fee` |  |
| `psp_vat_amount` | Standardized monetary amount for financial reporting. |
| `psp_wht_amount` | Standardized monetary amount for financial reporting. |
| `psp_net_sttl_amt` |  |
| `created_at` |  |
| `updated_at` |  |
| `batch_date` |  |


---

## pay_v_cybs_reconciliation_detail_exception

<small>8 columns</small>

| Column | Description |
| --- | --- |
| `id` |  |
| `record_id` |  |
| `raw_content` |  |
| `error_message` |  |
| `line_number` |  |
| `created_at` |  |
| `updated_at` |  |
| `batch_date` |  |


---

## pay_v_cybs_reconciliation_normal

<small>39 columns</small>

| Column | Description |
| --- | --- |
| `id` |  |
| `batch_id` |  |
| `transaction_id` |  |
| `transaction_amount` | Standardized monetary amount for financial reporting. |
| `transaction_currency` | Standardized ISO 3-letter currency code. |
| `transaction_status` |  |
| `transaction_type` |  |
| `transaction_created_at` |  |
| `transaction_request_id` |  |
| `transaction_request_amount` | Standardized monetary amount for financial reporting. |
| `transaction_request_currency` | Standardized ISO 3-letter currency code. |
| `acquirer_settlement_id` |  |
| `acquirer_settlement_merchant_txn_id` |  |
| `acquirer_settlement_merchant_txn_time` |  |
| `acquirer_settlement_system_txn_time` |  |
| `acquirer_settlement_txn_type` |  |
| `acquirer_settlement_merchant_txn_amt` |  |
| `acquirer_settlement_merchant_txn_curr` |  |
| `acquirer_settlement_txn_status` |  |
| `acquirer_settlement_merchant_sttl_amt` |  |
| `acquirer_settlement_merchant_sttl_curr` |  |
| `acquirer_settlement_funding_type` |  |
| `acquirer_settlement_crossborder_flag` |  |
| `acquirer_settlement_payment_brand` |  |
| `psp_reconciliation_id` |  |
| `psp_reconciliation_merchant_txn_id` |  |
| `psp_reconciliation_merchant_txn_time` |  |
| `psp_reconciliation_system_txn_time` |  |
| `psp_reconciliation_txn_type` |  |
| `psp_reconciliation_merchant_txn_amt` |  |
| `psp_reconciliation_merchant_txn_curr` |  |
| `psp_reconciliation_txn_status` |  |
| `psp_reconciliation_funding_type` |  |
| `psp_reconciliation_crossborder_flag` |  |
| `psp_reconciliation_payment_brand` |  |
| `completion_time` |  |
| `created_at` |  |
| `updated_at` |  |
| `batch_date` |  |

