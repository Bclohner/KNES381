<html>
<h1 align="center">This is my Centered Document Title</h1>
<h2 align="center"> And a Second Heading Too</h2>
</html>

## Table of Contents
- [Right Aligned Image](#right-aligned-image)
- [Hyperlink](#hyperlink-to-another-file-in-the-repository)
- [Scientific Notation](#scientific-notation)
- [Code Block](#code-block)
- [Page Grading](#page-grading)


## Right Aligned Image

<img src="https://images.unsplash.com/photo-1602418013963-c1f017b3bb63?q=80&w=1470&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" align="right" alt="An image of a cat" width="300">
Please enjoy this image of a cat I found on the internet.
<br clear="all">


## Hyperlink to Another File in the Repository
[Click Here](readme.md) to see another file in the repository.

## Scientific Notation
I also have an example of scientific notation with subscript here: VO<sub>2</sub>. But wait! Theres more! I can also use dot notation! V&#x0307;O<sub>2</sub>.


## Code Block
This is a Matlab function I wrote for KNES 463 displayed as a code block.
<pre><code>
function [Derivative]=centralderiv(x,dt)  
    xdot=zeros(size(x));
    for i=1:length(x) % the first element in a vector
        if i==1
            xdot=(x(i+1)-x(i))/(dt);
            Derivative(i)=xdot;
        elseif i==length(x) % the last element in a vector
            xdot=(x(i)-x(i-1))/dt; 
            Derivative(i)=xdot;
        else %every element in between
            xdot=(x(i+1)-x(i-1))/(2*dt); %formula for the central derivative
            Derivative(i)=xdot;
        end
    end
end
</code></pre>

## Page Grading
As per the D2L dropbox, we are required to state the grade we hope to achieve. Based on the assignment requirements, I hope to get an A+.
<br>
Here is a summary of the document features included that meet the requirements for an A+

- Minimum Requirements
     - A centered Title
     - An image positioned to the right of the text
     - A hyperlink to another markdown file
     - Scientific notation using subscript
- Higher Achievement
     - A table of contents using header anchor links
     - A code block
- Highest Distinction
     - Scientific dot notation


  

