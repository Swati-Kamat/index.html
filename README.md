
☆ An HTML registration form is a structured set of elements used to collect user input on a webpage. It is defined by the <form> tag, which acts as a     container for all input fields, buttons, and other related components. 

☆ Core Theory and Elements:
  <form> tag: The fundamental element that defines the form. It has key attributes:
  action: Specifies the URL where the form data will be sent upon submission (e.g., a server-side script).
  method: Specifies the HTTP method to use, typically POST (for sensitive data like passwords) or GET. POST keeps the data hidden in the HTTP request     body.
  <input> tag: The most versatile element for gathering data, whose behavior changes based on the type attribute. Key types for a registration form       include:
  type="text": For single-line text input (e.g., first name, last name).
  type="email": For email addresses; browsers can validate for a proper email format.
  type="password": Masks the characters as the user types for security.
  type="radio": For selecting one option from a set of choices (e.g., gender).
  type="checkbox": For selecting multiple options (e.g., terms and conditions, interests).
  type="submit": Creates a button that submits the form data to the action URL.
  <label> tag: Defines a label for an input element. The for attribute of the <label> should match the id attribute of the <input> to bind them           together, improving accessibility for screen readers and usability for users.
  <button> tag: Used to create a clickable button, often with type="submit" to send the form.
  <select> and <option> tags: Used to create a dropdown list for selecting from predefined choices (e.g., country, course selection).
  <textarea> tag: For multi-line text input, such as an address or a bio.
  <fieldset> tag: Used to group related form elements together (e.g., "Personal Information" or "Account Details"), which improves semantics and           accessibility. A <legend> tag is used within the <fieldset> to provide a title for the group.
