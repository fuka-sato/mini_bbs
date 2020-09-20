# mini_bbs
## membersテーブル
|Column|Type|Options|
|------|----|-------|
|name|varchar|null: false|
|email|varchar|null: false|
|password|varchar|null: false|
|picture|varchar||
|modified|timestanp||

## postsテーブル
|Column|Type|Options|
|------|----|-------|
|message|text|null: false|
|member_id|int|null: false|
|reply_message_id|int|null: false|
|modified|timestanp||