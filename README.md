# Central-National-Library
This folder holds the source code of the database project.

A library offers a book reservation service. A library management information system is to be developed, characterized by its address, phone number, the name of the responsible person, and weekly opening hours.

The system manages books, with copies available in a certain quantity. Each book is associated with a status: "borrowed" or "available."

Library users can register by providing their personal information and an arbitrary number of contact details (phone, mobile, email), specifying their preferred communication method.

When processing a loan, librarians can check the availability of book copies. If the book is available, the system returns the shelf and position where the book can be picked up. Since the library is part of a network of partner libraries, if no copies are available, the librarian can check which other libraries in the network have the book and request a transfer. Similarly, other libraries can make transfer requests. In this case, the book is marked as "borrowed by another library," and the destination library is tracked. Transfers between libraries are managed via phone communication between librarians.

Upon receiving a copy, the user can request to keep the book for consultation for 1, 2, or 3 months.

Librarians have the ability to generate a report indicating which borrowed books have not yet been returned and the information of the user currently in possession of the book. The contact details allow the librarian to get in touch to request the return of the book.

A book that has not been borrowed in the past 10 years is removed from the library's active collection. This operation is performed by the administrators of the library network. The record associated with the book is not deleted, but the book can no longer be loaned to users. Any ongoing loans remain valid until the book is returned.
