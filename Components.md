Each component is a logical or phisical separation of different units 
Server, Messaging, UE, caching 
point to note is not every code separation, logical separation, how different components work together


In Single Tier applications, UE , Backend, storage, messaging, caching all reside on same system like MS office 
- Advantage of single tier applications is no network latency and that helps in software performance

need for 2 tier application '
- it is useful for cases like productivity app, todo app , why and how is unclear, why can't they work in single machine ? I feel availability
- cause even when code is accessed by thirdparty its not much of a security threat
- just because there is no big time red flag on missing security, we need not go for 2 tier, i think availability is the thing 
- browser and mobile games, data comes to UE only at start and goes to server only to persist
