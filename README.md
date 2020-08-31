# Library-DB-app
This app uses SQL and python to manage the database of a simple library consisting of users, events, and items.


## Project Specifications:
• Library has print books, online books, magazines, scientific journals, CDs, records, etc.
• People can borrow the items from library and return by the due date.
• People may be subject to fines if they do not return items by the due date.
• Library also holds book clubs, book related events, art shows, film screenings, etc.
• Library events are recommended for specific audiences.
• Library events are held on library social rooms.
• People can attend library events for free.
• Library also has personnel and record keeping for personnel.
• Library also keeps records of items (books, etc.) that might be added to library in the future.
• People can sign up for a library account
• People can find an event
• People can when their item’s due date is
• People can check how much they owe the library from overdue fines
• People can pay part or all of what they owe the library
• Items can be checked out for 21 days until it is due. One dollar per day later than the due date will be added to what that person owes the library
• The library application will be designed for library users


## Domain
• Every item has an ID, title, author, edition, year, genre, quantity, number of available
copies.
o quantity is the number of copies the library has of the item regardless of type
(e.g. e-book, audio, and print)
o books may have different editions which will have unique rows
• Every item has item copies
• Every item copy has an item ID, copy number, copy type, and status
o copy number is the ID of the specific copy of an item and not the item itself
o copy type is the type of the item (e.g. e-book, audio, and print)
o status of the item copy indicates whether it is available or checked out
• Every future item has an ID, title, author, edition, genre, quantity, type, and arrival date
• Every person has an ID, first name, last name, age, and owing amount
• Every event has an ID, name, date, room, start time, end time, fee, recommended age
• A person can checkout and return multiple items
• A person can sign up for multiple events
• Every checked-out item has a due date of three weeks after that item was checked out
• Every person will be fined for each day that an item is overdue
• Every staff member of the library is a person
• Every staff member will have an ID, first name, last name, age, gender, and role
• Every volunteer will count as a staff member with volunteer as their role


## Entity-Relationship Diagram
![Diagram](https://raw.github.com/GumpacG/Library-DB-app/master/ER diagram.png)
