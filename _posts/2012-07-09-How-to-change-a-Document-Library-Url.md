---
layout: post
title: How to change a Document Library Url
byline: The Easy Way
category: Professional
tags:
- SharePoint
---

How  many times did you want to change the Url of a List or Document Library after it is created?

This is a common situation to who works with SharePoint, when you used international characters in the Name or you just want a long description and a short Url.

Suppose that you want to create a document library with the name "Façade".

Insert "Façade" in the Name and create the library (as you can see below).

[A1]: /img/posts/how-to-change-a-document-library-url/create-the-library.png
[A2]: /img/posts/how-to-change-a-document-library-url/create-the-library-thumb.png "Create the library"
[![Create the library][A2]][A1]

The result is that the Url of the library will be “Faade”, SharePoint automatically removes the invalid characters from the Url:

<p class="orangetext">http://sharepointserver/<span class="highlight">Faade</span>/Forms/AllItems.aspx</p>

Now, we would like to correct this but there is no option available:

[B1]: /img/posts/how-to-change-a-document-library-url/no-option-available.png
[B2]: /img/posts/how-to-change-a-document-library-url/no-option-available-thumb.png "No option available"
[![No option available][B2]][B1]

So, how can I change the Url of the document library to a meaningful one? You can search all over the web interface and there is just no option available for this, I even searched in the object model and even there I did not find an option to changed it after creation.

The normal solution is to delete the library, create a new one and give it the Name “Facade”, then go and change the name again and put “Façade”. But when you already have documents in the document library this is not an option.

Fortunately there is another way:
The Solution

On the library, select “Library” in the Ribbon and then the option “Open with Explorer”:

[C1]: /img/posts/how-to-change-a-document-library-url/open-with-explorer.png
[C2]: /img/posts/how-to-change-a-document-library-url/open-with-explorer-thumb.png "Open Library With Explorer"
[![Open Library With Explorer][C2]][C1]

Then go up one folder and rename through Windows Explorer the name of the library from “Façade” to “Facade”.

[D1]: /img/posts/how-to-change-a-document-library-url/rename-through-windows-explorer.png
[D2]: /img/posts/how-to-change-a-document-library-url/rename-through-windows-explorer-thumb.png "Rename through Windows Explorer"
[![Rename through Windows Explorer][D2]][D1]

This will change both the Url and the Display Name to “Facade”.

Now you only have to go to “Library Settings” –> “Title, description and navigation” and change the Name back to Façade.

And you’re done:

[E1]: /img/posts/how-to-change-a-document-library-url/and-you-are-done.png
[E2]: /img/posts/how-to-change-a-document-library-url/and-you-are-done-thumb.png "And you are done"
[![And you are done][E2]][E1]

I hope this will help!!
