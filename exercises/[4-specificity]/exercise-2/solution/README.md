# Questions & Answers
1. * Q:  After looking at the HTML and CSS files, figure out what color each paragraph will have. Write your answers in the following form: Paragraph [x] - color. Calculate the specificity of each applied property.
    * A: 
        * Paragraph 1 - red ( Class + Id = 10 + 100 = 110 )
        * Paragraph 2 - brown ( Class + Class + Id = 10 + 10 + 100 = 120 )
        * Paragraph 3 - purple ( Id = 100 )
        * Paragraph 4 - green ( Type = 1 )

2. * Q: Make it so the paragraphs have the following colors:
        * Paragraph 1 - yellow
        * Paragraph 2 - blue
        * Paragraph 3 - green
        * Paragraph 4 - green
    * A: We have to apply the !important keyword to the lower-specificity yellow property of the '#p1' paragraph, the lower-specificity blue property of the '#p2' paragraph, and the lower-specificity green p type property. 
    This way, firstly, all colors will be overridden by green. Then, when it will reach the yellow property of the '#p1', it being a higher specificity than the type selector and containing the !important keyword, the green color for the first paragraph will be overriden by yellow. 
    Lastly, when the '.container #p2' selector will be reached, it being higher specificity than the type one and containing the !important keyword,  the type selector will be overridden for the second paragraph as well, making it blue.