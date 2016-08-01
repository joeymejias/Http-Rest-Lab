Login => Receive Token
Method: POST
Data: username; password

Login => Signup
Method: GET

Receive Token => News
Method: GET
Data: Token

News => Repositories
Method: Get
Data: Token

Respositories => Repository News
Method: GET
Data: Token, Respository ID

Repository News => Code
Method: GET
Data: Toke, Repo ID, Path?

Code => Code Sub Directory
Method: GET
Data: Token, Repo ID, Path?

Repository News => Commit
Method: GET
Data: Token, Repo ID, Commit ID
