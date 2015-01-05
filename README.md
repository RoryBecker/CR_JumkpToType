'Jump to Type' for CodeRush 
==========

This plugin provides an additional menu item on the Navigate menu.

It allows the user to jump from a variable reference, to the variable's type's declaration.

Usage
===
Simply place you caret on a reference to a variable and press **Ctrl+Alt+N** (Navigate Shortcut)

One of the options should be to navigate to the **Type Declaration**. If this is selected then a marker will be dropped and CodeRush will navigate to the declaration of that variable's type.
[](./Screenshots/NavigateTypeDeclaration.png)

Optional Configuration
======

You can also configure a shortcut to directly trigger this navigation. 

Shortcuts may be configured via the [DevExpress\Options ... IDE\Shortcuts](http://community.devexpress.com/blogs/rorybecker/archive/2010/10/05/binding-keys-in-coderush.aspx) page.

In this case you bind to the 'Navigate' command passing 'Type Declaration' as a parameter.

[](./Screenshots/NavigateShortcut2.png)

You should also configure the shortcut to only work whilst the code editor has focus. This is done through the contextpicker. Locate the **Focus\Documents\Source\Code Editor** context and place a checkmark next to it. This will only allow this shortcut to operate when this context evaluates to true.

[](./Screenshots/ContextFocusCodeEditor.png)

[](./Screenshots/NavigateShortcut1.png)

Credits
======

Author: [Mark Miller](http://devexpress.com/mark ) 
