This Registration Form project is a project the free code camp goes through to learn the basics of html forms.

My notes:
1. The vh (viewport height) is equal to 1% of the height of the viewport.
2. The method attribute specifies how to send form-data to the URL specified in the action attribute. GET or POST can be used in this attribute to do specific actions with the form.
3. The rem unit stands for root em, which is relative to the font size of the html element.
4. The label elements are inline by default and display style neeeds to specified as block to make them not appear side by side.
5. Reminder: the for attribute in input elements links it with the label elements. Label will use for while input will use id attributes to link them.
6. Specifying the type attribute of the form element is imperative for the browser to know what kind of data it should expect. If none specified, then the default will be text.
7. The first input element with a type of submit is automatically set to submit its nearest parent form element.
8. Certain type attribute values have built in validation (ex: type="email" has the @ value validation)
9. For password type, patter attribute could be added to specify validations and takes in regular expressions (pattern="[a-z0-5]{8,}"). This stands for 8 or more lower case letter or 0 to 5 digits.
10. The name attribute can be used to related two radio inputs. Just make sure they share the same name.
11. The checked attribut in radio input element will load the form where that radio button automatically checked.
12. Best accessibility practices require input (uses id) and label (uses for) elementd being linked. They should have the same values.
13. The input type file is used if the user needs to upload a file.
14. The select element can be used to add a dropdown to the form. It is a container for a group of option elements. Each option element acts as a label for each dropdown option. Both of the element require a closing tag.
15. To make it useful, each option element must have a value attribute. Without which, the text content of the option will be submitted to the server.
16. The textarea element acts the same as an input element with a text type. However, it is a great feature of being able to receive multi-line text. The rows and cols attribute to change the textarea elements' size.