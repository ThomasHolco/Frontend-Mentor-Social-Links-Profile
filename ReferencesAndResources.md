From SheCodes.io:
http://shecodes.io/athena/37839-how-to-put-content-in-a-box-or-border-using-css

Changing Input When Interacting with Content In Border:
input {
    background-color: lightblue; /* Change background color */
    color: darkblue; /* Change text color */
    border: 1px solid blue; /* Change border color */
    padding: 10px; /* Add some padding */
    border-radius: 5px; /* Optional: round the corners */
}

Button: button {
    background-color: #4CAF50; /* Green background */
    border: none; /* Remove borders */
    color: white; /* White text */
    padding: 15px 32px; /* Padding */
    text-align: center; /* Centered text */
    text-decoration: none; /* Remove underline */
    display: inline-block; /* Inline block */
    font-size: 16px; /* Font size */
    margin: 4px 2px; /* Margin */
    cursor: pointer; /* Pointer cursor on hover */
    border-radius: 4px; /* Rounded corners */
    transition: background-color 0.3s; /* Smooth transition for background color */
}

button:hover {
    background-color: #45a049; /* Darker green on hover */
}




From thesitewizard.com:
https://www.thesitewizard.com/css/rectangular-box-border.shtml

Borders:

1. Create the HTML for the block. For this tutorial, I shall use a DIV block to enclose the text/pictures.

<div class="boxed">
  This text is enclosed in a box.
</div>

I gave the DIV block a class of "boxed" but you can of course use some other valid CSS class name. Replace my dummy content with your actual text and/or images.

2. Next, you will need to style the DIV box by adding a border. In your CSS section, or external CSS file, add the following code:

.boxed {
  border: 1px solid green ;
}


From w3schools.com:
https://www.w3schools.com/css/css_boxmodel.asp

Content - The content of the box, where text and images appear
Padding - Clears an area around the content. The padding is transparent
Border - A border that goes around the padding and content
Margin - Clears an area outside the border. The margin is transparent


https://www.w3schools.com/howto/howto_website_create_linktree.asp:  Referring to example 2

Used Chatgpt to understand how to implement a mobile view for the webpage. Almost all code (minus what was already prepped and the style-guide.md) was done by me. Only made adjustments based on what Chatgpt had suggested which was mostly just changing the widths to percentages and making max-widths to with them. Also got a quick rough overview of what the "vh" measurement was in coorelation to other measurements like pixels or rems.