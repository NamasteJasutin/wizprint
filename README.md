**wprint; A Small Gimmick that makes printing tasks to console just a bit more fun by introducing a Wizard that will tell you your customized message in a bubble

> wprint("Hello, world!") 


>
> .://+///:-`   .://+++oo+++++//:-.`-:://////::-
> s+++++++++oo+oo+++++++++++++++++oo+++++++++++os. 
> 'o˖˖Hello,˖world!˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖oo
>  :/+++///::+ooooooo+os+++++s+oooo+oooooooooooo+/`
>                        +o++o+`   `````     ```
>                        -s+.
>                           🧙

Standard messages show a small bubble, you can expand this however by adding a signature with the option signed="Pythonuigi"
>wprint("Hello, Pythonario", signed="Process Peach", wiz="p")



>  .://+///:-`  .://+++oo++++//:-.`-:://////::-
>   s+++++++++oo+oo++++++++++++++++oo++++++++++os. 
> /s˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖os`
> :s˖˖Hello,˖Pythonario˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖os
> :s˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖os
> 'o˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖oo
> .os˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖Process˖Peach˖˖˖˖˖˖˖˖˖oo
> 'o˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖˖oo
>  :/+++///::+ooooooo+os+++++s+oooo+oooooooooooo+/`
>                        +o++o+`   `````     ```
>                        -s+.
>                           👸

Try it with:
> from wizprint import wprint, fnt
> wprint("Hello, Pythonario", signed="Process Peach", wiz="p", background=fnt.Y, foreground=fnt.R)
All options:
> wprint(message="", background=fnt.black, foreground=fnt.B, bgchar='˖', signed="", wiz="w")

> from wizprint import fnt
For more font coloring options.

More info on fnt:
Format console: 
Colors: # For Blue use fnt.B
(P)urple, (B)lue, (G)reen, (Y)ellow, (R)ed.
Properties: # For bold use fnt.b
(b)old, (u)nderline, (i)talic, (c)lear
Example: f"{fnt.B}Blue {fnt.c}I am. {fnt.i}Roses {fnt.c}{fnt.b}are {fnt.R}Red{fnt.c}"
            Blue /     Clear /     Italic /      Clear / Bold /      Red /   Clear /

You can find Emoji's in fnt.emojis, I've included a few:
🧙, 👸, 👵, 👴, 🎅, 👮, 🕵, 👩, 👨, 👩, 🦸, 🧚.

