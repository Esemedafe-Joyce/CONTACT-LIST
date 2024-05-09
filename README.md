# CONTACT-LIST.

This project demonstrates storing contact information in an XML file. You can manage contacts using a text editor or an XML parsing library.

 **Features**
 
- Store names, emails, and phone numbers.
- Add, edit, and delete contacts.

**Getting Started**
1. Create an XML file named *contacts.xml*.
2. Add the following root element:

**XML**

`<contacts>
</contacts>`

```diff
-Use code with caution.
```

3. Define the contact structure:
   
**XML**


```
<contacts>
      <contact>
        <name>John Doe</name>
        <email>john.doe@example.com</email>
        <phone>123-456-7890</phone>
      </contact>
  </contacts>
```
  
  
```diff
-Use code with caution.
```

**Using the Contact List**

- **Text Editor**: Manually edit the XML file to add, edit, or delete contacts.
- **XML Parsing Library**: Use libraries like `DOM` or `SAX` in your preferred programming language for programmatic management.

Using an HTML interface and JavaScript's DOM manipulation capabilities, the project allows for dynamic creation of new contact entries within the XML data, including job titles.

**Further Exploration**

- Add more complex elements like addresses or birthdays.
- Implement search functionality based on contact details.
- Explore using XML parsing libraries like `DOM` or `SAX` to manage contacts programmatically.
