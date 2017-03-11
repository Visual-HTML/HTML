# HTML
HTML Structure Codes


Current Validator : https://validator.w3.org/nu/


------

> Test source of code : search instruction: 

https://api.github.com/search/code?q=repo:Visual-HTML/HTML+calculator

this instruction is search term: +calculator
source/data source/connection: https://api.github.com/search/code?q=repo:Visual-HTML/HTML

* what is the role /needs at editor level for this ? none : it is the designer logic ? no...
* you build and define a query model, they all end to Editor as an AddReference()/IncludeDynamicScript()
* this is the principle, it's to open to a variable toolbar, a variable designer, a variable user-control toolset...

- Editor must be able to get content from this "Codes Source", handle a list of "Codes Sources", code built within editor will support other codes as AddReference/IncludeDynamicScript does... you can avoid using them (not the objective) but for a reason or another you may need to process code injection otherwise and it's allowed because you are within a web browser environment (once your code is loaded you get the entire web browser environment available).

- Editor should provide a whitelisting support for those data sources: in a web server environment, these extra-data will allow or deny code injection from "Code Sources", restrict the set of data source: for security or document quality.
Security: ensure code loaded are for the initial "author support" purpose or selection of sources that satisfy or may satisfy authoring needs or ... .
Quality: ensure document is conform to checker grammar state or generated document is processable by other programs/applications in a global information/knowledge managemenet project or ... .

? what about all this when editor is saved local to a computer, deployed on another web server... //TODO:!

-- this "Codes Source" is defined as a distributed support (endless?) for end-user :  the fact is that editor and designer must expose easy to use authoring objects to end-user, even until the transformation from one object to another (this is possible on well-structured codes (ref. Strong Typing) or simple HTML code structure : a h1 with 3 p can become a h1 with ul/+3 li ...?

