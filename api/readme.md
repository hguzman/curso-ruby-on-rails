# API

## Incluir un modelo en un JSON

```
json_data = @user.transactions.map do |transaction|
  transaction.as_json(include: :users)
end
render json: { transactions: json_data }
```
