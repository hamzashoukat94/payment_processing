# payment_processing
Processes a transaction and prevents over-authorization due to additional charges like gratuity.

## Parameters:
- authorization_amount: The initial amount authorized for the transaction.
- purchase_amount: The amount for goods/services.
- incremental_authorizations: List of amounts for successful incremental authorizations.
- voided_transactions: List of amounts for voided transactions.
- grand_total_amount: The total amount for goods/services and any additional charges.
- gratuity_amount: Any additional charge such as gratuity.

## Returns:
- A tuple containing a boolean indicating if the transaction should proceed and a message.
    