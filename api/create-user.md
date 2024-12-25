Invoke-RestMethod -Uri "http://localhost:8080/api/auth/local/register" `
>>   -Method Post `
>>   -Headers @{
>>     "Content-Type" = "application/json";
>>     "Authorization" = "Bearer 1e800f12f4e812b6303d89a41afb2555b47f578da09eff1f8cc68d7b2a0aa91e634d9a5eb61ff7e473b8c5b8b5e7750d80b4de88d4772bde44a0e170e42329db7cc58f9ebcbd62d78ab9aa050f3a0526c81a7c84d1d745cc9b3bb55e43820393fb344ee095b90d66147aa83d2d317f2643ee31d5f0345612ddbc8467431a8e31"
>>   } `
>>   -Body '{
>>     "username": "Prim",
>>     "email": "nwrprim555@email.com",
>>     "password": "Prim@123"
>>   }'
