#Paragraphs

```The <p> element defines a paragraph 

EXAMPLE: <p>this is a paragraph</p>

If you add random spaces in the paragraph, the browser will ignore it and take out the extra spaces, for example these two paragraphs will be displayed the same: 

<p>This is the first paragraph</p>

<p>This    is the               first paragraph</p>```

#HTML Line breaks 

```To add a line break (add a new line) into the paragraph element, you can use the <br> tag wherever you want a new line to be placed into the content of the paragraph element

EXAMPLE: <p>This is<br>a line<br>break</p>

OUTPUT: This is 
        a line
        break

the <br> element is a single element, an end tag is not needed```

#The line space problem

```If you try to do: 

<p>
	Hello

	I am

	Speedy
</p>

The output will still be: 

Hello I am Speedy

To avoid this you use the <pre> element to save the text preformat and preserves both the space and line breaks.

<pre>
	Hello

	I am
	
	Speedy
</pre>

Output: 

	Hello

	I am

	Speedy``` 




