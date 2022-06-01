# Lottery API

- sell lottery ticket
- update lottery ticket
- delete lottery ticket
- get all tickets
- get ticket by id
- bulk buy (user can buy multiple tickets at once)
- raffle draw

Ticket:

- number (unique)
- usernames
- price
- timestamp

Routes:

- /tickets/t/:ticketId GET find single ticket
- /tickets/t/:ticketId PATCH update ticket by id
- /tickets/t/:ticketId DELETE delete ticket by id
- /tickets/u/:username GET finds tickets for a given user
- /tickets/u/:username PATCH update tickets for a given user
- /tickets/u/:username DELETE delete all tickets for a given user
- /tickets/sell - create tickets
- /tickets/bulk - bulk sell tickets
- /tickets/draw
- /tickets - find all tickets
