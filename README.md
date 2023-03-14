# GraphQL-example

## Query Examples and you can check more

query getAllEvents {
events{
id
title
}
}

query getEvent {
event(id:1){
id
title
}
}

query getAllUsers {
users{
id
username
}
}

query getUser {
user(id:1){
id
username
}
}

query getAllLocations {
locations{
id
name
}
}

query getLocation {
location(id:1){
id
name
}
}

query getAllParticipants {
participants{
id
user_id
event_id
}
}

query getParticipant {
participant(id:1){
id
user_id
event_id
}
}
