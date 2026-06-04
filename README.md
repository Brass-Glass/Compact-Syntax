<h1 style="text-align:center;font-family:helvetica;letter-spacing:3px;font-size:300%;margin-top:0px">
    Compact Syntax 4.0
</h1>

![cover](https://github.com/Brass-Glass/Compact-Syntax/blob/3ae22f5562a76cc86a234ec889ae3329931d0b5d/images/cover.png?raw=true)

### Syntax-highlighting for **Compact**, the language.
✧ About
===

**Compact** is a text-based language made using *Scratch*, the block-based language.\
It was designed with one idea in mind: to create a language with as **little blocks** as possible.\
It currently sits at **<span style="font-size:125%;">36</span> blocks**, but that can always change!\
*※ The project will be able to be viewed [here](https://example.org), once it is shared!*

⚝ How to Install
===

**Obtain the files** by downloading the .ZIP of this repository, and **unzip** the compressed folder.\
Find the **extensions** folder of Visual Studio Code (`user/.vscode/` for Windows, as an example).\
**Move** this extension’s folder to the extension folder.\
※ *this is only if you’re getting this from GitHub; with other sources, please follow their instructions!!*\
And **that’s all**! To have changes go into-effect, reload the window or close & reöpen the instance.\
Make sure your file is a `.cpt` or a `.compact` file, and highlighting should appear :D

☆ Syntax
===

Compact relies on the **operation** command, the *only* function of the language (ignoring the compiler).\
It takes one input, computing `[input] + (var1 / var2)` and saving it to an output variable.\
It can also receive one key-input, added-on to the above equation.\
The syntax looks like:
```compact
input output key-input
```
Inputs can be either **numbers** (denoted with a decimal) or **variables** (no decimal), output being a variable.\
Example:
```compact
25. 13
48 72
-534. 68 left arrow
```
There also exists the **constant** `i`, which equals `Infinity`, able to be an input.\
This proves useful for operations such as addition, like below, which does `var15 + 3 ⇒ var18`:
```compact
i 2
3. 1
1. 2
15 18
```
**Conditionals** compare two values, skipping the code in-between if the value is false.\
An example of this syntax is shown below, where the condition `var22 > var51` is being checked.
```compact
> 22 51
    [code goes here]
end
```
**While-loops** are simply modified conditionals, moving the code-reader to the top of the loop upon reaching the bottom.\
It only requires a few modifications to the conditional syntax.\
※ *note that indentation is not necessary! it’s only done for readability*
```compact
W
> 22 51
    [code goes here]
endW
```
Conditionals can also receive **key-inputs**—up to two!\
They are simply appended to the regular syntax, a double-space present if there are two key-inputs.\
The condition `var22 + A > var51 + left arrow` can be seen below.\
※ *one key-input can be done—just don’t add the double-space or second input*
```compact
> 22 51 a  left arrow
    [code goes here]
end
```
**Hash-variables** are special variables which can edit the next line.\
If, for example, you want to get the value of `var15`, turn that value into a variable, and read that value, you would use hash-variables!\
In the following code, if `var15 = 25`, and `var25 = 104`, the value `104` will be saved to `var63`.\
※ *confused? this is an advanced topic; for example, using hash-variables across conditionals requires more mathematics due to their complexity*
```compact
15 #1
0 63
```
Feel the need to write a **comment**?\
Any plain text is automatically understood as a comment, skipped by the compiler.\
An example is below!
```compact
this is a comment
also a comment!

and this too
```
If there is an improperly-formatted piece-of-code, an error will be highlighted.\
An easy way to see this is by missing an argument in a conditional or putting a number into the output of an operation.
```compact
> 22
    537. 81.
end
```

♡ Closing
===

I hope you enjoy this highlighting-extension!\
If you like it, please feel free to **write a review**!\
Otherwise, have a great day :\]\
*— brassy ♡*

