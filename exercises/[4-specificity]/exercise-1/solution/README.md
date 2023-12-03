# Questions & Answers
1. * Q: Check out both the HTML and CSS files within this folder and try to identify what color the paragraph will have. Calculate the specificity score for each of the two selecting methods.
    * A: The color of the paragraph will be green. The specificity of the first selection, namely the one with the universal selector, is 0. The specificity of the second selection, namely the one with the ID selector, is 100.
    
2. * Q: Make the selection with the lower specificity be applied.
    * A: The selection with the lower specificity is the one using the universal selector. In order to make it be applied, we can use the !important keyword following the property. You can find the practical solution in the 'styles.css' file in this folder.