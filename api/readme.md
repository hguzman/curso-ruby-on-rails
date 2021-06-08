# API REST

[Build a RESTful JSON API With Rails 5 - Part One](https://www.digitalocean.com/community/tutorials/build-a-restful-json-api-with-rails-5-part-one)

## Incluir un modelo en un JSON

```
json_data = @user.transactions.map do |transaction|
  transaction.as_json(include: :users)
end
render json: { transactions: json_data }
```
