<h1>Bra att veta</h1>

Följande **JSON API** krävs för att sökfunktionen ska fungera överhuvudtaget:

https://fj5sznxet5.execute-api.us-east-1.amazonaws.com/development/dictionary-contents

Länken innehåller en databas över alla tillgängliga söktermer, deras uttalanden och definition och är enkel att redigera i Amazon API Gateway (AWS). Note to self, man går via [namn] -> Resources -> [/namn] -> GET -> Intergration Response -> (utöka rutan) -> Mapping templates -> application/json
