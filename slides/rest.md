### Rest

| Verbo  | Padrão URL                | Ação|
| ------ | :-----------------------: | --- |
| GET    | /model(.:format)          | model#index|
| GET    | /model/new(.:format)      | model#new|
| POST   | /model(.:format)          | model#create|
| GET    | /model/:id/edit(.:format) | model#edit|
| PATCH  | /model/:id(.:format)      | model#update|
| PUT    | /model/:id(.:format)      | model#update|
| GET    | /model/:id(.:format)      | model#show|
| DELETE | /model/:id(.:format)      | model#destroy|
