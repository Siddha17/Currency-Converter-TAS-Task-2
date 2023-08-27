# Currency-Converter-TAS-Task-2
def currency_converter(amount,exchange_rate):
    converted_amount = amount * exchange_rate
    return converted_amount
amount = float(input("Enter the amount in your currency:"))
source_currency = input("Enter the source currency:").upper()
target_currency = input("Enter the target currency:").upper()

exchange_rates = {
      "USD":{
           "EUR":0.85,
           "GBP":0.72,
           },
           "EUR":{
               "USD":1.18,
               "GBP":0.84,
               },
        }

if source_currency in exchange_rates and target_currency in exchanges_rates[source_currency]:
exchange_rate = exchange_rates[source_currency][target_currency]
converted_amount = exchange_rates[source_currency][target_currency]
converted_amount = curency_converter(amount,exchange_rate)
print(f"The converted amount from {source_currency} to {target_currency} is: {converted_amount}")
else:
    print("Exchange rate not available for the specified currencies.")
    














