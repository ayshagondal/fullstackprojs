```mermaid
sequenceDiagram
  participant browser
  participant server

browser ->>server: request payload {content: "owo", date: "2024-07-21T05:02:01.364Z"}
activate server
server -->> browser : [{"message":"note created"}]
deactivate server
```
