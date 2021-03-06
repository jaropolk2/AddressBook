# API Methods' detail.
--------------------

#### This document provides description of each method/function in the API. Here is the list of methods with their description.

##### add_group(GroupName)
> Description:  Adds a group to group list of address book.

> Params:       GroupName as str

##### add_persson(FirstName, LastName, StreetAddress = [], Email = [], Phone = [], Group = [])
> Description:  Adds a person to the address book.

> Params:       Details of person. "FirstName and LastName" as str. "StreetAddress, Email, Phone, Group" can be multiple for person, thus passed as a list of str. First Name and Last Name must be provided.

##### count_persons()
> Description:  Prints and returns the number of entities in the address book.

> Returns:      Count of person(s) in address book.

##### get_address_book()
>Description:  Returns a list of AddressBook object(s) stored in the address book.

>Returns:      List of AddressBook object(s).

##### clear_address_book()
> Description:  Returns the list of AddressBook object(s) stored in address book and clears the address book entries.

> Returns:      List of AddressBook object(s).

##### clear_address_book_groups()
> Description:  Returns and clears the list of address book groups.

> Returns       List of address book group(s).

##### print_short_info(AddressBookObject)
> Description:  Prints the short info of an AddressBook object as "FirstName, LastName and Group".

> Params:       AddressBook object.

##### get_all_groups()
> Description:  Prints and returns a list of current group(s) in the address book.

> Returns:      List of (str) Group(s) of current address book.

##### get_persons_in_group(GroupName)
> Description:  Prints and returns a list of AddressBook object(s) with the given groupName.

> Params:       GroupName as str.

> Returns:      List of AddressBook object(s).

##### print_person_info(AddressBookObject)
> Description:  Prints a complete info of AddressBook object.

> Params:       AddressBook object.

##### get_group_info_of_person(FirstName)
> Description:  Prints and returns a list of group(s) against the given firstName.

> Params:       FirstName as str.

> Returns:      List of (str) group(s).

##### get_person_info_by_name(Name)
> Description:  Prints a short info of person with the provided name and returns a list AddressBook object(s) matching with provided name.

> Params:       Name as str.

> Returns:      List of AddressBook object(s).

##### get_person_info_by_email(Email)
> Description:  Prints a short info of person with the provided email and returns a list AddressBook object(s) matching with provided email address.

> Params:       Email as str.

> Returns:      List of AddressBook object(s).
