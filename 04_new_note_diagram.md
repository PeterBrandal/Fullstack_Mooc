sequenceDiagram

participant browser
participant server

(assume the DOM has been loaded)

browser->>server: "Save" input from user
server extracts data from input

server->>browser: appends new "<li>" element with input-data in the Notes list.